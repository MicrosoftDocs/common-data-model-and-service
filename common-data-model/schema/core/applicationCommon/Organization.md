---
title: Organization - Common Data Model | Microsoft Docs
description: This describes the Organization entitity.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/14/2019
ms.author: nebanfic
---

# Organization

Top level of the Microsoft Dynamics 365 business hierarchy. The organization can be a specific business, holding company, or corporation.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/Organization.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /Organization  
- [/foundationCommon/Organization](foundationCommon/Organization.md "/core/applicationCommon/foundationCommon/Organization.cdm.json/Organization")  
- [/foundationCommon/crmCommon/projectCommon/scheduling/Organization](foundationCommon/crmCommon/projectCommon/scheduling/Organization.md "/core/applicationCommon/foundationCommon/crmCommon/projectCommon/scheduling/Organization.cdm.json/Organization")  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[organizationId](#organizationId)|Unique identifier of the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[name](#name)|Name of the organization. The name is set when Microsoft CRM is installed and should not be changed.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[userGroupId](#userGroupId)|Unique identifier of the default group of users in the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[privilegeUserGroupId](#privilegeUserGroupId)|Unique identifier of the default privilege for users in the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[recurrenceExpansionJobBatchSize](#recurrenceExpansionJobBatchSize)|Specifies the value for number of instances created in on demand job in one shot.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[recurrenceExpansionJobBatchInterval](#recurrenceExpansionJobBatchInterval)|Specifies the interval (in seconds) for pausing expansion job.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[fiscalPeriodType](#fiscalPeriodType)|Type of fiscal period used throughout Microsoft CRM.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[fiscalCalendarStart](#fiscalCalendarStart)|Start date for the fiscal period that is to be used throughout Microsoft CRM.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[dateFormatCode](#dateFormatCode)|Information about how the date is displayed throughout Microsoft CRM.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[dateFormatCode_display](#dateFormatCode_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[timeFormatCode](#timeFormatCode)|Information that specifies how the time is displayed throughout Microsoft CRM.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[timeFormatCode_display](#timeFormatCode_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[currencySymbol](#currencySymbol)|Symbol used for currency throughout Microsoft Dynamics 365.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[weekStartDayCode](#weekStartDayCode)|Designated first day of the week throughout Microsoft Dynamics 365.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[weekStartDayCode_display](#weekStartDayCode_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[dateSeparator](#dateSeparator)|Character used to separate the month, the day, and the year in dates throughout Microsoft Dynamics 365.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[fullNameConventionCode](#fullNameConventionCode)|Order in which names are to be displayed throughout Microsoft CRM.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[fullNameConventionCode_display](#fullNameConventionCode_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[negativeFormatCode](#negativeFormatCode)|Information that specifies how negative numbers are displayed throughout Microsoft CRM.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[negativeFormatCode_display](#negativeFormatCode_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[numberFormat](#numberFormat)|Specification of how numbers are displayed throughout Microsoft CRM.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isDisabled](#isDisabled)|Information that specifies whether the organization is disabled.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[disabledReason](#disabledReason)|Reason for disabling the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[kbPrefix](#kbPrefix)|Prefix to use for all articles in Microsoft Dynamics 365.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[currentKbNumber](#currentKbNumber)|First article number to use. Deprecated. Use SetAutoNumberSeed message.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[casePrefix](#casePrefix)|Prefix to use for all cases throughout Microsoft Dynamics 365.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[currentCaseNumber](#currentCaseNumber)|First case number to use. Deprecated. Use SetAutoNumberSeed message.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[contractPrefix](#contractPrefix)|Prefix to use for all contracts throughout Microsoft Dynamics 365.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[currentContractNumber](#currentContractNumber)|First contract number to use. Deprecated. Use SetAutoNumberSeed message.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[quotePrefix](#quotePrefix)|Prefix to use for all quotes throughout Microsoft Dynamics 365.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[currentQuoteNumber](#currentQuoteNumber)|First quote number to use. Deprecated. Use SetAutoNumberSeed message.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[orderPrefix](#orderPrefix)|Prefix to use for all orders throughout Microsoft Dynamics 365.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[currentOrderNumber](#currentOrderNumber)|First order number to use. Deprecated. Use SetAutoNumberSeed message.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[invoicePrefix](#invoicePrefix)|Prefix to use for all invoice numbers throughout Microsoft Dynamics 365.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[currentInvoiceNumber](#currentInvoiceNumber)|First invoice number to use. Deprecated. Use SetAutoNumberSeed message.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[uniqueSpecifierLength](#uniqueSpecifierLength)|Number of characters appended to invoice, quote, and order numbers.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[createdOn](#createdOn)|Date and time when the organization was created.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[modifiedOn](#modifiedOn)|Date and time when the organization was last modified.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[fiscalYearFormat](#fiscalYearFormat)|Information that specifies how the name of the fiscal year is displayed throughout Microsoft CRM.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[fiscalPeriodFormat](#fiscalPeriodFormat)|Information that specifies how the name of the fiscal period is displayed throughout Microsoft CRM.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[fiscalYearPeriodConnect](#fiscalYearPeriodConnect)|Information that specifies how the names of the fiscal year and the fiscal period should be connected when displayed together.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[languageCode](#languageCode)|Preferred language for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[sortId](#sortId)|For internal use only.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[dateFormatString](#dateFormatString)|String showing how the date is displayed throughout Microsoft CRM.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[timeFormatString](#timeFormatString)|Text for how time is displayed in Microsoft Dynamics 365.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[pricingDecimalPrecision](#pricingDecimalPrecision)|Number of decimal places that can be used for prices.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[showWeekNumber](#showWeekNumber)|Information that specifies whether to display the week number in calendar displays throughout Microsoft CRM.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[nextTrackingNumber](#nextTrackingNumber)|Next token to be placed on the subject line of an email message.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[tagMaxAggressiveCycles](#tagMaxAggressiveCycles)|Maximum number of aggressive polling cycles executed for email auto-tagging when a new email is received.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[systemUserId](#systemUserId)|Unique identifier of the system user for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[grantAccessToNetworkService](#grantAccessToNetworkService)|For internal use only.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[allowOutlookScheduledSyncs](#allowOutlookScheduledSyncs)|Indicates whether scheduled synchronizations to Outlook are allowed.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[allowMarketingEmailExecution](#allowMarketingEmailExecution)|Indicates whether marketing emails execution is allowed.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[sqlAccessGroupId](#sqlAccessGroupId)|For internal use only.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[currencyFormatCode](#currencyFormatCode)|Information about how currency symbols are placed throughout Microsoft Dynamics CRM.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[currencyFormatCode_display](#currencyFormatCode_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[fiscalSettingsUpdated](#fiscalSettingsUpdated)|Information that specifies whether the fiscal settings have been updated.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[reportingGroupId](#reportingGroupId)|For internal use only.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[tokenExpiry](#tokenExpiry)|Duration used for token expiration.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[shareToPreviousOwnerOnAssign](#shareToPreviousOwnerOnAssign)|Information that specifies whether to share to previous owner on assign.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[acknowledgementTemplateId](#acknowledgementTemplateId)|Unique identifier of the template to be used for acknowledgement when a user unsubscribes.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who last modified the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[integrationUserId](#integrationUserId)|Unique identifier of the integration user for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[trackingTokenIdBase](#trackingTokenIdBase)|Base number used to provide separate tracking token identifiers to users belonging to different deployments.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[businessClosureCalendarId](#businessClosureCalendarId)|Unique identifier of the business closure calendar of organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[allowAutoUnsubscribeAcknowledgement](#allowAutoUnsubscribeAcknowledgement)|Indicates whether automatic unsubscribe acknowledgement email is allowed to send.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[allowAutoUnsubscribe](#allowAutoUnsubscribe)|Indicates whether automatic unsubscribe is allowed.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[picture](#picture)|For internal use only.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[versionNumber](#versionNumber)|Version number of the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[trackingPrefix](#trackingPrefix)|History list of tracking token prefixes.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[minOutlookSyncInterval](#minOutlookSyncInterval)|Minimum allowed time between scheduled Outlook synchronizations.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[bulkOperationPrefix](#bulkOperationPrefix)|Prefix used for bulk operation numbering.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[allowAutoResponseCreation](#allowAutoResponseCreation)|Indicates whether automatic response creation is allowed.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[maximumTrackingNumber](#maximumTrackingNumber)|Maximum tracking number before recycling takes place.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[campaignPrefix](#campaignPrefix)|Prefix used for campaign numbering.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[sqlAccessGroupName](#sqlAccessGroupName)|For internal use only.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[currentCampaignNumber](#currentCampaignNumber)|Current campaign number. Deprecated. Use SetAutoNumberSeed message.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[fiscalYearDisplayCode](#fiscalYearDisplayCode)|Information that specifies whether the fiscal year should be displayed based on the start date or the end date of the fiscal year.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[siteMapXml](#siteMapXml)|XML string that defines the navigation structure for the application.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isRegistered](#isRegistered)|For internal use only.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[reportingGroupName](#reportingGroupName)|For internal use only.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[currentBulkOperationNumber](#currentBulkOperationNumber)|Current bulk operation number. Deprecated. Use SetAutoNumberSeed message.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[schemaNamePrefix](#schemaNamePrefix)|Prefix used for custom entities and attributes.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[ignoreInternalEmail](#ignoreInternalEmail)|Indicates whether incoming email sent by internal Microsoft Dynamics 365 users or queues should be tracked.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[tagPollingPeriod](#tagPollingPeriod)|Normal polling frequency used for email receive auto-tagging in outlook.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[trackingTokenIdDigits](#trackingTokenIdDigits)|Number of digits used to represent a tracking token identifier.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[numberGroupFormat](#numberGroupFormat)|Specifies how numbers are grouped in Microsoft Dynamics 365.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[longDateFormatCode](#longDateFormatCode)|Information that specifies how the Long Date format is displayed in Microsoft Dynamics 365.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[currentImportSequenceNumber](#currentImportSequenceNumber)|Import sequence to use.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[parsedTablePrefix](#parsedTablePrefix)|Prefix used for parsed tables.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[v3CalloutConfigHash](#v3CalloutConfigHash)|Hash of the V3 callout configuration file.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isFiscalPeriodMonthBased](#isFiscalPeriodMonthBased)|Indicates whether the fiscal period is displayed as the month number.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[localeId](#localeId)|Unique identifier of the locale of the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[parsedTableColumnPrefix](#parsedTableColumnPrefix)|Prefix used for parsed table columns.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[supportUserId](#supportUserId)|Unique identifier of the support user for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[AMDesignator](#AMDesignator)|AM designator to use throughout Microsoft Dynamics CRM.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[currencyDisplayOption](#currencyDisplayOption)|Indicates whether to display money fields with currency code or currency symbol.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[currencyDisplayOption_display](#currencyDisplayOption_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[minAddressBookSyncInterval](#minAddressBookSyncInterval)|Normal polling frequency used for address book synchronization in Microsoft Office Outlook.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isDuplicateDetectionEnabledForOnlineCreateUpdate](#isDuplicateDetectionEnabledForOnlineCreateUpdate)|Indicates whether duplicate detection during online create or update is enabled.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[featureSet](#featureSet)|Features to be enabled as an XML BLOB.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[blockedAttachments](#blockedAttachments)|Prevent upload or download of certain attachment types that are considered dangerous.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isDuplicateDetectionEnabledForOfflineSync](#isDuplicateDetectionEnabledForOfflineSync)|Indicates whether duplicate detection of records during offline synchronization is enabled.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[allowOfflineScheduledSyncs](#allowOfflineScheduledSyncs)|Indicates whether background offline synchronization in Microsoft Office Outlook is allowed.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[allowUnresolvedPartiesOnEmailSend](#allowUnresolvedPartiesOnEmailSend)|Indicates whether users are allowed to send email to unresolved parties (parties must still have an email address).|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[timeSeparator](#timeSeparator)|Text for how the time separator is displayed throughout Microsoft Dynamics 365.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[currentParsedTableNumber](#currentParsedTableNumber)|First parsed table number to use.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[minOfflineSyncInterval](#minOfflineSyncInterval)|Normal polling frequency used for background offline synchronization in Microsoft Office Outlook.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[allowWebExcelExport](#allowWebExcelExport)|Indicates whether Web-based export of grids to Microsoft Office Excel is allowed.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[referenceSiteMapXml](#referenceSiteMapXml)|XML string that defines the navigation structure for the application. This is the site map from the previously upgraded build and is used in a 3-way merge during upgrade.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isDuplicateDetectionEnabledForImport](#isDuplicateDetectionEnabledForImport)|Indicates whether duplicate detection of records during import is enabled.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[calendarType](#calendarType)|Calendar type for the system. Set to Gregorian US by default.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[SQMEnabled](#SQMEnabled)|Setting for SQM data collection, 0 no, 1 yes enabled|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[negativeCurrencyFormatCode](#negativeCurrencyFormatCode)|Information that specifies how negative currency numbers are displayed throughout Microsoft Dynamics 365.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[allowAddressBookSyncs](#allowAddressBookSyncs)|Indicates whether background address book synchronization in Microsoft Office Outlook is allowed.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[ISVIntegrationCode](#ISVIntegrationCode)|Indicates whether loading of Microsoft Dynamics 365 in a browser window that does not have address, tool, and menu bars is enabled.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[ISVIntegrationCode_display](#ISVIntegrationCode_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[decimalSymbol](#decimalSymbol)|Symbol used for decimal in Microsoft Dynamics 365.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[maxUploadFileSize](#maxUploadFileSize)|Maximum allowed size of an attachment.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isAppMode](#isAppMode)|Indicates whether loading of Microsoft Dynamics 365 in a browser window that does not have address, tool, and menu bars is enabled.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[enablePricingOnCreate](#enablePricingOnCreate)|Enable pricing calculations on a Create call.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isSOPIntegrationEnabled](#isSOPIntegrationEnabled)|Enable sales order processing integration.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[PMDesignator](#PMDesignator)|PM designator to use throughout Microsoft Dynamics 365.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[currencyDecimalPrecision](#currencyDecimalPrecision)|Number of decimal places that can be used for currency.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[maxAppointmentDurationDays](#maxAppointmentDurationDays)|Maximum number of days an appointment can last.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[emailSendPollingPeriod](#emailSendPollingPeriod)|Normal polling frequency used for sending email in Microsoft Office Outlook.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[renderSecureIFrameForEmail](#renderSecureIFrameForEmail)|Flag to render the body of email in the Web form in an IFRAME with the security='restricted' attribute set. This is additional security but can cause a credentials prompt.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[numberSeparator](#numberSeparator)|Symbol used for number separation in Microsoft Dynamics 365.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[privReportingGroupId](#privReportingGroupId)|For internal use only.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[baseCurrencyId](#baseCurrencyId)|Unique identifier of the base currency of the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[maxRecordsForExportToExcel](#maxRecordsForExportToExcel)|Maximum number of records that will be exported to a static Microsoft Office Excel worksheet when exporting from the grid.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[privReportingGroupName](#privReportingGroupName)|For internal use only.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[yearStartWeekCode](#yearStartWeekCode)|Information that specifies how the first week of the year is specified in Microsoft Dynamics 365.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isPresenceEnabled](#isPresenceEnabled)|Information on whether IM presence is enabled.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isDuplicateDetectionEnabled](#isDuplicateDetectionEnabled)|Indicates whether duplicate detection of records is enabled.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[expireSubscriptionsInDays](#expireSubscriptionsInDays)|Maximum number of days before deleting inactive subscriptions.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isAuditEnabled](#isAuditEnabled)|Enable or disable auditing of changes.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[baseCurrencyPrecision](#baseCurrencyPrecision)|Number of decimal places that can be used for the base currency.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[baseCurrencySymbol](#baseCurrencySymbol)|Symbol used for the base currency.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[maxRecordsForLookupFilters](#maxRecordsForLookupFilters)|Maximum number of lookup and picklist records that can be selected by user for filtering.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[allowEntityOnlyAudit](#allowEntityOnlyAudit)|Indicates whether auditing of changes to entity is allowed when no attributes have changed.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[defaultRecurrenceEndRangeType](#defaultRecurrenceEndRangeType)|Type of default recurrence end range date.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[defaultRecurrenceEndRangeType_display](#defaultRecurrenceEndRangeType_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[futureExpansionWindow](#futureExpansionWindow)|Specifies the maximum number of months in future for which the recurring activities can be created.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[pastExpansionWindow](#pastExpansionWindow)|Specifies the maximum number of months in past for which the recurring activities can be created.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[recurrenceExpansionSynchCreateMax](#recurrenceExpansionSynchCreateMax)|Specifies the maximum number of instances to be created synchronously after creating a recurring appointment.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[recurrenceDefaultNumberOfOccurrences](#recurrenceDefaultNumberOfOccurrences)|Specifies the default value for number of occurrences field in the recurrence dialog.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who last modified the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[getStartedPaneContentEnabled](#getStartedPaneContentEnabled)|Indicates whether Get Started content is enabled for this organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[useReadForm](#useReadForm)|Indicates whether the read-optimized form should be enabled for this organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[initialVersion](#initialVersion)|Initial version of the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[sampleDataImportId](#sampleDataImportId)|Unique identifier of the sample data import job.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[reportScriptErrors](#reportScriptErrors)|Picklist for selecting the organization preference for reporting scripting errors.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[reportScriptErrors_display](#reportScriptErrors_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[requireApprovalForUserEmail](#requireApprovalForUserEmail)|Indicates whether Send As Other User privilege is enabled.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[requireApprovalForQueueEmail](#requireApprovalForQueueEmail)|Indicates whether Send As Other User privilege is enabled.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[goalRollupExpiryTime](#goalRollupExpiryTime)|Number of days after the goal's end date after which the rollup of the goal stops automatically.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[goalRollupFrequency](#goalRollupFrequency)|Number of hours between automatic rollup jobs .|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[autoApplyDefaultonCaseCreate](#autoApplyDefaultonCaseCreate)|Select whether to auto apply the default customer entitlement on case creation.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[autoApplyDefaultonCaseUpdate](#autoApplyDefaultonCaseUpdate)|Select whether to auto apply the default customer entitlement on case update.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[fiscalYearFormatPrefix](#fiscalYearFormatPrefix)|Prefix for the display of the fiscal year.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[fiscalYearFormatPrefix_display](#fiscalYearFormatPrefix_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[fiscalYearFormatSuffix](#fiscalYearFormatSuffix)|Suffix for the display of the fiscal year.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[fiscalYearFormatSuffix_display](#fiscalYearFormatSuffix_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[fiscalYearFormatYear](#fiscalYearFormatYear)|Format for the year.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[fiscalYearFormatYear_display](#fiscalYearFormatYear_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[discountCalculationMethod](#discountCalculationMethod)|Discount calculation method for the QOOI product.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[discountCalculationMethod_display](#discountCalculationMethod_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[fiscalPeriodFormatPeriod](#fiscalPeriodFormatPeriod)|Format in which the fiscal period will be displayed.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[fiscalPeriodFormatPeriod_display](#fiscalPeriodFormatPeriod_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[allowClientMessageBarAd](#allowClientMessageBarAd)|Indicates whether Outlook Client message bar advertisement is allowed.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[allowUserFormModePreference](#allowUserFormModePreference)|Indicates whether individuals can select their form mode preference in their personal options.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[hashFilterKeywords](#hashFilterKeywords)|Filter Subject Keywords|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[hashMaxCount](#hashMaxCount)|Maximum number of subject keywords or recipients used for correlation|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[hashDeltaSubjectCount](#hashDeltaSubjectCount)|Maximum difference allowed between subject keywords count of the email messaged to be correlated|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[hashMinAddressCount](#hashMinAddressCount)|Minimum number of recipients required to match for email messaged to be correlated|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[enableSmartMatching](#enableSmartMatching)|Use Smart Matching.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[pinpointLanguageCode](#pinpointLanguageCode)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[orgDbOrgSettings](#orgDbOrgSettings)|Organization settings stored in Organization Database.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isUserAccessAuditEnabled](#isUserAccessAuditEnabled)|Enable or disable auditing of user access.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[userAccessAuditingInterval](#userAccessAuditingInterval)|The interval at which user access is checked for auditing.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[quickFindRecordLimitEnabled](#quickFindRecordLimitEnabled)|Indicates whether a quick find record limit should be enabled for this organization (allows for faster Quick Find queries but prevents overly broad searches).|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[enableBingMapsIntegration](#enableBingMapsIntegration)|Enable Integration with Bing Maps|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isDefaultCountryCodeCheckEnabled](#isDefaultCountryCodeCheckEnabled)|Enable or disable country code selection.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[defaultCountryCode](#defaultCountryCode)|Text area to enter default country code.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[useSkypeProtocol](#useSkypeProtocol)|Indicates default protocol selected for organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[incomingEmailExchangeEmailRetrievalBatchSize](#incomingEmailExchangeEmailRetrievalBatchSize)|Setting for the Async Service Mailbox Queue. Defines the retrieval batch size of exchange server.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[emailCorrelationEnabled](#emailCorrelationEnabled)|Flag to turn email correlation on or off.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[yammerOAuthAccessTokenExpired](#yammerOAuthAccessTokenExpired)|Denotes whether the OAuth access token for Yammer network has expired|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[defaultEmailSettings](#defaultEmailSettings)|XML string containing the default email settings that are applied when a user or queue is created.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[yammerGroupId](#yammerGroupId)|Denotes the Yammer group ID|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[yammerNetworkPermalink](#yammerNetworkPermalink)|Denotes the Yammer network permalink|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[yammerPostMethod](#yammerPostMethod)|Internal Use Only|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[yammerPostMethod_display](#yammerPostMethod_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[emailConnectionChannel](#emailConnectionChannel)|Select if you want to use the Email Router or server-side synchronization for email processing.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[emailConnectionChannel_display](#emailConnectionChannel_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[defaultEmailServerProfileId](#defaultEmailServerProfileId)|Unique identifier of the default email server profile.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isAutoSaveEnabled](#isAutoSaveEnabled)|Information on whether auto save is enabled.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[bingMapsApiKey](#bingMapsApiKey)|Api Key to be used in requests to Bing Maps services.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[generateAlertsForErrors](#generateAlertsForErrors)|Indicates whether alerts will be generated for errors.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[generateAlertsForInformation](#generateAlertsForInformation)|Indicates whether alerts will be generated for information.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[generateAlertsForWarnings](#generateAlertsForWarnings)|Indicates whether alerts will be generated for warnings.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[notifyMailboxOwnerOfEmailServerLevelAlerts](#notifyMailboxOwnerOfEmailServerLevelAlerts)|Indicates whether mailbox owners will be notified of email server profile level alerts.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[maximumActiveBusinessProcessFlowsAllowedPerEntity](#maximumActiveBusinessProcessFlowsAllowedPerEntity)|Maximum number of active business process flows allowed per entity|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[entityImageId](#entityImageId)|For internal use only.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[allowUsersSeeAppdownloadMessage](#allowUsersSeeAppdownloadMessage)|Indicates whether the showing tablet application notification bars in a browser is allowed.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[signupOutlookDownloadFWLink](#signupOutlookDownloadFWLink)|CRM for Outlook Download URL|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[cascadeStatusUpdate](#cascadeStatusUpdate)|Flag to cascade Update on incident.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[restrictStatusUpdate](#restrictStatusUpdate)|Flag to restrict Update on incident.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[suppressSLA](#suppressSLA)|Indicates whether SLA is suppressed.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[socialInsightsTermsAccepted](#socialInsightsTermsAccepted)|Flag for whether the organization has accepted the Social Insights terms of use.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[socialInsightsInstance](#socialInsightsInstance)|Identifier for the Social Insights instance for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[disableSocialCare](#disableSocialCare)|Indicates whether Social Care is disabled.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[maxProductsInBundle](#maxProductsInBundle)|Restrict the maximum no of items in a bundle|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[useInbuiltRuleForDefaultPricelistSelection](#useInbuiltRuleForDefaultPricelistSelection)|Flag indicates whether to Use Inbuilt Rule For DefaultPricelist.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[OOBPriceCalculationEnabled](#OOBPriceCalculationEnabled)|Enable OOB pricing calculation logic for Opportunity, Quote, Order and Invoice entities.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isHierarchicalSecurityModelEnabled](#isHierarchicalSecurityModelEnabled)|Enable Hierarchical Security Model|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[maximumDynamicPropertiesAllowed](#maximumDynamicPropertiesAllowed)|Restrict the maximum number of product properties for a product family/bundle|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[usePositionHierarchy](#usePositionHierarchy)|Use position hierarchy|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[maxDepthForHierarchicalSecurityModel](#maxDepthForHierarchicalSecurityModel)|Maximum depth for hierarchy security propagation.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[slaPauseStates](#slaPauseStates)|Contains the on hold case status values.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[socialInsightsEnabled](#socialInsightsEnabled)|Flag for whether the organization is using Social Insights.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isAppointmentAttachmentSyncEnabled](#isAppointmentAttachmentSyncEnabled)|Enable or disable attachments sync for outlook and exchange.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isAssignedTasksSyncEnabled](#isAssignedTasksSyncEnabled)|Enable or disable assigned tasks sync for outlook and exchange.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isContactMailingAddressSyncEnabled](#isContactMailingAddressSyncEnabled)|Enable or disable mailing address sync for outlook and exchange.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[maxSupportedInternetExplorerVersion](#maxSupportedInternetExplorerVersion)|The maximum version of IE to run browser emulation for in Outlook client|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[globalHelpUrl](#globalHelpUrl)|URL for the web page global help.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[globalHelpUrlEnabled](#globalHelpUrlEnabled)|Indicates whether the customizable global help is enabled.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[globalAppendUrlParametersEnabled](#globalAppendUrlParametersEnabled)|Indicates whether the append URL parameters is enabled.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[KMSettings](#KMSettings)|XML string containing the Knowledge Management settings that are applied in Knowledge Management Wizard.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[createProductsWithoutParentInActiveState](#createProductsWithoutParentInActiveState)|Enable Initial state of newly created products to be Active instead of Draft|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isMailboxInactiveBackoffEnabled](#isMailboxInactiveBackoffEnabled)|Enable or disable mailbox keep alive for Server Side Sync.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isFullTextSearchEnabled](#isFullTextSearchEnabled)|Indicates whether full-text search for Quick Find entities should be enabled for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[enforceReadOnlyPlugins](#enforceReadOnlyPlugins)|Organization setting to enforce read only plugins.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[sharePointDeploymentType](#sharePointDeploymentType)|Indicates which SharePoint deployment type is configured for Server to Server. (Online or On-Premises)|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[sharePointDeploymentType_display](#sharePointDeploymentType_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[organizationState](#organizationState)|Indicates the organization lifecycle state|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[organizationState_display](#organizationState_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[defaultThemeData](#defaultThemeData)|Default theme data for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isFolderBasedTrackingEnabled](#isFolderBasedTrackingEnabled)|Enable or disable folder based tracking for Server Side Sync.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[webResourceHash](#webResourceHash)|Hash value of web resources.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[expireChangeTrackingInDays](#expireChangeTrackingInDays)|Maximum number of days to keep change tracking deleted records|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[maxFolderBasedTrackingMappings](#maxFolderBasedTrackingMappings)|Maximum number of Folder Based Tracking mappings user can add|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[privacyStatementUrl](#privacyStatementUrl)|Privacy Statement URL|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[pluginTraceLogSetting](#pluginTraceLogSetting)|Plug-in Trace Log Setting for the Organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[pluginTraceLogSetting_display](#pluginTraceLogSetting_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isMailboxForcedUnlockingEnabled](#isMailboxForcedUnlockingEnabled)|Enable or disable forced unlocking for Server Side Sync mailboxes.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[mailboxIntermittentIssueMinRange](#mailboxIntermittentIssueMinRange)|Lower Threshold For Mailbox Intermittent Issue.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[mailboxPermanentIssueMinRange](#mailboxPermanentIssueMinRange)|Lower Threshold For Mailbox Permanent Issue.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[highContrastThemeData](#highContrastThemeData)|High contrast theme data for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[delegatedAdminUserId](#delegatedAdminUserId)|Unique identifier of the delegated admin user for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isExternalSearchIndexEnabled](#isExternalSearchIndexEnabled)|Select whether data can be synchronized with an external search index.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isMobileOfflineEnabled](#isMobileOfflineEnabled)|Indicates whether the feature MobileOffline should be enabled for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isOfficeGraphEnabled](#isOfficeGraphEnabled)|Indicates whether the feature OfficeGraph should be enabled for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isOneDriveEnabled](#isOneDriveEnabled)|Indicates whether the feature One Drive should be enabled for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[externalPartyEntitySettings](#externalPartyEntitySettings)|XML string containing the ExternalPartyEnabled entities settings.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[externalPartyCorrelationKeys](#externalPartyCorrelationKeys)|XML string containing the ExternalPartyEnabled entities correlation keys for association of existing External Party instance entities to newly created IsExternalPartyEnabled entities.For internal use only|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[maxVerboseLoggingMailbox](#maxVerboseLoggingMailbox)|Maximum number of mailboxes that can be toggled for verbose logging|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[maxVerboseLoggingSyncCycles](#maxVerboseLoggingSyncCycles)|Maximum number of sync cycles for which verbose logging will be enabled by default|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[mobileOfflineSyncInterval](#mobileOfflineSyncInterval)|Sync interval for mobile offline.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[officeGraphDelveUrl](#officeGraphDelveUrl)|The url to open the Delve for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[mobileOfflineMinLicenseTrial](#mobileOfflineMinLicenseTrial)|Minimum number of user license required for mobile offline service by trial organization|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[mobileOfflineMinLicenseProd](#mobileOfflineMinLicenseProd)|Minimum number of user license required for mobile offline service by production/preview organization|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[daysSinceRecordLastModifiedMaxValue](#daysSinceRecordLastModifiedMaxValue)|The maximum value for the Mobile Offline setting Days since record last modified|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[taskBasedFlowEnabled](#taskBasedFlowEnabled)|Select whether to turn on task flows for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[showKBArticleDeprecationNotification](#showKBArticleDeprecationNotification)|Select whether to display a KB article deprecation notification to the user.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[azureSchedulerJobCollectionName](#azureSchedulerJobCollectionName)|For internal use only.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[cortanaProactiveExperienceEnabled](#cortanaProactiveExperienceEnabled)|Indicates whether the feature CortanaProactiveExperience Flow processes should be enabled for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[officeAppsAutoDeploymentEnabled](#officeAppsAutoDeploymentEnabled)|Indicates whether the Office Apps auto deployment is enabled for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[appDesignerExperienceEnabled](#appDesignerExperienceEnabled)|Indicates whether the appDesignerExperience is enabled for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[enableImmersiveSkypeIntegration](#enableImmersiveSkypeIntegration)|Enable Integration with Immersive Skype|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[autoApplySLA](#autoApplySLA)|Indicates whether to Auto-apply SLA on case record update after SLA was manually applied.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isEmailServerProfileContentFilteringEnabled](#isEmailServerProfileContentFilteringEnabled)|Enable Email Server Profile content filtering|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isDelegateAccessEnabled](#isDelegateAccessEnabled)|Enable Delegation Access content|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[displayNavigationTour](#displayNavigationTour)|Indicates whether or not navigation tour is displayed.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[useLegacyRendering](#useLegacyRendering)|Select whether to use legacy form rendering.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[defaultMobileOfflineProfileId](#defaultMobileOfflineProfileId)|Unique identifier of the default mobile offline profile.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[kaPrefix](#kaPrefix)|Type the prefix to use for all knowledge articles in Microsoft Dynamics 365.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[currentKaNumber](#currentKaNumber)|Enter the first number to use for knowledge articles. Deprecated. Use SetAutoNumberSeed message.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[currentCategoryNumber](#currentCategoryNumber)|Enter the first number to use for Categories. Deprecated. Use SetAutoNumberSeed message.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[categoryPrefix](#categoryPrefix)|Type the prefix to use for all categories in Microsoft Dynamics 365.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[maximumEntitiesWithActiveSLA](#maximumEntitiesWithActiveSLA)|Maximum number of active SLA allowed per entity in online|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[maximumSLAKPIPerEntityWithActiveSLA](#maximumSLAKPIPerEntityWithActiveSLA)|Maximum number of SLA KPI per active SLA allowed for entity in online|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isConflictDetectionEnabledForMobileClient](#isConflictDetectionEnabledForMobileClient)|Information that specifies whether conflict detection for mobile client is enabled.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isDelveActionHubIntegrationEnabled](#isDelveActionHubIntegrationEnabled)|Indicates whether the feature Action Hub should be enabled for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[orgInsightsEnabled](#orgInsightsEnabled)|Select whether to turn on OrgInsights for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[productRecommendationsEnabled](#productRecommendationsEnabled)|Select whether to turn on product recommendations for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[textAnalyticsEnabled](#textAnalyticsEnabled)|Select whether to turn on text analytics for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[maxConditionsForMobileOfflineFilters](#maxConditionsForMobileOfflineFilters)|Maximum number of conditions allowed for mobile offline filters|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isFolderAutoCreatedonSP](#isFolderAutoCreatedonSP)|Select whether folders should be automatically created on SharePoint.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[powerBiFeatureEnabled](#powerBiFeatureEnabled)|Indicates whether the Power BI feature should be enabled for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isActionCardEnabled](#isActionCardEnabled)|Indicates whether the feature Action Card should be enabled for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isEmailMonitoringAllowed](#isEmailMonitoringAllowed)|Allow tracking recipient activity on sent emails.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isActivityAnalysisEnabled](#isActivityAnalysisEnabled)|Indicates whether the feature Relationship Analytics should be enabled for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isAutoDataCaptureEnabled](#isAutoDataCaptureEnabled)|Indicates whether the feature Auto Capture should be enabled for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[externalBaseUrl](#externalBaseUrl)|Specify the base URL to use to look for external document suggestions.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isPreviewEnabledForActionCard](#isPreviewEnabledForActionCard)|Indicates whether the Preview feature for Action Card should be enabled for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isPreviewForEmailMonitoringAllowed](#isPreviewForEmailMonitoringAllowed)|Is Preview For Email Monitoring Allowed.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[unresolveEmailAddressIfMultipleMatch](#unresolveEmailAddressIfMultipleMatch)|Indicates whether email address should be unresolved if multiple matches are found|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[riErrorStatus](#riErrorStatus)|Error status of Relationship Insights provisioning.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[widgetProperties](#widgetProperties)|For Internal use only.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[enableMicrosoftFlowIntegration](#enableMicrosoftFlowIntegration)|Enable Integration with Microsoft Flow|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isEnabledForAllRoles](#isEnabledForAllRoles)|Indicates whether appmodule is enabled for all roles|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isPreviewForAutoCaptureEnabled](#isPreviewForAutoCaptureEnabled)|Indicates whether the feature Auto Capture should be enabled for the organization at Preview Settings.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[defaultCrmCustomName](#defaultCrmCustomName)|Name of the default crm custom.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[ACIWebEndpointUrl](#ACIWebEndpointUrl)|ACI Web Endpoint URL.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[enableLPAuthoring](#enableLPAuthoring)|Select to enable learning path auhtoring.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isResourceBookingExchangeSyncEnabled](#isResourceBookingExchangeSyncEnabled)|Indicates if the synchronization of user resource booking with Exchange is enabled at organization level.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isMobileClientOnDemandSyncEnabled](#isMobileClientOnDemandSyncEnabled)|Information that specifies whether mobile client on demand sync is enabled.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[postMessageWhitelistDomains](#postMessageWhitelistDomains)|For internal use only.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isRelationshipInsightsEnabled](#isRelationshipInsightsEnabled)|Indicates whether the feature Relationship Insights should be enabled for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[resolveSimilarUnresolvedEmailAddress](#resolveSimilarUnresolvedEmailAddress)|Apply same email address to all unresolved matches when you manually resolve it for one|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isTextWrapEnabled](#isTextWrapEnabled)|Information on whether text wrap is enabled.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[sessionTimeoutEnabled](#sessionTimeoutEnabled)|Information that specifies whether session timeout is enabled|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[sessionTimeoutInMins](#sessionTimeoutInMins)|Session timeout in minutes|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[sessionTimeoutReminderInMins](#sessionTimeoutReminderInMins)|Session timeout reminder in minutes|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[microsoftFlowEnvironment](#microsoftFlowEnvironment)|Environment selected for Integration with Microsoft Flow|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[inactivityTimeoutEnabled](#inactivityTimeoutEnabled)|Information that specifies whether Inactivity timeout is enabled|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[inactivityTimeoutInMins](#inactivityTimeoutInMins)|Inactivity timeout in minutes|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[inactivityTimeoutReminderInMins](#inactivityTimeoutReminderInMins)|Inactivity timeout reminder in minutes|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[syncOptInSelection](#syncOptInSelection)|Indicates the selection to use the dynamics 365 azure sync framework or server side sync.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[syncOptInSelectionStatus](#syncOptInSelectionStatus)|Indicates the status of the opt-in or opt-out operation for dynamics 365 azure sync.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[syncOptInSelectionStatus_display](#syncOptInSelectionStatus_display)||<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isActionSupportFeatureEnabled](#isActionSupportFeatureEnabled)|Information that specifies whether Action Support Feature is enabled|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isBPFEntityCustomizationFeatureEnabled](#isBPFEntityCustomizationFeatureEnabled)|Information that specifies whether BPF Entity Customization Feature is enabled|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[boundDashboardDefaultCardExpanded](#boundDashboardDefaultCardExpanded)|Display cards in expanded state for interactive dashboard|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[maxActionStepsInBPF](#maxActionStepsInBPF)|Maximum number of actionsteps allowed in a BPF|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[serveStaticResourcesFromAzureCDN](#serveStaticResourcesFromAzureCDN)|Serve Static Content From CDN|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isExternalFileStorageEnabled](#isExternalFileStorageEnabled)|Indicates whether the organization's files are being stored in Azure.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[clientFeatureSet](#clientFeatureSet)|Client Features to be enabled as an XML BLOB.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isReadAuditEnabled](#isReadAuditEnabled)|Enable or disable auditing of read operations.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[isNotesAnalysisEnabled](#isNotesAnalysisEnabled)|Indicates whether the feature Notes Analysis should be enabled for the organization.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[allowLegacyDialogsEmbedding](#allowLegacyDialogsEmbedding)|Enable embedding of certain legacy dialogs in Unified Interface browser client|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|
|[appointmentRichEditorExperience](#appointmentRichEditorExperience)|Information on whether rich editing experience for Appointment is enabled.|<a href="Organization.md" target="_blank">applicationCommon/Organization</a>|

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier of the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization</td></tr><tr><td>description</td><td>Unique identifier of the organization.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#name name="name">name</a>

Name of the organization. The name is set when Microsoft CRM is installed and should not be changed.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Name</td></tr><tr><td>description</td><td>Name of the organization. The name is set when Microsoft CRM is installed and should not be changed.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>160</td></tr><tr><td>sourceName</td><td>name</td></tr></table>

### <a href=#userGroupId name="userGroupId">userGroupId</a>

Unique identifier of the default group of users in the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>User Group</td></tr><tr><td>description</td><td>Unique identifier of the default group of users in the organization.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>usergroupid</td></tr></table>

### <a href=#privilegeUserGroupId name="privilegeUserGroupId">privilegeUserGroupId</a>

Unique identifier of the default privilege for users in the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Privilege User Group</td></tr><tr><td>description</td><td>Unique identifier of the default privilege for users in the organization.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>privilegeusergroupid</td></tr></table>

### <a href=#recurrenceExpansionJobBatchSize name="recurrenceExpansionJobBatchSize">recurrenceExpansionJobBatchSize</a>

Specifies the value for number of instances created in on demand job in one shot.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurrence Expansion On Demand Job Batch Size</td></tr><tr><td>description</td><td>Specifies the value for number of instances created in on demand job in one shot.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>recurrenceexpansionjobbatchsize</td></tr></table>

### <a href=#recurrenceExpansionJobBatchInterval name="recurrenceExpansionJobBatchInterval">recurrenceExpansionJobBatchInterval</a>

Specifies the interval (in seconds) for pausing expansion job.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurrence Expansion Job Batch Interval</td></tr><tr><td>description</td><td>Specifies the interval (in seconds) for pausing expansion job.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>recurrenceexpansionjobbatchinterval</td></tr></table>

### <a href=#fiscalPeriodType name="fiscalPeriodType">fiscalPeriodType</a>

Type of fiscal period used throughout Microsoft CRM.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal Period Type</td></tr><tr><td>description</td><td>Type of fiscal period used throughout Microsoft CRM.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>fiscalperiodtype</td></tr></table>

### <a href=#fiscalCalendarStart name="fiscalCalendarStart">fiscalCalendarStart</a>

Start date for the fiscal period that is to be used throughout Microsoft CRM.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal Calendar Start</td></tr><tr><td>description</td><td>Start date for the fiscal period that is to be used throughout Microsoft CRM.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fiscalcalendarstart</td></tr></table>

### <a href=#dateFormatCode name="dateFormatCode">dateFormatCode</a>

Information about how the date is displayed throughout Microsoft CRM.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Format Code</td></tr><tr><td>description</td><td>Information about how the date is displayed throughout Microsoft CRM.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>dateformatcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#dateFormatCode_display name="dateFormatCode_display">dateFormatCode_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#timeFormatCode name="timeFormatCode">timeFormatCode</a>

Information that specifies how the time is displayed throughout Microsoft CRM.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Format Code</td></tr><tr><td>description</td><td>Information that specifies how the time is displayed throughout Microsoft CRM.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>timeformatcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#timeFormatCode_display name="timeFormatCode_display">timeFormatCode_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#currencySymbol name="currencySymbol">currencySymbol</a>

Symbol used for currency throughout Microsoft Dynamics 365.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency Symbol</td></tr><tr><td>description</td><td>Symbol used for currency throughout Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>13</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>currencysymbol</td></tr></table>

### <a href=#weekStartDayCode name="weekStartDayCode">weekStartDayCode</a>

Designated first day of the week throughout Microsoft Dynamics 365.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Week Start Day Code</td></tr><tr><td>description</td><td>Designated first day of the week throughout Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>weekstartdaycode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td></td></tr></table>

### <a href=#weekStartDayCode_display name="weekStartDayCode_display">weekStartDayCode_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#dateSeparator name="dateSeparator">dateSeparator</a>

Character used to separate the month, the day, and the year in dates throughout Microsoft Dynamics 365.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Separator</td></tr><tr><td>description</td><td>Character used to separate the month, the day, and the year in dates throughout Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>5</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>dateseparator</td></tr></table>

### <a href=#fullNameConventionCode name="fullNameConventionCode">fullNameConventionCode</a>

Order in which names are to be displayed throughout Microsoft CRM.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Full Name Display Order</td></tr><tr><td>description</td><td>Order in which names are to be displayed throughout Microsoft CRM.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>fullnameconventioncode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Last Name, First Name</td><td>0</td></tr><tr><td>en</td><td>First Name</td><td>1</td></tr><tr><td>en</td><td>Last Name, First Name, Middle Initial</td><td>2</td></tr><tr><td>en</td><td>First Name, Middle Initial, Last Name</td><td>3</td></tr><tr><td>en</td><td>Last Name, First Name, Middle Name</td><td>4</td></tr><tr><td>en</td><td>First Name, Middle Name, Last Name</td><td>5</td></tr><tr><td>en</td><td>Last Name, space, First Name</td><td>6</td></tr><tr><td>en</td><td>Last Name, no space, First Name</td><td>7</td></tr></table></td></tr></table>

### <a href=#fullNameConventionCode_display name="fullNameConventionCode_display">fullNameConventionCode_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#negativeFormatCode name="negativeFormatCode">negativeFormatCode</a>

Information that specifies how negative numbers are displayed throughout Microsoft CRM.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Negative Format</td></tr><tr><td>description</td><td>Information that specifies how negative numbers are displayed throughout Microsoft CRM.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>negativeformatcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Brackets</td><td>0</td></tr><tr><td>en</td><td>Dash</td><td>1</td></tr><tr><td>en</td><td>Dash plus Space</td><td>2</td></tr><tr><td>en</td><td>Trailing Dash</td><td>3</td></tr><tr><td>en</td><td>Space plus Trailing Dash</td><td>4</td></tr></table></td></tr></table>

### <a href=#negativeFormatCode_display name="negativeFormatCode_display">negativeFormatCode_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#numberFormat name="numberFormat">numberFormat</a>

Specification of how numbers are displayed throughout Microsoft CRM.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number Format</td></tr><tr><td>description</td><td>Specification of how numbers are displayed throughout Microsoft CRM.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>numberformat</td></tr></table>

### <a href=#isDisabled name="isDisabled">isDisabled</a>

Information that specifies whether the organization is disabled.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Organization Disabled</td></tr><tr><td>description</td><td>Information that specifies whether the organization is disabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isdisabled</td></tr></table>

### <a href=#disabledReason name="disabledReason">disabledReason</a>

Reason for disabling the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Disabled Reason</td></tr><tr><td>description</td><td>Reason for disabling the organization.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>disabledreason</td></tr></table>

### <a href=#kbPrefix name="kbPrefix">kbPrefix</a>

Prefix to use for all articles in Microsoft Dynamics 365.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Article Prefix</td></tr><tr><td>description</td><td>Prefix to use for all articles in Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>kbprefix</td></tr></table>

### <a href=#currentKbNumber name="currentKbNumber">currentKbNumber</a>

First article number to use. Deprecated. Use SetAutoNumberSeed message.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Current Article Number</td></tr><tr><td>description</td><td>First article number to use. Deprecated. Use SetAutoNumberSeed message.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>currentkbnumber</td></tr></table>

### <a href=#casePrefix name="casePrefix">casePrefix</a>

Prefix to use for all cases throughout Microsoft Dynamics 365.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Case Prefix</td></tr><tr><td>description</td><td>Prefix to use for all cases throughout Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>caseprefix</td></tr></table>

### <a href=#currentCaseNumber name="currentCaseNumber">currentCaseNumber</a>

First case number to use. Deprecated. Use SetAutoNumberSeed message.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Current Case Number</td></tr><tr><td>description</td><td>First case number to use. Deprecated. Use SetAutoNumberSeed message.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>currentcasenumber</td></tr></table>

### <a href=#contractPrefix name="contractPrefix">contractPrefix</a>

Prefix to use for all contracts throughout Microsoft Dynamics 365.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contract Prefix</td></tr><tr><td>description</td><td>Prefix to use for all contracts throughout Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>contractprefix</td></tr></table>

### <a href=#currentContractNumber name="currentContractNumber">currentContractNumber</a>

First contract number to use. Deprecated. Use SetAutoNumberSeed message.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Current Contract Number</td></tr><tr><td>description</td><td>First contract number to use. Deprecated. Use SetAutoNumberSeed message.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>currentcontractnumber</td></tr></table>

### <a href=#quotePrefix name="quotePrefix">quotePrefix</a>

Prefix to use for all quotes throughout Microsoft Dynamics 365.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quote Prefix</td></tr><tr><td>description</td><td>Prefix to use for all quotes throughout Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>quoteprefix</td></tr></table>

### <a href=#currentQuoteNumber name="currentQuoteNumber">currentQuoteNumber</a>

First quote number to use. Deprecated. Use SetAutoNumberSeed message.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Current Quote Number</td></tr><tr><td>description</td><td>First quote number to use. Deprecated. Use SetAutoNumberSeed message.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>currentquotenumber</td></tr></table>

### <a href=#orderPrefix name="orderPrefix">orderPrefix</a>

Prefix to use for all orders throughout Microsoft Dynamics 365.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Order Prefix</td></tr><tr><td>description</td><td>Prefix to use for all orders throughout Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>orderprefix</td></tr></table>

### <a href=#currentOrderNumber name="currentOrderNumber">currentOrderNumber</a>

First order number to use. Deprecated. Use SetAutoNumberSeed message.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Current Order Number</td></tr><tr><td>description</td><td>First order number to use. Deprecated. Use SetAutoNumberSeed message.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>currentordernumber</td></tr></table>

### <a href=#invoicePrefix name="invoicePrefix">invoicePrefix</a>

Prefix to use for all invoice numbers throughout Microsoft Dynamics 365.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Invoice Prefix</td></tr><tr><td>description</td><td>Prefix to use for all invoice numbers throughout Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>invoiceprefix</td></tr></table>

### <a href=#currentInvoiceNumber name="currentInvoiceNumber">currentInvoiceNumber</a>

First invoice number to use. Deprecated. Use SetAutoNumberSeed message.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Current Invoice Number</td></tr><tr><td>description</td><td>First invoice number to use. Deprecated. Use SetAutoNumberSeed message.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>currentinvoicenumber</td></tr></table>

### <a href=#uniqueSpecifierLength name="uniqueSpecifierLength">uniqueSpecifierLength</a>

Number of characters appended to invoice, quote, and order numbers.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Unique String Length</td></tr><tr><td>description</td><td>Number of characters appended to invoice, quote, and order numbers.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>6</td></tr><tr><td>minimumValue</td><td>4</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>uniquespecifierlength</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the organization was created.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the organization was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the organization was last modified.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the organization was last modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#fiscalYearFormat name="fiscalYearFormat">fiscalYearFormat</a>

Information that specifies how the name of the fiscal year is displayed throughout Microsoft CRM.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal Year Format</td></tr><tr><td>description</td><td>Information that specifies how the name of the fiscal year is displayed throughout Microsoft CRM.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>25</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fiscalyearformat</td></tr></table>

### <a href=#fiscalPeriodFormat name="fiscalPeriodFormat">fiscalPeriodFormat</a>

Information that specifies how the name of the fiscal period is displayed throughout Microsoft CRM.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal Period Format</td></tr><tr><td>description</td><td>Information that specifies how the name of the fiscal period is displayed throughout Microsoft CRM.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>25</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fiscalperiodformat</td></tr></table>

### <a href=#fiscalYearPeriodConnect name="fiscalYearPeriodConnect">fiscalYearPeriodConnect</a>

Information that specifies how the names of the fiscal year and the fiscal period should be connected when displayed together.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal Year Period Connector</td></tr><tr><td>description</td><td>Information that specifies how the names of the fiscal year and the fiscal period should be connected when displayed together.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>5</td></tr><tr><td>sourceName</td><td>fiscalyearperiodconnect</td></tr></table>

### <a href=#languageCode name="languageCode">languageCode</a>

Preferred language for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Language</td></tr><tr><td>description</td><td>Preferred language for the organization.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>languagecode</td></tr></table>

### <a href=#sortId name="sortId">sortId</a>

For internal use only.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sort</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sortid</td></tr></table>

### <a href=#dateFormatString name="dateFormatString">dateFormatString</a>

String showing how the date is displayed throughout Microsoft CRM.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Date Format String</td></tr><tr><td>description</td><td>String showing how the date is displayed throughout Microsoft CRM.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>dateformatstring</td></tr></table>

### <a href=#timeFormatString name="timeFormatString">timeFormatString</a>

Text for how time is displayed in Microsoft Dynamics 365.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Format String</td></tr><tr><td>description</td><td>Text for how time is displayed in Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>255</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timeformatstring</td></tr></table>

### <a href=#pricingDecimalPrecision name="pricingDecimalPrecision">pricingDecimalPrecision</a>

Number of decimal places that can be used for prices.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Pricing Decimal Precision</td></tr><tr><td>description</td><td>Number of decimal places that can be used for prices.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>4</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>pricingdecimalprecision</td></tr></table>

### <a href=#showWeekNumber name="showWeekNumber">showWeekNumber</a>

Information that specifies whether to display the week number in calendar displays throughout Microsoft CRM.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Show Week Number</td></tr><tr><td>description</td><td>Information that specifies whether to display the week number in calendar displays throughout Microsoft CRM.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>showweeknumber</td></tr></table>

### <a href=#nextTrackingNumber name="nextTrackingNumber">nextTrackingNumber</a>

Next token to be placed on the subject line of an email message.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Next Tracking Number</td></tr><tr><td>description</td><td>Next token to be placed on the subject line of an email message.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>nexttrackingnumber</td></tr></table>

### <a href=#tagMaxAggressiveCycles name="tagMaxAggressiveCycles">tagMaxAggressiveCycles</a>

Maximum number of aggressive polling cycles executed for email auto-tagging when a new email is received.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Auto-Tag Max Cycles</td></tr><tr><td>description</td><td>Maximum number of aggressive polling cycles executed for email auto-tagging when a new email is received.</td></tr><tr><td>dataFormat</td><td>Int16</td></tr><tr><td>sourceName</td><td>tagmaxaggressivecycles</td></tr></table>

### <a href=#systemUserId name="systemUserId">systemUserId</a>

Unique identifier of the system user for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>System User</td></tr><tr><td>description</td><td>Unique identifier of the system user for the organization.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>systemuserid</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the organization.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#grantAccessToNetworkService name="grantAccessToNetworkService">grantAccessToNetworkService</a>

For internal use only.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Grant Access To Network Service</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>grantaccesstonetworkservice</td></tr></table>

### <a href=#allowOutlookScheduledSyncs name="allowOutlookScheduledSyncs">allowOutlookScheduledSyncs</a>

Indicates whether scheduled synchronizations to Outlook are allowed.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow Scheduled Synchronization</td></tr><tr><td>description</td><td>Indicates whether scheduled synchronizations to Outlook are allowed.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>allowoutlookscheduledsyncs</td></tr></table>

### <a href=#allowMarketingEmailExecution name="allowMarketingEmailExecution">allowMarketingEmailExecution</a>

Indicates whether marketing emails execution is allowed.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow Marketing Email Execution</td></tr><tr><td>description</td><td>Indicates whether marketing emails execution is allowed.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>allowmarketingemailexecution</td></tr></table>

### <a href=#sqlAccessGroupId name="sqlAccessGroupId">sqlAccessGroupId</a>

For internal use only.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SQL Access Group</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sqlaccessgroupid</td></tr></table>

### <a href=#currencyFormatCode name="currencyFormatCode">currencyFormatCode</a>

Information about how currency symbols are placed throughout Microsoft Dynamics CRM.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency Format Code</td></tr><tr><td>description</td><td>Information about how currency symbols are placed throughout Microsoft Dynamics CRM.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>currencyformatcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>$123</td><td>0</td></tr><tr><td>en</td><td>123$</td><td>1</td></tr><tr><td>en</td><td>$ 123</td><td>2</td></tr><tr><td>en</td><td>123 $</td><td>3</td></tr></table></td></tr></table>

### <a href=#currencyFormatCode_display name="currencyFormatCode_display">currencyFormatCode_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#fiscalSettingsUpdated name="fiscalSettingsUpdated">fiscalSettingsUpdated</a>

Information that specifies whether the fiscal settings have been updated.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Fiscal Settings Updated</td></tr><tr><td>description</td><td>Information that specifies whether the fiscal settings have been updated.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>fiscalsettingsupdated</td></tr></table>

### <a href=#reportingGroupId name="reportingGroupId">reportingGroupId</a>

For internal use only.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reporting Group</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>reportinggroupid</td></tr></table>

### <a href=#tokenExpiry name="tokenExpiry">tokenExpiry</a>

Duration used for token expiration.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Token Expiration Duration</td></tr><tr><td>description</td><td>Duration used for token expiration.</td></tr><tr><td>dataFormat</td><td>Int16</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>tokenexpiry</td></tr></table>

### <a href=#shareToPreviousOwnerOnAssign name="shareToPreviousOwnerOnAssign">shareToPreviousOwnerOnAssign</a>

Information that specifies whether to share to previous owner on assign.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Share To Previous Owner On Assign</td></tr><tr><td>description</td><td>Information that specifies whether to share to previous owner on assign.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>sharetopreviousowneronassign</td></tr></table>

### <a href=#acknowledgementTemplateId name="acknowledgementTemplateId">acknowledgementTemplateId</a>

Unique identifier of the template to be used for acknowledgement when a user unsubscribes.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Acknowledgement Template</td></tr><tr><td>description</td><td>Unique identifier of the template to be used for acknowledgement when a user unsubscribes.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>acknowledgementtemplateid</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who last modified the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who last modified the organization.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#integrationUserId name="integrationUserId">integrationUserId</a>

Unique identifier of the integration user for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Integration User</td></tr><tr><td>description</td><td>Unique identifier of the integration user for the organization.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>integrationuserid</td></tr></table>

### <a href=#trackingTokenIdBase name="trackingTokenIdBase">trackingTokenIdBase</a>

Base number used to provide separate tracking token identifiers to users belonging to different deployments.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tracking Token Base</td></tr><tr><td>description</td><td>Base number used to provide separate tracking token identifiers to users belonging to different deployments.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>trackingtokenidbase</td></tr></table>

### <a href=#businessClosureCalendarId name="businessClosureCalendarId">businessClosureCalendarId</a>

Unique identifier of the business closure calendar of organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Business Closure Calendar</td></tr><tr><td>description</td><td>Unique identifier of the business closure calendar of organization.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>businessclosurecalendarid</td></tr></table>

### <a href=#allowAutoUnsubscribeAcknowledgement name="allowAutoUnsubscribeAcknowledgement">allowAutoUnsubscribeAcknowledgement</a>

Indicates whether automatic unsubscribe acknowledgement email is allowed to send.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow Automatic Unsubscribe Acknowledgement</td></tr><tr><td>description</td><td>Indicates whether automatic unsubscribe acknowledgement email is allowed to send.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>allowautounsubscribeacknowledgement</td></tr></table>

### <a href=#allowAutoUnsubscribe name="allowAutoUnsubscribe">allowAutoUnsubscribe</a>

Indicates whether automatic unsubscribe is allowed.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow Automatic Unsubscribe</td></tr><tr><td>description</td><td>Indicates whether automatic unsubscribe is allowed.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>allowautounsubscribe</td></tr></table>

### <a href=#picture name="picture">picture</a>

For internal use only.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Picture</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>picture</td></tr></table>

### <a href=#versionNumber name="versionNumber">versionNumber</a>

Version number of the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version number of the organization.</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr></table>

### <a href=#trackingPrefix name="trackingPrefix">trackingPrefix</a>

History list of tracking token prefixes.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tracking Prefix</td></tr><tr><td>description</td><td>History list of tracking token prefixes.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>trackingprefix</td></tr></table>

### <a href=#minOutlookSyncInterval name="minOutlookSyncInterval">minOutlookSyncInterval</a>

Minimum allowed time between scheduled Outlook synchronizations.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Min Synchronization Frequency</td></tr><tr><td>description</td><td>Minimum allowed time between scheduled Outlook synchronizations.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>minoutlooksyncinterval</td></tr></table>

### <a href=#bulkOperationPrefix name="bulkOperationPrefix">bulkOperationPrefix</a>

Prefix used for bulk operation numbering.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bulk Operation Prefix</td></tr><tr><td>description</td><td>Prefix used for bulk operation numbering.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>sourceName</td><td>bulkoperationprefix</td></tr></table>

### <a href=#allowAutoResponseCreation name="allowAutoResponseCreation">allowAutoResponseCreation</a>

Indicates whether automatic response creation is allowed.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow Automatic Response Creation</td></tr><tr><td>description</td><td>Indicates whether automatic response creation is allowed.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>allowautoresponsecreation</td></tr></table>

### <a href=#maximumTrackingNumber name="maximumTrackingNumber">maximumTrackingNumber</a>

Maximum tracking number before recycling takes place.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Max Tracking Number</td></tr><tr><td>description</td><td>Maximum tracking number before recycling takes place.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>maximumtrackingnumber</td></tr></table>

### <a href=#campaignPrefix name="campaignPrefix">campaignPrefix</a>

Prefix used for campaign numbering.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Campaign Prefix</td></tr><tr><td>description</td><td>Prefix used for campaign numbering.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>sourceName</td><td>campaignprefix</td></tr></table>

### <a href=#sqlAccessGroupName name="sqlAccessGroupName">sqlAccessGroupName</a>

For internal use only.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SQL Access Group Name</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sqlaccessgroupname</td></tr></table>

### <a href=#currentCampaignNumber name="currentCampaignNumber">currentCampaignNumber</a>

Current campaign number. Deprecated. Use SetAutoNumberSeed message.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Current Campaign Number</td></tr><tr><td>description</td><td>Current campaign number. Deprecated. Use SetAutoNumberSeed message.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>currentcampaignnumber</td></tr></table>

### <a href=#fiscalYearDisplayCode name="fiscalYearDisplayCode">fiscalYearDisplayCode</a>

Information that specifies whether the fiscal year should be displayed based on the start date or the end date of the fiscal year.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal Year Display</td></tr><tr><td>description</td><td>Information that specifies whether the fiscal year should be displayed based on the start date or the end date of the fiscal year.</td></tr><tr><td>dataFormat</td><td>Int16</td></tr><tr><td>sourceName</td><td>fiscalyeardisplaycode</td></tr></table>

### <a href=#siteMapXml name="siteMapXml">siteMapXml</a>

XML string that defines the navigation structure for the application.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SiteMap XML</td></tr><tr><td>description</td><td>XML string that defines the navigation structure for the application.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sitemapxml</td></tr></table>

### <a href=#isRegistered name="isRegistered">isRegistered</a>

For internal use only.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Registered</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isregistered</td></tr></table>

### <a href=#reportingGroupName name="reportingGroupName">reportingGroupName</a>

For internal use only.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reporting Group Name</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>reportinggroupname</td></tr></table>

### <a href=#currentBulkOperationNumber name="currentBulkOperationNumber">currentBulkOperationNumber</a>

Current bulk operation number. Deprecated. Use SetAutoNumberSeed message.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Current Bulk Operation Number</td></tr><tr><td>description</td><td>Current bulk operation number. Deprecated. Use SetAutoNumberSeed message.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>currentbulkoperationnumber</td></tr></table>

### <a href=#schemaNamePrefix name="schemaNamePrefix">schemaNamePrefix</a>

Prefix used for custom entities and attributes.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Customization Name Prefix</td></tr><tr><td>description</td><td>Prefix used for custom entities and attributes.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>8</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>schemanameprefix</td></tr></table>

### <a href=#ignoreInternalEmail name="ignoreInternalEmail">ignoreInternalEmail</a>

Indicates whether incoming email sent by internal Microsoft Dynamics 365 users or queues should be tracked.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ignore Internal Email</td></tr><tr><td>description</td><td>Indicates whether incoming email sent by internal Microsoft Dynamics 365 users or queues should be tracked.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>ignoreinternalemail</td></tr></table>

### <a href=#tagPollingPeriod name="tagPollingPeriod">tagPollingPeriod</a>

Normal polling frequency used for email receive auto-tagging in outlook.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Auto-Tag Interval</td></tr><tr><td>description</td><td>Normal polling frequency used for email receive auto-tagging in outlook.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>tagpollingperiod</td></tr></table>

### <a href=#trackingTokenIdDigits name="trackingTokenIdDigits">trackingTokenIdDigits</a>

Number of digits used to represent a tracking token identifier.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tracking Token Digits</td></tr><tr><td>description</td><td>Number of digits used to represent a tracking token identifier.</td></tr><tr><td>dataFormat</td><td>Int16</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>trackingtokeniddigits</td></tr></table>

### <a href=#numberGroupFormat name="numberGroupFormat">numberGroupFormat</a>

Specifies how numbers are grouped in Microsoft Dynamics 365.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number Grouping Format</td></tr><tr><td>description</td><td>Specifies how numbers are grouped in Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>50</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>numbergroupformat</td></tr></table>

### <a href=#longDateFormatCode name="longDateFormatCode">longDateFormatCode</a>

Information that specifies how the Long Date format is displayed in Microsoft Dynamics 365.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Long Date Format</td></tr><tr><td>description</td><td>Information that specifies how the Long Date format is displayed in Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>longdateformatcode</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#currentImportSequenceNumber name="currentImportSequenceNumber">currentImportSequenceNumber</a>

Import sequence to use.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Current Import Sequence Number</td></tr><tr><td>description</td><td>Import sequence to use.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>currentimportsequencenumber</td></tr></table>

### <a href=#parsedTablePrefix name="parsedTablePrefix">parsedTablePrefix</a>

Prefix used for parsed tables.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parsed Table Prefix</td></tr><tr><td>description</td><td>Prefix used for parsed tables.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>sourceName</td><td>parsedtableprefix</td></tr></table>

### <a href=#v3CalloutConfigHash name="v3CalloutConfigHash">v3CalloutConfigHash</a>

Hash of the V3 callout configuration file.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>V3 Callout Hash</td></tr><tr><td>description</td><td>Hash of the V3 callout configuration file.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>v3calloutconfighash</td></tr></table>

### <a href=#isFiscalPeriodMonthBased name="isFiscalPeriodMonthBased">isFiscalPeriodMonthBased</a>

Indicates whether the fiscal period is displayed as the month number.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Fiscal Period Monthly</td></tr><tr><td>description</td><td>Indicates whether the fiscal period is displayed as the month number.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isfiscalperiodmonthbased</td></tr></table>

### <a href=#localeId name="localeId">localeId</a>

Unique identifier of the locale of the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Locale</td></tr><tr><td>description</td><td>Unique identifier of the locale of the organization.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>localeid</td></tr></table>

### <a href=#parsedTableColumnPrefix name="parsedTableColumnPrefix">parsedTableColumnPrefix</a>

Prefix used for parsed table columns.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parsed Table Column Prefix</td></tr><tr><td>description</td><td>Prefix used for parsed table columns.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>sourceName</td><td>parsedtablecolumnprefix</td></tr></table>

### <a href=#supportUserId name="supportUserId">supportUserId</a>

Unique identifier of the support user for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Support User</td></tr><tr><td>description</td><td>Unique identifier of the support user for the organization.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>supportuserid</td></tr></table>

### <a href=#AMDesignator name="AMDesignator">AMDesignator</a>

AM designator to use throughout Microsoft Dynamics CRM.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>AM Designator</td></tr><tr><td>description</td><td>AM designator to use throughout Microsoft Dynamics CRM.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>25</td></tr><tr><td>sourceName</td><td>amdesignator</td></tr></table>

### <a href=#currencyDisplayOption name="currencyDisplayOption">currencyDisplayOption</a>

Indicates whether to display money fields with currency code or currency symbol.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Display Currencies Using</td></tr><tr><td>description</td><td>Indicates whether to display money fields with currency code or currency symbol.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>currencydisplayoption</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Currency symbol</td><td>0</td></tr><tr><td>en</td><td>Currency code</td><td>1</td></tr></table></td></tr></table>

### <a href=#currencyDisplayOption_display name="currencyDisplayOption_display">currencyDisplayOption_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#minAddressBookSyncInterval name="minAddressBookSyncInterval">minAddressBookSyncInterval</a>

Normal polling frequency used for address book synchronization in Microsoft Office Outlook.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Min Address Synchronization Frequency</td></tr><tr><td>description</td><td>Normal polling frequency used for address book synchronization in Microsoft Office Outlook.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>minaddressbooksyncinterval</td></tr></table>

### <a href=#isDuplicateDetectionEnabledForOnlineCreateUpdate name="isDuplicateDetectionEnabledForOnlineCreateUpdate">isDuplicateDetectionEnabledForOnlineCreateUpdate</a>

Indicates whether duplicate detection during online create or update is enabled.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Duplicate Detection Enabled for Online Create/Update</td></tr><tr><td>description</td><td>Indicates whether duplicate detection during online create or update is enabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isduplicatedetectionenabledforonlinecreateupdate</td></tr></table>

### <a href=#featureSet name="featureSet">featureSet</a>

Features to be enabled as an XML BLOB.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Feature Set</td></tr><tr><td>description</td><td>Features to be enabled as an XML BLOB.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>featureset</td></tr></table>

### <a href=#blockedAttachments name="blockedAttachments">blockedAttachments</a>

Prevent upload or download of certain attachment types that are considered dangerous.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Block Attachments</td></tr><tr><td>description</td><td>Prevent upload or download of certain attachment types that are considered dangerous.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>blockedattachments</td></tr></table>

### <a href=#isDuplicateDetectionEnabledForOfflineSync name="isDuplicateDetectionEnabledForOfflineSync">isDuplicateDetectionEnabledForOfflineSync</a>

Indicates whether duplicate detection of records during offline synchronization is enabled.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Duplicate Detection Enabled For Offline Synchronization</td></tr><tr><td>description</td><td>Indicates whether duplicate detection of records during offline synchronization is enabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isduplicatedetectionenabledforofflinesync</td></tr></table>

### <a href=#allowOfflineScheduledSyncs name="allowOfflineScheduledSyncs">allowOfflineScheduledSyncs</a>

Indicates whether background offline synchronization in Microsoft Office Outlook is allowed.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow Offline Scheduled Synchronization</td></tr><tr><td>description</td><td>Indicates whether background offline synchronization in Microsoft Office Outlook is allowed.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>allowofflinescheduledsyncs</td></tr></table>

### <a href=#allowUnresolvedPartiesOnEmailSend name="allowUnresolvedPartiesOnEmailSend">allowUnresolvedPartiesOnEmailSend</a>

Indicates whether users are allowed to send email to unresolved parties (parties must still have an email address).  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow Unresolved Address Email Send</td></tr><tr><td>description</td><td>Indicates whether users are allowed to send email to unresolved parties (parties must still have an email address).</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>allowunresolvedpartiesonemailsend</td></tr></table>

### <a href=#timeSeparator name="timeSeparator">timeSeparator</a>

Text for how the time separator is displayed throughout Microsoft Dynamics 365.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Separator</td></tr><tr><td>description</td><td>Text for how the time separator is displayed throughout Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>5</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timeseparator</td></tr></table>

### <a href=#currentParsedTableNumber name="currentParsedTableNumber">currentParsedTableNumber</a>

First parsed table number to use.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Current Parsed Table Number</td></tr><tr><td>description</td><td>First parsed table number to use.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>currentparsedtablenumber</td></tr></table>

### <a href=#minOfflineSyncInterval name="minOfflineSyncInterval">minOfflineSyncInterval</a>

Normal polling frequency used for background offline synchronization in Microsoft Office Outlook.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Min Offline Synchronization Frequency</td></tr><tr><td>description</td><td>Normal polling frequency used for background offline synchronization in Microsoft Office Outlook.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>minofflinesyncinterval</td></tr></table>

### <a href=#allowWebExcelExport name="allowWebExcelExport">allowWebExcelExport</a>

Indicates whether Web-based export of grids to Microsoft Office Excel is allowed.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow Export to Excel</td></tr><tr><td>description</td><td>Indicates whether Web-based export of grids to Microsoft Office Excel is allowed.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>allowwebexcelexport</td></tr></table>

### <a href=#referenceSiteMapXml name="referenceSiteMapXml">referenceSiteMapXml</a>

XML string that defines the navigation structure for the application. This is the site map from the previously upgraded build and is used in a 3-way merge during upgrade.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Reference SiteMap XML</td></tr><tr><td>description</td><td>XML string that defines the navigation structure for the application. This is the site map from the previously upgraded build and is used in a 3-way merge during upgrade.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>referencesitemapxml</td></tr></table>

### <a href=#isDuplicateDetectionEnabledForImport name="isDuplicateDetectionEnabledForImport">isDuplicateDetectionEnabledForImport</a>

Indicates whether duplicate detection of records during import is enabled.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Duplicate Detection Enabled For Import</td></tr><tr><td>description</td><td>Indicates whether duplicate detection of records during import is enabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isduplicatedetectionenabledforimport</td></tr></table>

### <a href=#calendarType name="calendarType">calendarType</a>

Calendar type for the system. Set to Gregorian US by default.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Calendar Type</td></tr><tr><td>description</td><td>Calendar type for the system. Set to Gregorian US by default.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>calendartype</td></tr></table>

### <a href=#SQMEnabled name="SQMEnabled">SQMEnabled</a>

Setting for SQM data collection, 0 no, 1 yes enabled  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is SQM Enabled</td></tr><tr><td>description</td><td>Setting for SQM data collection, 0 no, 1 yes enabled</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sqmenabled</td></tr></table>

### <a href=#negativeCurrencyFormatCode name="negativeCurrencyFormatCode">negativeCurrencyFormatCode</a>

Information that specifies how negative currency numbers are displayed throughout Microsoft Dynamics 365.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Negative Currency Format</td></tr><tr><td>description</td><td>Information that specifies how negative currency numbers are displayed throughout Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>negativecurrencyformatcode</td></tr></table>

### <a href=#allowAddressBookSyncs name="allowAddressBookSyncs">allowAddressBookSyncs</a>

Indicates whether background address book synchronization in Microsoft Office Outlook is allowed.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow Address Book Synchronization</td></tr><tr><td>description</td><td>Indicates whether background address book synchronization in Microsoft Office Outlook is allowed.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>allowaddressbooksyncs</td></tr></table>

### <a href=#ISVIntegrationCode name="ISVIntegrationCode">ISVIntegrationCode</a>

Indicates whether loading of Microsoft Dynamics 365 in a browser window that does not have address, tool, and menu bars is enabled.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ISV Integration Mode</td></tr><tr><td>description</td><td>Indicates whether loading of Microsoft Dynamics 365 in a browser window that does not have address, tool, and menu bars is enabled.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>isvintegrationcode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>None</td><td>0</td></tr><tr><td>en</td><td>Web</td><td>1</td></tr><tr><td>en</td><td>Outlook Workstation Client</td><td>2</td></tr><tr><td>en</td><td>Web; Outlook Workstation Client</td><td>3</td></tr><tr><td>en</td><td>Outlook Laptop Client</td><td>4</td></tr><tr><td>en</td><td>Web; Outlook Laptop Client</td><td>5</td></tr><tr><td>en</td><td>Outlook</td><td>6</td></tr><tr><td>en</td><td>All</td><td>7</td></tr></table></td></tr></table>

### <a href=#ISVIntegrationCode_display name="ISVIntegrationCode_display">ISVIntegrationCode_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#decimalSymbol name="decimalSymbol">decimalSymbol</a>

Symbol used for decimal in Microsoft Dynamics 365.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Decimal Symbol</td></tr><tr><td>description</td><td>Symbol used for decimal in Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>5</td></tr><tr><td>sourceName</td><td>decimalsymbol</td></tr></table>

### <a href=#maxUploadFileSize name="maxUploadFileSize">maxUploadFileSize</a>

Maximum allowed size of an attachment.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Max Upload File Size</td></tr><tr><td>description</td><td>Maximum allowed size of an attachment.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>maxuploadfilesize</td></tr></table>

### <a href=#isAppMode name="isAppMode">isAppMode</a>

Indicates whether loading of Microsoft Dynamics 365 in a browser window that does not have address, tool, and menu bars is enabled.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Application Mode Enabled</td></tr><tr><td>description</td><td>Indicates whether loading of Microsoft Dynamics 365 in a browser window that does not have address, tool, and menu bars is enabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isappmode</td></tr></table>

### <a href=#enablePricingOnCreate name="enablePricingOnCreate">enablePricingOnCreate</a>

Enable pricing calculations on a Create call.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Pricing On Create</td></tr><tr><td>description</td><td>Enable pricing calculations on a Create call.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>enablepricingoncreate</td></tr></table>

### <a href=#isSOPIntegrationEnabled name="isSOPIntegrationEnabled">isSOPIntegrationEnabled</a>

Enable sales order processing integration.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Sales Order Integration Enabled</td></tr><tr><td>description</td><td>Enable sales order processing integration.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>issopintegrationenabled</td></tr></table>

### <a href=#PMDesignator name="PMDesignator">PMDesignator</a>

PM designator to use throughout Microsoft Dynamics 365.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>PM Designator</td></tr><tr><td>description</td><td>PM designator to use throughout Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>25</td></tr><tr><td>sourceName</td><td>pmdesignator</td></tr></table>

### <a href=#currencyDecimalPrecision name="currencyDecimalPrecision">currencyDecimalPrecision</a>

Number of decimal places that can be used for currency.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency Decimal Precision</td></tr><tr><td>description</td><td>Number of decimal places that can be used for currency.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>currencydecimalprecision</td></tr></table>

### <a href=#maxAppointmentDurationDays name="maxAppointmentDurationDays">maxAppointmentDurationDays</a>

Maximum number of days an appointment can last.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Max Appointment Duration</td></tr><tr><td>description</td><td>Maximum number of days an appointment can last.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>maxappointmentdurationdays</td></tr></table>

### <a href=#emailSendPollingPeriod name="emailSendPollingPeriod">emailSendPollingPeriod</a>

Normal polling frequency used for sending email in Microsoft Office Outlook.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Send Polling Frequency</td></tr><tr><td>description</td><td>Normal polling frequency used for sending email in Microsoft Office Outlook.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>emailsendpollingperiod</td></tr></table>

### <a href=#renderSecureIFrameForEmail name="renderSecureIFrameForEmail">renderSecureIFrameForEmail</a>

Flag to render the body of email in the Web form in an IFRAME with the security='restricted' attribute set. This is additional security but can cause a credentials prompt.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Render Secure Frame For Email</td></tr><tr><td>description</td><td>Flag to render the body of email in the Web form in an IFRAME with the security='restricted' attribute set. This is additional security but can cause a credentials prompt.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>rendersecureiframeforemail</td></tr></table>

### <a href=#numberSeparator name="numberSeparator">numberSeparator</a>

Symbol used for number separation in Microsoft Dynamics 365.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Number Separator</td></tr><tr><td>description</td><td>Symbol used for number separation in Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>5</td></tr><tr><td>sourceName</td><td>numberseparator</td></tr></table>

### <a href=#privReportingGroupId name="privReportingGroupId">privReportingGroupId</a>

For internal use only.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Privilege Reporting Group</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>privreportinggroupid</td></tr></table>

### <a href=#baseCurrencyId name="baseCurrencyId">baseCurrencyId</a>

Unique identifier of the base currency of the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Unique identifier of the base currency of the organization.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>basecurrencyid</td></tr></table>

### <a href=#maxRecordsForExportToExcel name="maxRecordsForExportToExcel">maxRecordsForExportToExcel</a>

Maximum number of records that will be exported to a static Microsoft Office Excel worksheet when exporting from the grid.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Max Records For Excel Export</td></tr><tr><td>description</td><td>Maximum number of records that will be exported to a static Microsoft Office Excel worksheet when exporting from the grid.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>maxrecordsforexporttoexcel</td></tr></table>

### <a href=#privReportingGroupName name="privReportingGroupName">privReportingGroupName</a>

For internal use only.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Privilege Reporting Group Name</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>256</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>privreportinggroupname</td></tr></table>

### <a href=#yearStartWeekCode name="yearStartWeekCode">yearStartWeekCode</a>

Information that specifies how the first week of the year is specified in Microsoft Dynamics 365.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Year Start Week Code</td></tr><tr><td>description</td><td>Information that specifies how the first week of the year is specified in Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>yearstartweekcode</td></tr></table>

### <a href=#isPresenceEnabled name="isPresenceEnabled">isPresenceEnabled</a>

Information on whether IM presence is enabled.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Presence Enabled</td></tr><tr><td>description</td><td>Information on whether IM presence is enabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>ispresenceenabled</td></tr></table>

### <a href=#isDuplicateDetectionEnabled name="isDuplicateDetectionEnabled">isDuplicateDetectionEnabled</a>

Indicates whether duplicate detection of records is enabled.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Duplicate Detection Enabled</td></tr><tr><td>description</td><td>Indicates whether duplicate detection of records is enabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isduplicatedetectionenabled</td></tr></table>

### <a href=#expireSubscriptionsInDays name="expireSubscriptionsInDays">expireSubscriptionsInDays</a>

Maximum number of days before deleting inactive subscriptions.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Days to Expire Subscriptions</td></tr><tr><td>description</td><td>Maximum number of days before deleting inactive subscriptions.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>expiresubscriptionsindays</td></tr></table>

### <a href=#isAuditEnabled name="isAuditEnabled">isAuditEnabled</a>

Enable or disable auditing of changes.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Auditing Enabled</td></tr><tr><td>description</td><td>Enable or disable auditing of changes.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isauditenabled</td></tr></table>

### <a href=#baseCurrencyPrecision name="baseCurrencyPrecision">baseCurrencyPrecision</a>

Number of decimal places that can be used for the base currency.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Base Currency Precision</td></tr><tr><td>description</td><td>Number of decimal places that can be used for the base currency.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>4</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>basecurrencyprecision</td></tr></table>

### <a href=#baseCurrencySymbol name="baseCurrencySymbol">baseCurrencySymbol</a>

Symbol used for the base currency.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Base Currency Symbol</td></tr><tr><td>description</td><td>Symbol used for the base currency.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>5</td></tr><tr><td>sourceName</td><td>basecurrencysymbol</td></tr></table>

### <a href=#maxRecordsForLookupFilters name="maxRecordsForLookupFilters">maxRecordsForLookupFilters</a>

Maximum number of lookup and picklist records that can be selected by user for filtering.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Max Records Filter Selection</td></tr><tr><td>description</td><td>Maximum number of lookup and picklist records that can be selected by user for filtering.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>maxrecordsforlookupfilters</td></tr></table>

### <a href=#allowEntityOnlyAudit name="allowEntityOnlyAudit">allowEntityOnlyAudit</a>

Indicates whether auditing of changes to entity is allowed when no attributes have changed.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow Entity Level Auditing</td></tr><tr><td>description</td><td>Indicates whether auditing of changes to entity is allowed when no attributes have changed.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>allowentityonlyaudit</td></tr></table>

### <a href=#defaultRecurrenceEndRangeType name="defaultRecurrenceEndRangeType">defaultRecurrenceEndRangeType</a>

Type of default recurrence end range date.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Recurrence End Range Type</td></tr><tr><td>description</td><td>Type of default recurrence end range date.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>defaultrecurrenceendrangetype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>No End Date</td><td>1</td></tr><tr><td>en</td><td>Number of Occurrences</td><td>2</td></tr><tr><td>en</td><td>End By Date</td><td>3</td></tr></table></td></tr></table>

### <a href=#defaultRecurrenceEndRangeType_display name="defaultRecurrenceEndRangeType_display">defaultRecurrenceEndRangeType_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#futureExpansionWindow name="futureExpansionWindow">futureExpansionWindow</a>

Specifies the maximum number of months in future for which the recurring activities can be created.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Future Expansion Window</td></tr><tr><td>description</td><td>Specifies the maximum number of months in future for which the recurring activities can be created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>140</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>sourceName</td><td>futureexpansionwindow</td></tr></table>

### <a href=#pastExpansionWindow name="pastExpansionWindow">pastExpansionWindow</a>

Specifies the maximum number of months in past for which the recurring activities can be created.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Past Expansion Window</td></tr><tr><td>description</td><td>Specifies the maximum number of months in past for which the recurring activities can be created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>120</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>sourceName</td><td>pastexpansionwindow</td></tr></table>

### <a href=#recurrenceExpansionSynchCreateMax name="recurrenceExpansionSynchCreateMax">recurrenceExpansionSynchCreateMax</a>

Specifies the maximum number of instances to be created synchronously after creating a recurring appointment.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurrence Expansion Synchronization Create Maximum</td></tr><tr><td>description</td><td>Specifies the maximum number of instances to be created synchronously after creating a recurring appointment.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>1000</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>sourceName</td><td>recurrenceexpansionsynchcreatemax</td></tr></table>

### <a href=#recurrenceDefaultNumberOfOccurrences name="recurrenceDefaultNumberOfOccurrences">recurrenceDefaultNumberOfOccurrences</a>

Specifies the default value for number of occurrences field in the recurrence dialog.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Recurrence Default Number of Occurrences</td></tr><tr><td>description</td><td>Specifies the default value for number of occurrences field in the recurrence dialog.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>999</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>sourceName</td><td>recurrencedefaultnumberofoccurrences</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the organization.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who last modified the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who last modified the organization.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#getStartedPaneContentEnabled name="getStartedPaneContentEnabled">getStartedPaneContentEnabled</a>

Indicates whether Get Started content is enabled for this organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Get Started Pane Content Enabled</td></tr><tr><td>description</td><td>Indicates whether Get Started content is enabled for this organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>getstartedpanecontentenabled</td></tr></table>

### <a href=#useReadForm name="useReadForm">useReadForm</a>

Indicates whether the read-optimized form should be enabled for this organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use Read-Optimized Form</td></tr><tr><td>description</td><td>Indicates whether the read-optimized form should be enabled for this organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>usereadform</td></tr></table>

### <a href=#initialVersion name="initialVersion">initialVersion</a>

Initial version of the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Initial Version</td></tr><tr><td>description</td><td>Initial version of the organization.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>initialversion</td></tr></table>

### <a href=#sampleDataImportId name="sampleDataImportId">sampleDataImportId</a>

Unique identifier of the sample data import job.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sample Data Import</td></tr><tr><td>description</td><td>Unique identifier of the sample data import job.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sampledataimportid</td></tr></table>

### <a href=#reportScriptErrors name="reportScriptErrors">reportScriptErrors</a>

Picklist for selecting the organization preference for reporting scripting errors.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Report Script Errors</td></tr><tr><td>description</td><td>Picklist for selecting the organization preference for reporting scripting errors.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>reportscripterrors</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>No preference for sending an error report to Microsoft about Microsoft Dynamics 365</td><td>0</td></tr><tr><td>en</td><td>Ask me for permission to send an error report to Microsoft</td><td>1</td></tr><tr><td>en</td><td>Automatically send an error report to Microsoft without asking me for permission</td><td>2</td></tr><tr><td>en</td><td>Never send an error report to Microsoft about Microsoft Dynamics 365</td><td>3</td></tr></table></td></tr></table>

### <a href=#reportScriptErrors_display name="reportScriptErrors_display">reportScriptErrors_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#requireApprovalForUserEmail name="requireApprovalForUserEmail">requireApprovalForUserEmail</a>

Indicates whether Send As Other User privilege is enabled.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Approval For User Email Required</td></tr><tr><td>description</td><td>Indicates whether Send As Other User privilege is enabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>requireapprovalforuseremail</td></tr></table>

### <a href=#requireApprovalForQueueEmail name="requireApprovalForQueueEmail">requireApprovalForQueueEmail</a>

Indicates whether Send As Other User privilege is enabled.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Approval For Queue Email Required</td></tr><tr><td>description</td><td>Indicates whether Send As Other User privilege is enabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>requireapprovalforqueueemail</td></tr></table>

### <a href=#goalRollupExpiryTime name="goalRollupExpiryTime">goalRollupExpiryTime</a>

Number of days after the goal's end date after which the rollup of the goal stops automatically.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Expiration Time for Goal</td></tr><tr><td>description</td><td>Number of days after the goal's end date after which the rollup of the goal stops automatically.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>400</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>goalrollupexpirytime</td></tr></table>

### <a href=#goalRollupFrequency name="goalRollupFrequency">goalRollupFrequency</a>

Number of hours between automatic rollup jobs .  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Automatic Rollup Frequency for Goal</td></tr><tr><td>description</td><td>Number of hours between automatic rollup jobs .</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>sourceName</td><td>goalrollupfrequency</td></tr></table>

### <a href=#autoApplyDefaultonCaseCreate name="autoApplyDefaultonCaseCreate">autoApplyDefaultonCaseCreate</a>

Select whether to auto apply the default customer entitlement on case creation.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Auto Apply Default Entitlement on Case Create</td></tr><tr><td>description</td><td>Select whether to auto apply the default customer entitlement on case creation.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>autoapplydefaultoncasecreate</td></tr></table>

### <a href=#autoApplyDefaultonCaseUpdate name="autoApplyDefaultonCaseUpdate">autoApplyDefaultonCaseUpdate</a>

Select whether to auto apply the default customer entitlement on case update.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Auto Apply Default Entitlement on Case Update</td></tr><tr><td>description</td><td>Select whether to auto apply the default customer entitlement on case update.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>autoapplydefaultoncaseupdate</td></tr></table>

### <a href=#fiscalYearFormatPrefix name="fiscalYearFormatPrefix">fiscalYearFormatPrefix</a>

Prefix for the display of the fiscal year.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Prefix for Fiscal Year</td></tr><tr><td>description</td><td>Prefix for the display of the fiscal year.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fiscalyearformatprefix</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>FY</td><td>1</td></tr><tr><td>en</td><td></td><td>2</td></tr></table></td></tr></table>

### <a href=#fiscalYearFormatPrefix_display name="fiscalYearFormatPrefix_display">fiscalYearFormatPrefix_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#fiscalYearFormatSuffix name="fiscalYearFormatSuffix">fiscalYearFormatSuffix</a>

Suffix for the display of the fiscal year.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Suffix for Fiscal Year</td></tr><tr><td>description</td><td>Suffix for the display of the fiscal year.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fiscalyearformatsuffix</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>FY</td><td>1</td></tr><tr><td>en</td><td> Fiscal Year</td><td>2</td></tr><tr><td>en</td><td></td><td>3</td></tr></table></td></tr></table>

### <a href=#fiscalYearFormatSuffix_display name="fiscalYearFormatSuffix_display">fiscalYearFormatSuffix_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#fiscalYearFormatYear name="fiscalYearFormatYear">fiscalYearFormatYear</a>

Format for the year.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal Year Format Year</td></tr><tr><td>description</td><td>Format for the year.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fiscalyearformatyear</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>YYYY</td><td>1</td></tr><tr><td>en</td><td>YY</td><td>2</td></tr><tr><td>en</td><td>GGYY</td><td>3</td></tr></table></td></tr></table>

### <a href=#fiscalYearFormatYear_display name="fiscalYearFormatYear_display">fiscalYearFormatYear_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#discountCalculationMethod name="discountCalculationMethod">discountCalculationMethod</a>

Discount calculation method for the QOOI product.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Discount calculation method</td></tr><tr><td>description</td><td>Discount calculation method for the QOOI product.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>discountcalculationmethod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Line item</td><td>0</td></tr><tr><td>en</td><td>Per unit</td><td>1</td></tr></table></td></tr></table>

### <a href=#discountCalculationMethod_display name="discountCalculationMethod_display">discountCalculationMethod_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#fiscalPeriodFormatPeriod name="fiscalPeriodFormatPeriod">fiscalPeriodFormatPeriod</a>

Format in which the fiscal period will be displayed.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Format for Fiscal Period</td></tr><tr><td>description</td><td>Format in which the fiscal period will be displayed.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fiscalperiodformatperiod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Quarter {0}</td><td>1</td></tr><tr><td>en</td><td>Q{0}</td><td>2</td></tr><tr><td>en</td><td>P{0}</td><td>3</td></tr><tr><td>en</td><td>Month {0}</td><td>4</td></tr><tr><td>en</td><td>M{0}</td><td>5</td></tr><tr><td>en</td><td>Semester {0}</td><td>6</td></tr><tr><td>en</td><td>Month Name</td><td>7</td></tr></table></td></tr></table>

### <a href=#fiscalPeriodFormatPeriod_display name="fiscalPeriodFormatPeriod_display">fiscalPeriodFormatPeriod_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#allowClientMessageBarAd name="allowClientMessageBarAd">allowClientMessageBarAd</a>

Indicates whether Outlook Client message bar advertisement is allowed.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow Outlook Client Message Bar Advertisement</td></tr><tr><td>description</td><td>Indicates whether Outlook Client message bar advertisement is allowed.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>allowclientmessagebarad</td></tr></table>

### <a href=#allowUserFormModePreference name="allowUserFormModePreference">allowUserFormModePreference</a>

Indicates whether individuals can select their form mode preference in their personal options.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow User Form Mode Preference</td></tr><tr><td>description</td><td>Indicates whether individuals can select their form mode preference in their personal options.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>allowuserformmodepreference</td></tr></table>

### <a href=#hashFilterKeywords name="hashFilterKeywords">hashFilterKeywords</a>

Filter Subject Keywords  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hash Filter Keywords</td></tr><tr><td>description</td><td>Filter Subject Keywords</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>hashfilterkeywords</td></tr></table>

### <a href=#hashMaxCount name="hashMaxCount">hashMaxCount</a>

Maximum number of subject keywords or recipients used for correlation  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hash Max Count</td></tr><tr><td>description</td><td>Maximum number of subject keywords or recipients used for correlation</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>hashmaxcount</td></tr></table>

### <a href=#hashDeltaSubjectCount name="hashDeltaSubjectCount">hashDeltaSubjectCount</a>

Maximum difference allowed between subject keywords count of the email messaged to be correlated  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hash Delta Subject Count</td></tr><tr><td>description</td><td>Maximum difference allowed between subject keywords count of the email messaged to be correlated</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>hashdeltasubjectcount</td></tr></table>

### <a href=#hashMinAddressCount name="hashMinAddressCount">hashMinAddressCount</a>

Minimum number of recipients required to match for email messaged to be correlated  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Hash Min Address Count</td></tr><tr><td>description</td><td>Minimum number of recipients required to match for email messaged to be correlated</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>hashminaddresscount</td></tr></table>

### <a href=#enableSmartMatching name="enableSmartMatching">enableSmartMatching</a>

Use Smart Matching.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Smart Matching</td></tr><tr><td>description</td><td>Use Smart Matching.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>enablesmartmatching</td></tr></table>

### <a href=#pinpointLanguageCode name="pinpointLanguageCode">pinpointLanguageCode</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>pinpointlanguagecode</td></tr></table>

### <a href=#orgDbOrgSettings name="orgDbOrgSettings">orgDbOrgSettings</a>

Organization settings stored in Organization Database.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Database Organization Settings</td></tr><tr><td>description</td><td>Organization settings stored in Organization Database.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>orgdborgsettings</td></tr></table>

### <a href=#isUserAccessAuditEnabled name="isUserAccessAuditEnabled">isUserAccessAuditEnabled</a>

Enable or disable auditing of user access.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is User Access Auditing Enabled</td></tr><tr><td>description</td><td>Enable or disable auditing of user access.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isuseraccessauditenabled</td></tr></table>

### <a href=#userAccessAuditingInterval name="userAccessAuditingInterval">userAccessAuditingInterval</a>

The interval at which user access is checked for auditing.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>User Authentication Auditing Interval</td></tr><tr><td>description</td><td>The interval at which user access is checked for auditing.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>useraccessauditinginterval</td></tr></table>

### <a href=#quickFindRecordLimitEnabled name="quickFindRecordLimitEnabled">quickFindRecordLimitEnabled</a>

Indicates whether a quick find record limit should be enabled for this organization (allows for faster Quick Find queries but prevents overly broad searches).  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Quick Find Record Limit Enabled</td></tr><tr><td>description</td><td>Indicates whether a quick find record limit should be enabled for this organization (allows for faster Quick Find queries but prevents overly broad searches).</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>quickfindrecordlimitenabled</td></tr></table>

### <a href=#enableBingMapsIntegration name="enableBingMapsIntegration">enableBingMapsIntegration</a>

Enable Integration with Bing Maps  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Integration with Bing Maps</td></tr><tr><td>description</td><td>Enable Integration with Bing Maps</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>enablebingmapsintegration</td></tr></table>

### <a href=#isDefaultCountryCodeCheckEnabled name="isDefaultCountryCodeCheckEnabled">isDefaultCountryCodeCheckEnabled</a>

Enable or disable country code selection.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable or disable country code selection</td></tr><tr><td>description</td><td>Enable or disable country code selection.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isdefaultcountrycodecheckenabled</td></tr></table>

### <a href=#defaultCountryCode name="defaultCountryCode">defaultCountryCode</a>

Text area to enter default country code.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Country Code</td></tr><tr><td>description</td><td>Text area to enter default country code.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>30</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>defaultcountrycode</td></tr></table>

### <a href=#useSkypeProtocol name="useSkypeProtocol">useSkypeProtocol</a>

Indicates default protocol selected for organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>User Skype Protocol</td></tr><tr><td>description</td><td>Indicates default protocol selected for organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>useskypeprotocol</td></tr></table>

### <a href=#incomingEmailExchangeEmailRetrievalBatchSize name="incomingEmailExchangeEmailRetrievalBatchSize">incomingEmailExchangeEmailRetrievalBatchSize</a>

Setting for the Async Service Mailbox Queue. Defines the retrieval batch size of exchange server.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Email Retrieval Batch Size</td></tr><tr><td>description</td><td>Setting for the Async Service Mailbox Queue. Defines the retrieval batch size of exchange server.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>incomingemailexchangeemailretrievalbatchsize</td></tr></table>

### <a href=#emailCorrelationEnabled name="emailCorrelationEnabled">emailCorrelationEnabled</a>

Flag to turn email correlation on or off.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use Email Correlation</td></tr><tr><td>description</td><td>Flag to turn email correlation on or off.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>emailcorrelationenabled</td></tr></table>

### <a href=#yammerOAuthAccessTokenExpired name="yammerOAuthAccessTokenExpired">yammerOAuthAccessTokenExpired</a>

Denotes whether the OAuth access token for Yammer network has expired  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yammer OAuth Access Token Expired</td></tr><tr><td>description</td><td>Denotes whether the OAuth access token for Yammer network has expired</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yammeroauthaccesstokenexpired</td></tr></table>

### <a href=#defaultEmailSettings name="defaultEmailSettings">defaultEmailSettings</a>

XML string containing the default email settings that are applied when a user or queue is created.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Email Settings</td></tr><tr><td>description</td><td>XML string containing the default email settings that are applied when a user or queue is created.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>defaultemailsettings</td></tr></table>

### <a href=#yammerGroupId name="yammerGroupId">yammerGroupId</a>

Denotes the Yammer group ID  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yammer Group Id</td></tr><tr><td>description</td><td>Denotes the Yammer group ID</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yammergroupid</td></tr></table>

### <a href=#yammerNetworkPermalink name="yammerNetworkPermalink">yammerNetworkPermalink</a>

Denotes the Yammer network permalink  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Yammer Network Permalink</td></tr><tr><td>description</td><td>Denotes the Yammer network permalink</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yammernetworkpermalink</td></tr></table>

### <a href=#yammerPostMethod name="yammerPostMethod">yammerPostMethod</a>

Internal Use Only  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Internal Use Only</td></tr><tr><td>description</td><td>Internal Use Only</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>yammerpostmethod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Public</td><td>0</td></tr><tr><td>en</td><td>Private</td><td>1</td></tr></table></td></tr></table>

### <a href=#yammerPostMethod_display name="yammerPostMethod_display">yammerPostMethod_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#emailConnectionChannel name="emailConnectionChannel">emailConnectionChannel</a>

Select if you want to use the Email Router or server-side synchronization for email processing.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Connection Channel</td></tr><tr><td>description</td><td>Select if you want to use the Email Router or server-side synchronization for email processing.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>emailconnectionchannel</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Server-Side Synchronization</td><td>0</td></tr><tr><td>en</td><td>Microsoft Dynamics 365 Email Router</td><td>1</td></tr></table></td></tr></table>

### <a href=#emailConnectionChannel_display name="emailConnectionChannel_display">emailConnectionChannel_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#defaultEmailServerProfileId name="defaultEmailServerProfileId">defaultEmailServerProfileId</a>

Unique identifier of the default email server profile.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Email Server Profile</td></tr><tr><td>description</td><td>Unique identifier of the default email server profile.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>defaultemailserverprofileid</td></tr></table>

### <a href=#isAutoSaveEnabled name="isAutoSaveEnabled">isAutoSaveEnabled</a>

Information on whether auto save is enabled.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Auto Save Enabled</td></tr><tr><td>description</td><td>Information on whether auto save is enabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isautosaveenabled</td></tr></table>

### <a href=#bingMapsApiKey name="bingMapsApiKey">bingMapsApiKey</a>

Api Key to be used in requests to Bing Maps services.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bing Maps API Key</td></tr><tr><td>description</td><td>Api Key to be used in requests to Bing Maps services.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>bingmapsapikey</td></tr></table>

### <a href=#generateAlertsForErrors name="generateAlertsForErrors">generateAlertsForErrors</a>

Indicates whether alerts will be generated for errors.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Generate Alerts For Errors</td></tr><tr><td>description</td><td>Indicates whether alerts will be generated for errors.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>generatealertsforerrors</td></tr></table>

### <a href=#generateAlertsForInformation name="generateAlertsForInformation">generateAlertsForInformation</a>

Indicates whether alerts will be generated for information.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Generate Alerts For Information</td></tr><tr><td>description</td><td>Indicates whether alerts will be generated for information.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>generatealertsforinformation</td></tr></table>

### <a href=#generateAlertsForWarnings name="generateAlertsForWarnings">generateAlertsForWarnings</a>

Indicates whether alerts will be generated for warnings.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Generate Alerts For Warnings</td></tr><tr><td>description</td><td>Indicates whether alerts will be generated for warnings.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>generatealertsforwarnings</td></tr></table>

### <a href=#notifyMailboxOwnerOfEmailServerLevelAlerts name="notifyMailboxOwnerOfEmailServerLevelAlerts">notifyMailboxOwnerOfEmailServerLevelAlerts</a>

Indicates whether mailbox owners will be notified of email server profile level alerts.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Notify Mailbox Owner Of Email Server Level Alerts</td></tr><tr><td>description</td><td>Indicates whether mailbox owners will be notified of email server profile level alerts.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>notifymailboxownerofemailserverlevelalerts</td></tr></table>

### <a href=#maximumActiveBusinessProcessFlowsAllowedPerEntity name="maximumActiveBusinessProcessFlowsAllowedPerEntity">maximumActiveBusinessProcessFlowsAllowedPerEntity</a>

Maximum number of active business process flows allowed per entity  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum active business process flows per entity</td></tr><tr><td>description</td><td>Maximum number of active business process flows allowed per entity</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>maximumactivebusinessprocessflowsallowedperentity</td></tr></table>

### <a href=#entityImageId name="entityImageId">entityImageId</a>

For internal use only.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entity Image Id</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr></table>

### <a href=#allowUsersSeeAppdownloadMessage name="allowUsersSeeAppdownloadMessage">allowUsersSeeAppdownloadMessage</a>

Indicates whether the showing tablet application notification bars in a browser is allowed.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow the showing tablet application notification bars in a browser.</td></tr><tr><td>description</td><td>Indicates whether the showing tablet application notification bars in a browser is allowed.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>allowusersseeappdownloadmessage</td></tr></table>

### <a href=#signupOutlookDownloadFWLink name="signupOutlookDownloadFWLink">signupOutlookDownloadFWLink</a>

CRM for Outlook Download URL  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>CRMForOutlookDownloadURL</td></tr><tr><td>description</td><td>CRM for Outlook Download URL</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>200</td></tr><tr><td>sourceName</td><td>signupoutlookdownloadfwlink</td></tr></table>

### <a href=#cascadeStatusUpdate name="cascadeStatusUpdate">cascadeStatusUpdate</a>

Flag to cascade Update on incident.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Cascade Status Update</td></tr><tr><td>description</td><td>Flag to cascade Update on incident.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>cascadestatusupdate</td></tr></table>

### <a href=#restrictStatusUpdate name="restrictStatusUpdate">restrictStatusUpdate</a>

Flag to restrict Update on incident.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Restrict Status Update</td></tr><tr><td>description</td><td>Flag to restrict Update on incident.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>restrictstatusupdate</td></tr></table>

### <a href=#suppressSLA name="suppressSLA">suppressSLA</a>

Indicates whether SLA is suppressed.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is SLA suppressed</td></tr><tr><td>description</td><td>Indicates whether SLA is suppressed.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>suppresssla</td></tr></table>

### <a href=#socialInsightsTermsAccepted name="socialInsightsTermsAccepted">socialInsightsTermsAccepted</a>

Flag for whether the organization has accepted the Social Insights terms of use.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Social Insights Terms of Use</td></tr><tr><td>description</td><td>Flag for whether the organization has accepted the Social Insights terms of use.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>socialinsightstermsaccepted</td></tr></table>

### <a href=#socialInsightsInstance name="socialInsightsInstance">socialInsightsInstance</a>

Identifier for the Social Insights instance for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Social Insights instance identifier</td></tr><tr><td>description</td><td>Identifier for the Social Insights instance for the organization.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>2048</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>socialinsightsinstance</td></tr></table>

### <a href=#disableSocialCare name="disableSocialCare">disableSocialCare</a>

Indicates whether Social Care is disabled.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Social Care disabled</td></tr><tr><td>description</td><td>Indicates whether Social Care is disabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>disablesocialcare</td></tr></table>

### <a href=#maxProductsInBundle name="maxProductsInBundle">maxProductsInBundle</a>

Restrict the maximum no of items in a bundle  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Bundle Item Limit</td></tr><tr><td>description</td><td>Restrict the maximum no of items in a bundle</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>maxproductsinbundle</td></tr></table>

### <a href=#useInbuiltRuleForDefaultPricelistSelection name="useInbuiltRuleForDefaultPricelistSelection">useInbuiltRuleForDefaultPricelistSelection</a>

Flag indicates whether to Use Inbuilt Rule For DefaultPricelist.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use Inbuilt Rule For Default Pricelist Selection</td></tr><tr><td>description</td><td>Flag indicates whether to Use Inbuilt Rule For DefaultPricelist.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>useinbuiltrulefordefaultpricelistselection</td></tr></table>

### <a href=#OOBPriceCalculationEnabled name="OOBPriceCalculationEnabled">OOBPriceCalculationEnabled</a>

Enable OOB pricing calculation logic for Opportunity, Quote, Order and Invoice entities.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable OOB Price calculation</td></tr><tr><td>description</td><td>Enable OOB pricing calculation logic for Opportunity, Quote, Order and Invoice entities.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>oobpricecalculationenabled</td></tr></table>

### <a href=#isHierarchicalSecurityModelEnabled name="isHierarchicalSecurityModelEnabled">isHierarchicalSecurityModelEnabled</a>

Enable Hierarchical Security Model  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Hierarchical Security Model</td></tr><tr><td>description</td><td>Enable Hierarchical Security Model</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>ishierarchicalsecuritymodelenabled</td></tr></table>

### <a href=#maximumDynamicPropertiesAllowed name="maximumDynamicPropertiesAllowed">maximumDynamicPropertiesAllowed</a>

Restrict the maximum number of product properties for a product family/bundle  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Product Properties Item Limit</td></tr><tr><td>description</td><td>Restrict the maximum number of product properties for a product family/bundle</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>maximumdynamicpropertiesallowed</td></tr></table>

### <a href=#usePositionHierarchy name="usePositionHierarchy">usePositionHierarchy</a>

Use position hierarchy  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Use position hierarchy</td></tr><tr><td>description</td><td>Use position hierarchy</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>usepositionhierarchy</td></tr></table>

### <a href=#maxDepthForHierarchicalSecurityModel name="maxDepthForHierarchicalSecurityModel">maxDepthForHierarchicalSecurityModel</a>

Maximum depth for hierarchy security propagation.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum depth for hierarchy security propagation.</td></tr><tr><td>description</td><td>Maximum depth for hierarchy security propagation.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>maxdepthforhierarchicalsecuritymodel</td></tr></table>

### <a href=#slaPauseStates name="slaPauseStates">slaPauseStates</a>

Contains the on hold case status values.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>SLA pause states</td></tr><tr><td>description</td><td>Contains the on hold case status values.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>slapausestates</td></tr></table>

### <a href=#socialInsightsEnabled name="socialInsightsEnabled">socialInsightsEnabled</a>

Flag for whether the organization is using Social Insights.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Social Insights Enabled</td></tr><tr><td>description</td><td>Flag for whether the organization is using Social Insights.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>socialinsightsenabled</td></tr></table>

### <a href=#isAppointmentAttachmentSyncEnabled name="isAppointmentAttachmentSyncEnabled">isAppointmentAttachmentSyncEnabled</a>

Enable or disable attachments sync for outlook and exchange.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Attachment Sync Enabled</td></tr><tr><td>description</td><td>Enable or disable attachments sync for outlook and exchange.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isappointmentattachmentsyncenabled</td></tr></table>

### <a href=#isAssignedTasksSyncEnabled name="isAssignedTasksSyncEnabled">isAssignedTasksSyncEnabled</a>

Enable or disable assigned tasks sync for outlook and exchange.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Assigned Tasks Sync Enabled</td></tr><tr><td>description</td><td>Enable or disable assigned tasks sync for outlook and exchange.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isassignedtaskssyncenabled</td></tr></table>

### <a href=#isContactMailingAddressSyncEnabled name="isContactMailingAddressSyncEnabled">isContactMailingAddressSyncEnabled</a>

Enable or disable mailing address sync for outlook and exchange.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Mailing Address Sync Enabled</td></tr><tr><td>description</td><td>Enable or disable mailing address sync for outlook and exchange.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>iscontactmailingaddresssyncenabled</td></tr></table>

### <a href=#maxSupportedInternetExplorerVersion name="maxSupportedInternetExplorerVersion">maxSupportedInternetExplorerVersion</a>

The maximum version of IE to run browser emulation for in Outlook client  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Max supported IE version</td></tr><tr><td>description</td><td>The maximum version of IE to run browser emulation for in Outlook client</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>maxsupportedinternetexplorerversion</td></tr></table>

### <a href=#globalHelpUrl name="globalHelpUrl">globalHelpUrl</a>

URL for the web page global help.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Global Help URL.</td></tr><tr><td>description</td><td>URL for the web page global help.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>globalhelpurl</td></tr></table>

### <a href=#globalHelpUrlEnabled name="globalHelpUrlEnabled">globalHelpUrlEnabled</a>

Indicates whether the customizable global help is enabled.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Customizable Global Help enabled</td></tr><tr><td>description</td><td>Indicates whether the customizable global help is enabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>globalhelpurlenabled</td></tr></table>

### <a href=#globalAppendUrlParametersEnabled name="globalAppendUrlParametersEnabled">globalAppendUrlParametersEnabled</a>

Indicates whether the append URL parameters is enabled.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is AppendUrl Parameters enabled</td></tr><tr><td>description</td><td>Indicates whether the append URL parameters is enabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>globalappendurlparametersenabled</td></tr></table>

### <a href=#KMSettings name="KMSettings">KMSettings</a>

XML string containing the Knowledge Management settings that are applied in Knowledge Management Wizard.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Knowledge Management Settings</td></tr><tr><td>description</td><td>XML string containing the Knowledge Management settings that are applied in Knowledge Management Wizard.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>kmsettings</td></tr></table>

### <a href=#createProductsWithoutParentInActiveState name="createProductsWithoutParentInActiveState">createProductsWithoutParentInActiveState</a>

Enable Initial state of newly created products to be Active instead of Draft  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Active Initial Product State</td></tr><tr><td>description</td><td>Enable Initial state of newly created products to be Active instead of Draft</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>createproductswithoutparentinactivestate</td></tr></table>

### <a href=#isMailboxInactiveBackoffEnabled name="isMailboxInactiveBackoffEnabled">isMailboxInactiveBackoffEnabled</a>

Enable or disable mailbox keep alive for Server Side Sync.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Mailbox Keep Alive Enabled</td></tr><tr><td>description</td><td>Enable or disable mailbox keep alive for Server Side Sync.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>ismailboxinactivebackoffenabled</td></tr></table>

### <a href=#isFullTextSearchEnabled name="isFullTextSearchEnabled">isFullTextSearchEnabled</a>

Indicates whether full-text search for Quick Find entities should be enabled for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Full-text search for Quick Find</td></tr><tr><td>description</td><td>Indicates whether full-text search for Quick Find entities should be enabled for the organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isfulltextsearchenabled</td></tr></table>

### <a href=#enforceReadOnlyPlugins name="enforceReadOnlyPlugins">enforceReadOnlyPlugins</a>

Organization setting to enforce read only plugins.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization setting to enforce read only plugins.</td></tr><tr><td>description</td><td>Organization setting to enforce read only plugins.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>enforcereadonlyplugins</td></tr></table>

### <a href=#sharePointDeploymentType name="sharePointDeploymentType">sharePointDeploymentType</a>

Indicates which SharePoint deployment type is configured for Server to Server. (Online or On-Premises)  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Choose SharePoint Deployment Type</td></tr><tr><td>description</td><td>Indicates which SharePoint deployment type is configured for Server to Server. (Online or On-Premises)</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sharepointdeploymenttype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Online</td><td>0</td></tr><tr><td>en</td><td>On-Premises</td><td>1</td></tr></table></td></tr></table>

### <a href=#sharePointDeploymentType_display name="sharePointDeploymentType_display">sharePointDeploymentType_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#organizationState name="organizationState">organizationState</a>

Indicates the organization lifecycle state  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization State</td></tr><tr><td>description</td><td>Indicates the organization lifecycle state</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>organizationstate</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Creating</td><td>0</td></tr><tr><td>en</td><td>Upgrading</td><td>1</td></tr><tr><td>en</td><td>Updating</td><td>2</td></tr><tr><td>en</td><td>Active</td><td>3</td></tr></table></td></tr></table>

### <a href=#organizationState_display name="organizationState_display">organizationState_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#defaultThemeData name="defaultThemeData">defaultThemeData</a>

Default theme data for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Theme Data</td></tr><tr><td>description</td><td>Default theme data for the organization.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>defaultthemedata</td></tr></table>

### <a href=#isFolderBasedTrackingEnabled name="isFolderBasedTrackingEnabled">isFolderBasedTrackingEnabled</a>

Enable or disable folder based tracking for Server Side Sync.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Folder Based Tracking Enabled</td></tr><tr><td>description</td><td>Enable or disable folder based tracking for Server Side Sync.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isfolderbasedtrackingenabled</td></tr></table>

### <a href=#webResourceHash name="webResourceHash">webResourceHash</a>

Hash value of web resources.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Web resource hash</td></tr><tr><td>description</td><td>Hash value of web resources.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>webresourcehash</td></tr></table>

### <a href=#expireChangeTrackingInDays name="expireChangeTrackingInDays">expireChangeTrackingInDays</a>

Maximum number of days to keep change tracking deleted records  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Days to Expire Change Tracking Deleted Records</td></tr><tr><td>description</td><td>Maximum number of days to keep change tracking deleted records</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>365</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>expirechangetrackingindays</td></tr></table>

### <a href=#maxFolderBasedTrackingMappings name="maxFolderBasedTrackingMappings">maxFolderBasedTrackingMappings</a>

Maximum number of Folder Based Tracking mappings user can add  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Max Folder Based Tracking Mappings</td></tr><tr><td>description</td><td>Maximum number of Folder Based Tracking mappings user can add</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>25</td></tr><tr><td>minimumValue</td><td>1</td></tr><tr><td>sourceName</td><td>maxfolderbasedtrackingmappings</td></tr></table>

### <a href=#privacyStatementUrl name="privacyStatementUrl">privacyStatementUrl</a>

Privacy Statement URL  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Privacy Statement URL</td></tr><tr><td>description</td><td>Privacy Statement URL</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>privacystatementurl</td></tr></table>

### <a href=#pluginTraceLogSetting name="pluginTraceLogSetting">pluginTraceLogSetting</a>

Plug-in Trace Log Setting for the Organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Plug-in Trace Log Setting</td></tr><tr><td>description</td><td>Plug-in Trace Log Setting for the Organization.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>plugintracelogsetting</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Off</td><td>0</td></tr><tr><td>en</td><td>Exception</td><td>1</td></tr><tr><td>en</td><td>All</td><td>2</td></tr></table></td></tr></table>

### <a href=#pluginTraceLogSetting_display name="pluginTraceLogSetting_display">pluginTraceLogSetting_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#isMailboxForcedUnlockingEnabled name="isMailboxForcedUnlockingEnabled">isMailboxForcedUnlockingEnabled</a>

Enable or disable forced unlocking for Server Side Sync mailboxes.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Mailbox Forced Unlocking Enabled</td></tr><tr><td>description</td><td>Enable or disable forced unlocking for Server Side Sync mailboxes.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>ismailboxforcedunlockingenabled</td></tr></table>

### <a href=#mailboxIntermittentIssueMinRange name="mailboxIntermittentIssueMinRange">mailboxIntermittentIssueMinRange</a>

Lower Threshold For Mailbox Intermittent Issue.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lower Threshold For Mailbox Intermittent Issue</td></tr><tr><td>description</td><td>Lower Threshold For Mailbox Intermittent Issue.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>mailboxintermittentissueminrange</td></tr></table>

### <a href=#mailboxPermanentIssueMinRange name="mailboxPermanentIssueMinRange">mailboxPermanentIssueMinRange</a>

Lower Threshold For Mailbox Permanent Issue.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lower Threshold For Mailbox Permanent Issue.</td></tr><tr><td>description</td><td>Lower Threshold For Mailbox Permanent Issue.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>mailboxpermanentissueminrange</td></tr></table>

### <a href=#highContrastThemeData name="highContrastThemeData">highContrastThemeData</a>

High contrast theme data for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>High contrast Theme Data</td></tr><tr><td>description</td><td>High contrast theme data for the organization.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>highcontrastthemedata</td></tr></table>

### <a href=#delegatedAdminUserId name="delegatedAdminUserId">delegatedAdminUserId</a>

Unique identifier of the delegated admin user for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delegated Admin</td></tr><tr><td>description</td><td>Unique identifier of the delegated admin user for the organization.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>delegatedadminuserid</td></tr></table>

### <a href=#isExternalSearchIndexEnabled name="isExternalSearchIndexEnabled">isExternalSearchIndexEnabled</a>

Select whether data can be synchronized with an external search index.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable external search data syncing</td></tr><tr><td>description</td><td>Select whether data can be synchronized with an external search index.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isexternalsearchindexenabled</td></tr></table>

### <a href=#isMobileOfflineEnabled name="isMobileOfflineEnabled">isMobileOfflineEnabled</a>

Indicates whether the feature MobileOffline should be enabled for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable MobileOffline for this Organization</td></tr><tr><td>description</td><td>Indicates whether the feature MobileOffline should be enabled for the organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>ismobileofflineenabled</td></tr></table>

### <a href=#isOfficeGraphEnabled name="isOfficeGraphEnabled">isOfficeGraphEnabled</a>

Indicates whether the feature OfficeGraph should be enabled for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable OfficeGraph for this Organization</td></tr><tr><td>description</td><td>Indicates whether the feature OfficeGraph should be enabled for the organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isofficegraphenabled</td></tr></table>

### <a href=#isOneDriveEnabled name="isOneDriveEnabled">isOneDriveEnabled</a>

Indicates whether the feature One Drive should be enabled for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable One Drive for this Organization</td></tr><tr><td>description</td><td>Indicates whether the feature One Drive should be enabled for the organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isonedriveenabled</td></tr></table>

### <a href=#externalPartyEntitySettings name="externalPartyEntitySettings">externalPartyEntitySettings</a>

XML string containing the ExternalPartyEnabled entities settings.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ExternalPartyEnabled Entities Settings.For internal use only</td></tr><tr><td>description</td><td>XML string containing the ExternalPartyEnabled entities settings.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>externalpartyentitysettings</td></tr></table>

### <a href=#externalPartyCorrelationKeys name="externalPartyCorrelationKeys">externalPartyCorrelationKeys</a>

XML string containing the ExternalPartyEnabled entities correlation keys for association of existing External Party instance entities to newly created IsExternalPartyEnabled entities.For internal use only  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ExternalPartyEnabled Entities correlation Keys</td></tr><tr><td>description</td><td>XML string containing the ExternalPartyEnabled entities correlation keys for association of existing External Party instance entities to newly created IsExternalPartyEnabled entities.For internal use only</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>externalpartycorrelationkeys</td></tr></table>

### <a href=#maxVerboseLoggingMailbox name="maxVerboseLoggingMailbox">maxVerboseLoggingMailbox</a>

Maximum number of mailboxes that can be toggled for verbose logging  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Max No Of Mailboxes To Enable For Verbose Logging</td></tr><tr><td>description</td><td>Maximum number of mailboxes that can be toggled for verbose logging</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>maxverboseloggingmailbox</td></tr></table>

### <a href=#maxVerboseLoggingSyncCycles name="maxVerboseLoggingSyncCycles">maxVerboseLoggingSyncCycles</a>

Maximum number of sync cycles for which verbose logging will be enabled by default  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum number of sync cycles for which verbose logging will be enabled by default</td></tr><tr><td>description</td><td>Maximum number of sync cycles for which verbose logging will be enabled by default</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>maxverboseloggingsynccycles</td></tr></table>

### <a href=#mobileOfflineSyncInterval name="mobileOfflineSyncInterval">mobileOfflineSyncInterval</a>

Sync interval for mobile offline.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Sync interval for mobile offline.</td></tr><tr><td>description</td><td>Sync interval for mobile offline.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>mobileofflinesyncinterval</td></tr></table>

### <a href=#officeGraphDelveUrl name="officeGraphDelveUrl">officeGraphDelveUrl</a>

The url to open the Delve for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>The url to open the Delve</td></tr><tr><td>description</td><td>The url to open the Delve for the organization.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>officegraphdelveurl</td></tr></table>

### <a href=#mobileOfflineMinLicenseTrial name="mobileOfflineMinLicenseTrial">mobileOfflineMinLicenseTrial</a>

Minimum number of user license required for mobile offline service by trial organization  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Minimum number of user license required for mobile offline service by trial organization</td></tr><tr><td>description</td><td>Minimum number of user license required for mobile offline service by trial organization</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>mobileofflineminlicensetrial</td></tr></table>

### <a href=#mobileOfflineMinLicenseProd name="mobileOfflineMinLicenseProd">mobileOfflineMinLicenseProd</a>

Minimum number of user license required for mobile offline service by production/preview organization  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Minimum number of user license required for mobile offline service by production/preview organization</td></tr><tr><td>description</td><td>Minimum number of user license required for mobile offline service by production/preview organization</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>mobileofflineminlicenseprod</td></tr></table>

### <a href=#daysSinceRecordLastModifiedMaxValue name="daysSinceRecordLastModifiedMaxValue">daysSinceRecordLastModifiedMaxValue</a>

The maximum value for the Mobile Offline setting Days since record last modified  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Max value of Days since record last modified</td></tr><tr><td>description</td><td>The maximum value for the Mobile Offline setting Days since record last modified</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>dayssincerecordlastmodifiedmaxvalue</td></tr></table>

### <a href=#taskBasedFlowEnabled name="taskBasedFlowEnabled">taskBasedFlowEnabled</a>

Select whether to turn on task flows for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Task Flow processes for this Organization</td></tr><tr><td>description</td><td>Select whether to turn on task flows for the organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>taskbasedflowenabled</td></tr></table>

### <a href=#showKBArticleDeprecationNotification name="showKBArticleDeprecationNotification">showKBArticleDeprecationNotification</a>

Select whether to display a KB article deprecation notification to the user.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Show KBArticle deprecation message to user</td></tr><tr><td>description</td><td>Select whether to display a KB article deprecation notification to the user.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>showkbarticledeprecationnotification</td></tr></table>

### <a href=#azureSchedulerJobCollectionName name="azureSchedulerJobCollectionName">azureSchedulerJobCollectionName</a>

For internal use only.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>For internal use only.</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>azureschedulerjobcollectionname</td></tr></table>

### <a href=#cortanaProactiveExperienceEnabled name="cortanaProactiveExperienceEnabled">cortanaProactiveExperienceEnabled</a>

Indicates whether the feature CortanaProactiveExperience Flow processes should be enabled for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Cortana Proactive Experience Flow processes for this Organization</td></tr><tr><td>description</td><td>Indicates whether the feature CortanaProactiveExperience Flow processes should be enabled for the organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>cortanaproactiveexperienceenabled</td></tr></table>

### <a href=#officeAppsAutoDeploymentEnabled name="officeAppsAutoDeploymentEnabled">officeAppsAutoDeploymentEnabled</a>

Indicates whether the Office Apps auto deployment is enabled for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Office Apps Auto Deployment for this Organization</td></tr><tr><td>description</td><td>Indicates whether the Office Apps auto deployment is enabled for the organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>officeappsautodeploymentenabled</td></tr></table>

### <a href=#appDesignerExperienceEnabled name="appDesignerExperienceEnabled">appDesignerExperienceEnabled</a>

Indicates whether the appDesignerExperience is enabled for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable App Designer Experience for this Organization</td></tr><tr><td>description</td><td>Indicates whether the appDesignerExperience is enabled for the organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>appdesignerexperienceenabled</td></tr></table>

### <a href=#enableImmersiveSkypeIntegration name="enableImmersiveSkypeIntegration">enableImmersiveSkypeIntegration</a>

Enable Integration with Immersive Skype  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Integration with Immersive Skype</td></tr><tr><td>description</td><td>Enable Integration with Immersive Skype</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>enableimmersiveskypeintegration</td></tr></table>

### <a href=#autoApplySLA name="autoApplySLA">autoApplySLA</a>

Indicates whether to Auto-apply SLA on case record update after SLA was manually applied.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Auto-apply SLA After Manually Over-riding</td></tr><tr><td>description</td><td>Indicates whether to Auto-apply SLA on case record update after SLA was manually applied.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>autoapplysla</td></tr></table>

### <a href=#isEmailServerProfileContentFilteringEnabled name="isEmailServerProfileContentFilteringEnabled">isEmailServerProfileContentFilteringEnabled</a>

Enable Email Server Profile content filtering  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Email Server Profile Content Filtering Enabled</td></tr><tr><td>description</td><td>Enable Email Server Profile content filtering</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isemailserverprofilecontentfilteringenabled</td></tr></table>

### <a href=#isDelegateAccessEnabled name="isDelegateAccessEnabled">isDelegateAccessEnabled</a>

Enable Delegation Access content  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Delegation Access Enabled</td></tr><tr><td>description</td><td>Enable Delegation Access content</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isdelegateaccessenabled</td></tr></table>

### <a href=#displayNavigationTour name="displayNavigationTour">displayNavigationTour</a>

Indicates whether or not navigation tour is displayed.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Display Navigation Tour</td></tr><tr><td>description</td><td>Indicates whether or not navigation tour is displayed.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>displaynavigationtour</td></tr></table>

### <a href=#useLegacyRendering name="useLegacyRendering">useLegacyRendering</a>

Select whether to use legacy form rendering.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Legacy Form Rendering</td></tr><tr><td>description</td><td>Select whether to use legacy form rendering.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>uselegacyrendering</td></tr></table>

### <a href=#defaultMobileOfflineProfileId name="defaultMobileOfflineProfileId">defaultMobileOfflineProfileId</a>

Unique identifier of the default mobile offline profile.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Default Mobile Offline Profile</td></tr><tr><td>description</td><td>Unique identifier of the default mobile offline profile.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>defaultmobileofflineprofileid</td></tr></table>

### <a href=#kaPrefix name="kaPrefix">kaPrefix</a>

Type the prefix to use for all knowledge articles in Microsoft Dynamics 365.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Knowledge Article Prefix</td></tr><tr><td>description</td><td>Type the prefix to use for all knowledge articles in Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>sourceName</td><td>kaprefix</td></tr></table>

### <a href=#currentKaNumber name="currentKaNumber">currentKaNumber</a>

Enter the first number to use for knowledge articles. Deprecated. Use SetAutoNumberSeed message.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Current Knowledge Article Number</td></tr><tr><td>description</td><td>Enter the first number to use for knowledge articles. Deprecated. Use SetAutoNumberSeed message.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>sourceName</td><td>currentkanumber</td></tr></table>

### <a href=#currentCategoryNumber name="currentCategoryNumber">currentCategoryNumber</a>

Enter the first number to use for Categories. Deprecated. Use SetAutoNumberSeed message.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Current Category Number</td></tr><tr><td>description</td><td>Enter the first number to use for Categories. Deprecated. Use SetAutoNumberSeed message.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>sourceName</td><td>currentcategorynumber</td></tr></table>

### <a href=#categoryPrefix name="categoryPrefix">categoryPrefix</a>

Type the prefix to use for all categories in Microsoft Dynamics 365.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Category Prefix</td></tr><tr><td>description</td><td>Type the prefix to use for all categories in Microsoft Dynamics 365.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>20</td></tr><tr><td>sourceName</td><td>categoryprefix</td></tr></table>

### <a href=#maximumEntitiesWithActiveSLA name="maximumEntitiesWithActiveSLA">maximumEntitiesWithActiveSLA</a>

Maximum number of active SLA allowed per entity in online  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum number of active SLA allowed per entity in online</td></tr><tr><td>description</td><td>Maximum number of active SLA allowed per entity in online</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>maximumentitieswithactivesla</td></tr></table>

### <a href=#maximumSLAKPIPerEntityWithActiveSLA name="maximumSLAKPIPerEntityWithActiveSLA">maximumSLAKPIPerEntityWithActiveSLA</a>

Maximum number of SLA KPI per active SLA allowed for entity in online  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum number of active SLA KPI allowed per entity in online</td></tr><tr><td>description</td><td>Maximum number of SLA KPI per active SLA allowed for entity in online</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>maximumslakpiperentitywithactivesla</td></tr></table>

### <a href=#isConflictDetectionEnabledForMobileClient name="isConflictDetectionEnabledForMobileClient">isConflictDetectionEnabledForMobileClient</a>

Information that specifies whether conflict detection for mobile client is enabled.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Conflict Detection for Mobile Client enabled</td></tr><tr><td>description</td><td>Information that specifies whether conflict detection for mobile client is enabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isconflictdetectionenabledformobileclient</td></tr></table>

### <a href=#isDelveActionHubIntegrationEnabled name="isDelveActionHubIntegrationEnabled">isDelveActionHubIntegrationEnabled</a>

Indicates whether the feature Action Hub should be enabled for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Action Hub for this Organization</td></tr><tr><td>description</td><td>Indicates whether the feature Action Hub should be enabled for the organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isdelveactionhubintegrationenabled</td></tr></table>

### <a href=#orgInsightsEnabled name="orgInsightsEnabled">orgInsightsEnabled</a>

Select whether to turn on OrgInsights for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable OrgInsights for this Organization</td></tr><tr><td>description</td><td>Select whether to turn on OrgInsights for the organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>orginsightsenabled</td></tr></table>

### <a href=#productRecommendationsEnabled name="productRecommendationsEnabled">productRecommendationsEnabled</a>

Select whether to turn on product recommendations for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Product Recommendations for this Organization</td></tr><tr><td>description</td><td>Select whether to turn on product recommendations for the organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>productrecommendationsenabled</td></tr></table>

### <a href=#textAnalyticsEnabled name="textAnalyticsEnabled">textAnalyticsEnabled</a>

Select whether to turn on text analytics for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Text Analytics for this Organization</td></tr><tr><td>description</td><td>Select whether to turn on text analytics for the organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>textanalyticsenabled</td></tr></table>

### <a href=#maxConditionsForMobileOfflineFilters name="maxConditionsForMobileOfflineFilters">maxConditionsForMobileOfflineFilters</a>

Maximum number of conditions allowed for mobile offline filters  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum number of conditions allowed for mobile offline filters</td></tr><tr><td>description</td><td>Maximum number of conditions allowed for mobile offline filters</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>maxconditionsformobileofflinefilters</td></tr></table>

### <a href=#isFolderAutoCreatedonSP name="isFolderAutoCreatedonSP">isFolderAutoCreatedonSP</a>

Select whether folders should be automatically created on SharePoint.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Automatically create folders</td></tr><tr><td>description</td><td>Select whether folders should be automatically created on SharePoint.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isfolderautocreatedonsp</td></tr></table>

### <a href=#powerBiFeatureEnabled name="powerBiFeatureEnabled">powerBiFeatureEnabled</a>

Indicates whether the Power BI feature should be enabled for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Power BI feature for this Organization</td></tr><tr><td>description</td><td>Indicates whether the Power BI feature should be enabled for the organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>powerbifeatureenabled</td></tr></table>

### <a href=#isActionCardEnabled name="isActionCardEnabled">isActionCardEnabled</a>

Indicates whether the feature Action Card should be enabled for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Action Card for this Organization</td></tr><tr><td>description</td><td>Indicates whether the feature Action Card should be enabled for the organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isactioncardenabled</td></tr></table>

### <a href=#isEmailMonitoringAllowed name="isEmailMonitoringAllowed">isEmailMonitoringAllowed</a>

Allow tracking recipient activity on sent emails.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allow tracking recipient activity on sent emails</td></tr><tr><td>description</td><td>Allow tracking recipient activity on sent emails.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isemailmonitoringallowed</td></tr></table>

### <a href=#isActivityAnalysisEnabled name="isActivityAnalysisEnabled">isActivityAnalysisEnabled</a>

Indicates whether the feature Relationship Analytics should be enabled for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Relationship Analytics for this Organization</td></tr><tr><td>description</td><td>Indicates whether the feature Relationship Analytics should be enabled for the organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isactivityanalysisenabled</td></tr></table>

### <a href=#isAutoDataCaptureEnabled name="isAutoDataCaptureEnabled">isAutoDataCaptureEnabled</a>

Indicates whether the feature Auto Capture should be enabled for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Auto Capture for this Organization</td></tr><tr><td>description</td><td>Indicates whether the feature Auto Capture should be enabled for the organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isautodatacaptureenabled</td></tr></table>

### <a href=#externalBaseUrl name="externalBaseUrl">externalBaseUrl</a>

Specify the base URL to use to look for external document suggestions.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>External Base URL</td></tr><tr><td>description</td><td>Specify the base URL to use to look for external document suggestions.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>externalbaseurl</td></tr></table>

### <a href=#isPreviewEnabledForActionCard name="isPreviewEnabledForActionCard">isPreviewEnabledForActionCard</a>

Indicates whether the Preview feature for Action Card should be enabled for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Preview Action Card feature for this Organization</td></tr><tr><td>description</td><td>Indicates whether the Preview feature for Action Card should be enabled for the organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>ispreviewenabledforactioncard</td></tr></table>

### <a href=#isPreviewForEmailMonitoringAllowed name="isPreviewForEmailMonitoringAllowed">isPreviewForEmailMonitoringAllowed</a>

Is Preview For Email Monitoring Allowed.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Allows Preview For Email Monitoring</td></tr><tr><td>description</td><td>Is Preview For Email Monitoring Allowed.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>ispreviewforemailmonitoringallowed</td></tr></table>

### <a href=#unresolveEmailAddressIfMultipleMatch name="unresolveEmailAddressIfMultipleMatch">unresolveEmailAddressIfMultipleMatch</a>

Indicates whether email address should be unresolved if multiple matches are found  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Set To,cc,bcc fields as unresolved if multiple matches are found</td></tr><tr><td>description</td><td>Indicates whether email address should be unresolved if multiple matches are found</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>unresolveemailaddressifmultiplematch</td></tr></table>

### <a href=#riErrorStatus name="riErrorStatus">riErrorStatus</a>

Error status of Relationship Insights provisioning.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Error status of Relationship Insights provisioning.</td></tr><tr><td>description</td><td>Error status of Relationship Insights provisioning.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rierrorstatus</td></tr></table>

### <a href=#widgetProperties name="widgetProperties">widgetProperties</a>

For Internal use only.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>For Internal use only.</td></tr><tr><td>description</td><td>For Internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>widgetproperties</td></tr></table>

### <a href=#enableMicrosoftFlowIntegration name="enableMicrosoftFlowIntegration">enableMicrosoftFlowIntegration</a>

Enable Integration with Microsoft Flow  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Integration with Microsoft Flow</td></tr><tr><td>description</td><td>Enable Integration with Microsoft Flow</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>enablemicrosoftflowintegration</td></tr></table>

### <a href=#isEnabledForAllRoles name="isEnabledForAllRoles">isEnabledForAllRoles</a>

Indicates whether appmodule is enabled for all roles  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>option set values for isenabledforallroles</td></tr><tr><td>description</td><td>Indicates whether appmodule is enabled for all roles</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isenabledforallroles</td></tr></table>

### <a href=#isPreviewForAutoCaptureEnabled name="isPreviewForAutoCaptureEnabled">isPreviewForAutoCaptureEnabled</a>

Indicates whether the feature Auto Capture should be enabled for the organization at Preview Settings.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Auto Capture for this Organization at Preview Settings</td></tr><tr><td>description</td><td>Indicates whether the feature Auto Capture should be enabled for the organization at Preview Settings.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>ispreviewforautocaptureenabled</td></tr></table>

### <a href=#defaultCrmCustomName name="defaultCrmCustomName">defaultCrmCustomName</a>

Name of the default crm custom.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name of the default app</td></tr><tr><td>description</td><td>Name of the default crm custom.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>defaultcrmcustomname</td></tr></table>

### <a href=#ACIWebEndpointUrl name="ACIWebEndpointUrl">ACIWebEndpointUrl</a>

ACI Web Endpoint URL.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>ACI Tenant URL.</td></tr><tr><td>description</td><td>ACI Web Endpoint URL.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>aciwebendpointurl</td></tr></table>

### <a href=#enableLPAuthoring name="enableLPAuthoring">enableLPAuthoring</a>

Select to enable learning path auhtoring.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Learning Path Authoring</td></tr><tr><td>description</td><td>Select to enable learning path auhtoring.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>enablelpauthoring</td></tr></table>

### <a href=#isResourceBookingExchangeSyncEnabled name="isResourceBookingExchangeSyncEnabled">isResourceBookingExchangeSyncEnabled</a>

Indicates if the synchronization of user resource booking with Exchange is enabled at organization level.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Resource booking synchronization enabled</td></tr><tr><td>description</td><td>Indicates if the synchronization of user resource booking with Exchange is enabled at organization level.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isresourcebookingexchangesyncenabled</td></tr></table>

### <a href=#isMobileClientOnDemandSyncEnabled name="isMobileClientOnDemandSyncEnabled">isMobileClientOnDemandSyncEnabled</a>

Information that specifies whether mobile client on demand sync is enabled.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Mobile Client On Demand Sync enabled</td></tr><tr><td>description</td><td>Information that specifies whether mobile client on demand sync is enabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>ismobileclientondemandsyncenabled</td></tr></table>

### <a href=#postMessageWhitelistDomains name="postMessageWhitelistDomains">postMessageWhitelistDomains</a>

For internal use only.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>For internal use only.</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>500</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>postmessagewhitelistdomains</td></tr></table>

### <a href=#isRelationshipInsightsEnabled name="isRelationshipInsightsEnabled">isRelationshipInsightsEnabled</a>

Indicates whether the feature Relationship Insights should be enabled for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Relationship Insights for this Organization</td></tr><tr><td>description</td><td>Indicates whether the feature Relationship Insights should be enabled for the organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isrelationshipinsightsenabled</td></tr></table>

### <a href=#resolveSimilarUnresolvedEmailAddress name="resolveSimilarUnresolvedEmailAddress">resolveSimilarUnresolvedEmailAddress</a>

Apply same email address to all unresolved matches when you manually resolve it for one  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Apply same email address to all unresolved matches when you manually resolve it for one</td></tr><tr><td>description</td><td>Apply same email address to all unresolved matches when you manually resolve it for one</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>resolvesimilarunresolvedemailaddress</td></tr></table>

### <a href=#isTextWrapEnabled name="isTextWrapEnabled">isTextWrapEnabled</a>

Information on whether text wrap is enabled.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Text Wrap</td></tr><tr><td>description</td><td>Information on whether text wrap is enabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>istextwrapenabled</td></tr></table>

### <a href=#sessionTimeoutEnabled name="sessionTimeoutEnabled">sessionTimeoutEnabled</a>

Information that specifies whether session timeout is enabled  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session timeout enabled</td></tr><tr><td>description</td><td>Information that specifies whether session timeout is enabled</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>sessiontimeoutenabled</td></tr></table>

### <a href=#sessionTimeoutInMins name="sessionTimeoutInMins">sessionTimeoutInMins</a>

Session timeout in minutes  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session timeout in minutes</td></tr><tr><td>description</td><td>Session timeout in minutes</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sessiontimeoutinmins</td></tr></table>

### <a href=#sessionTimeoutReminderInMins name="sessionTimeoutReminderInMins">sessionTimeoutReminderInMins</a>

Session timeout reminder in minutes  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Session timeout reminder in minutes</td></tr><tr><td>description</td><td>Session timeout reminder in minutes</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>sessiontimeoutreminderinmins</td></tr></table>

### <a href=#microsoftFlowEnvironment name="microsoftFlowEnvironment">microsoftFlowEnvironment</a>

Environment selected for Integration with Microsoft Flow  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Environment selected for Integration with Microsoft Flow</td></tr><tr><td>description</td><td>Environment selected for Integration with Microsoft Flow</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1024</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>microsoftflowenvironment</td></tr></table>

### <a href=#inactivityTimeoutEnabled name="inactivityTimeoutEnabled">inactivityTimeoutEnabled</a>

Information that specifies whether Inactivity timeout is enabled  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inactivity timeout enabled</td></tr><tr><td>description</td><td>Information that specifies whether Inactivity timeout is enabled</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>inactivitytimeoutenabled</td></tr></table>

### <a href=#inactivityTimeoutInMins name="inactivityTimeoutInMins">inactivityTimeoutInMins</a>

Inactivity timeout in minutes  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inactivity timeout in minutes</td></tr><tr><td>description</td><td>Inactivity timeout in minutes</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>inactivitytimeoutinmins</td></tr></table>

### <a href=#inactivityTimeoutReminderInMins name="inactivityTimeoutReminderInMins">inactivityTimeoutReminderInMins</a>

Inactivity timeout reminder in minutes  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Inactivity timeout reminder in minutes</td></tr><tr><td>description</td><td>Inactivity timeout reminder in minutes</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>inactivitytimeoutreminderinmins</td></tr></table>

### <a href=#syncOptInSelection name="syncOptInSelection">syncOptInSelection</a>

Indicates the selection to use the dynamics 365 azure sync framework or server side sync.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable dynamics 365 azure sync framework for this organization.</td></tr><tr><td>description</td><td>Indicates the selection to use the dynamics 365 azure sync framework or server side sync.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>syncoptinselection</td></tr></table>

### <a href=#syncOptInSelectionStatus name="syncOptInSelectionStatus">syncOptInSelectionStatus</a>

Indicates the status of the opt-in or opt-out operation for dynamics 365 azure sync.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status of opt-in or opt-out operation for dynamics 365 azure sync.</td></tr><tr><td>description</td><td>Indicates the status of the opt-in or opt-out operation for dynamics 365 azure sync.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>syncoptinselectionstatus</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Processing</td><td>1</td></tr><tr><td>en</td><td>Passed</td><td>2</td></tr><tr><td>en</td><td>Failed</td><td>3</td></tr></table></td></tr></table>

### <a href=#syncOptInSelectionStatus_display name="syncOptInSelectionStatus_display">syncOptInSelectionStatus_display</a>

First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#isActionSupportFeatureEnabled name="isActionSupportFeatureEnabled">isActionSupportFeatureEnabled</a>

Information that specifies whether Action Support Feature is enabled  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Action Support Feature enabled</td></tr><tr><td>description</td><td>Information that specifies whether Action Support Feature is enabled</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isactionsupportfeatureenabled</td></tr></table>

### <a href=#isBPFEntityCustomizationFeatureEnabled name="isBPFEntityCustomizationFeatureEnabled">isBPFEntityCustomizationFeatureEnabled</a>

Information that specifies whether BPF Entity Customization Feature is enabled  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>BPF Entity Customization Feature enabled</td></tr><tr><td>description</td><td>Information that specifies whether BPF Entity Customization Feature is enabled</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isbpfentitycustomizationfeatureenabled</td></tr></table>

### <a href=#boundDashboardDefaultCardExpanded name="boundDashboardDefaultCardExpanded">boundDashboardDefaultCardExpanded</a>

Display cards in expanded state for interactive dashboard  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Display cards in expanded state for Interactive Dashboard</td></tr><tr><td>description</td><td>Display cards in expanded state for interactive dashboard</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>bounddashboarddefaultcardexpanded</td></tr></table>

### <a href=#maxActionStepsInBPF name="maxActionStepsInBPF">maxActionStepsInBPF</a>

Maximum number of actionsteps allowed in a BPF  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Maximum number of actionsteps allowed in a BPF</td></tr><tr><td>description</td><td>Maximum number of actionsteps allowed in a BPF</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>100</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>maxactionstepsinbpf</td></tr></table>

### <a href=#serveStaticResourcesFromAzureCDN name="serveStaticResourcesFromAzureCDN">serveStaticResourcesFromAzureCDN</a>

Serve Static Content From CDN  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Serve Static Content From CDN</td></tr><tr><td>description</td><td>Serve Static Content From CDN</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>servestaticresourcesfromazurecdn</td></tr></table>

### <a href=#isExternalFileStorageEnabled name="isExternalFileStorageEnabled">isExternalFileStorageEnabled</a>

Indicates whether the organization's files are being stored in Azure.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable external file storage</td></tr><tr><td>description</td><td>Indicates whether the organization's files are being stored in Azure.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isexternalfilestorageenabled</td></tr></table>

### <a href=#clientFeatureSet name="clientFeatureSet">clientFeatureSet</a>

Client Features to be enabled as an XML BLOB.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Client Feature Set</td></tr><tr><td>description</td><td>Client Features to be enabled as an XML BLOB.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1073741823</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>clientfeatureset</td></tr></table>

### <a href=#isReadAuditEnabled name="isReadAuditEnabled">isReadAuditEnabled</a>

Enable or disable auditing of read operations.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Is Read Auditing Enabled</td></tr><tr><td>description</td><td>Enable or disable auditing of read operations.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>isreadauditenabled</td></tr></table>

### <a href=#isNotesAnalysisEnabled name="isNotesAnalysisEnabled">isNotesAnalysisEnabled</a>

Indicates whether the feature Notes Analysis should be enabled for the organization.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Notes Analysis for this Organization</td></tr><tr><td>description</td><td>Indicates whether the feature Notes Analysis should be enabled for the organization.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isnotesanalysisenabled</td></tr></table>

### <a href=#allowLegacyDialogsEmbedding name="allowLegacyDialogsEmbedding">allowLegacyDialogsEmbedding</a>

Enable embedding of certain legacy dialogs in Unified Interface browser client  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable embedding of certain legacy dialogs in Unified Interface browser client</td></tr><tr><td>description</td><td>Enable embedding of certain legacy dialogs in Unified Interface browser client</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>allowlegacydialogsembedding</td></tr></table>

### <a href=#appointmentRichEditorExperience name="appointmentRichEditorExperience">appointmentRichEditorExperience</a>

Information on whether rich editing experience for Appointment is enabled.  
First included in: applicationCommon/Organization (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Enable Rich Editing Experience for Appointment</td></tr><tr><td>description</td><td>Information on whether rich editing experience for Appointment is enabled.</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>sourceName</td><td>appointmentricheditorexperience</td></tr></table>

---
title: Case
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/5/2019
ms.author: tpalmer
---

# Case

## Properties

Display Name: Case

Description: Service request case associated with a contract.

Latest Version: 0.8.1

Entity Definition on GitHub: [https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Case.cdm.json](https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Case.cdm.json)

## Instances

[/core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case](../../service/Case.md)

[/core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Case.cdm.json/Case](Case.md)

## Attributes - Summary

|Name|Description|First Included in Instance|
|---|---|---|
|[createdOn](#createdOn)|Date and time when the record was created.|[service/Case](../../service/Case.md)|
|[createdBy](#createdBy)|Shows who created the record.|[service/Case](../../service/Case.md)|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|[service/Case](../../service/Case.md)|
|[modifiedBy](#modifiedBy)|Shows who last updated the record.|[service/Case](../../service/Case.md)|
|[createdOnBehalfBy](#createdOnBehalfBy)|Shows who created the record on behalf of another user.|[service/Case](../../service/Case.md)|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Shows who last updated the record on behalf of another user.|[service/Case](../../service/Case.md)|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|[service/Case](../../service/Case.md)|
|[importSequenceNumber](#importSequenceNumber)|Unique identifier of the data import or data migration that created this record.|[service/Case](../../service/Case.md)|
|[ownerIdType](#ownerIdType)|The type of owner, either User or Team.|[service/Case](../../service/Case.md)|
|[ownerId](#ownerId)|Owner Id|[service/Case](../../service/Case.md)|
|[owningBusinessUnit](#owningBusinessUnit)|Unique identifier for the business unit that owns the record|[service/Case](../../service/Case.md)|
|[owningUser](#owningUser)|Unique identifier of the user that owns the activity.|[service/Case](../../service/Case.md)|
|[owningTeam](#owningTeam)|Unique identifier for the team that owns the record.|[service/Case](../../service/Case.md)|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|[service/Case](../../service/Case.md)|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|[service/Case](../../service/Case.md)|
|[versionNumber](#versionNumber)|Version Number|[service/Case](../../service/Case.md)|
|[incidentId](#incidentId)|Unique identifier of the case.|[service/Case](../../service/Case.md)|
|[emailAddress](#emailAddress)|The primary email address for the entity.|[service/Case](../../service/Case.md)|
|[title](#title)|Type a subject or descriptive name, such as the request, issue, or company name, to identify the case in Microsoft Dynamics 365 views.|[service/Case](../../service/Case.md)|
|[processId](#processId)|Contains the id of the process associated with the entity.|[service/Case](../../service/Case.md)|
|[stageId](#stageId)|Contains the id of the stage where the entity is located.|[service/Case](../../service/Case.md)|
|[traversedPath](#traversedPath)|A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.|[service/Case](../../service/Case.md)|
|[activitiesComplete](#activitiesComplete)|This attribute is used for Sample Service Business Processes.|[service/Case](../../service/Case.md)|
|[actualServiceUnits](#actualServiceUnits)|Type the number of service units that were actually required to resolve the case.|[service/Case](../../service/Case.md)|
|[billedServiceUnits](#billedServiceUnits)|Type the number of service units that were billed to the customer for the case.|[service/Case](../../service/Case.md)|
|[blockedProfile](#blockedProfile)|Details whether the profile is blocked or not.|[service/Case](../../service/Case.md)|
|[caseOriginCode](#caseOriginCode)|Select how contact about the case was originated, such as email, phone, or web, for use in reporting and analysis.|[service/Case](../../service/Case.md)|
|[caseOriginCode_display](#caseOriginCode_display)||[service/Case](../../service/Case.md)|
|[caseTypeCode](#caseTypeCode)|Select the type of case to identify the incident for use in case routing and analysis.|[service/Case](../../service/Case.md)|
|[caseTypeCode_display](#caseTypeCode_display)||[service/Case](../../service/Case.md)|
|[checkEmail](#checkEmail)|This attribute is used for Sample Service Business Processes.|[service/Case](../../service/Case.md)|
|[contractDetailId](#contractDetailId)|Choose the contract line that the case should be logged under to make sure the customer is charged correctly.|[service/Case](../../service/Case.md)|
|[contractId](#contractId)|Choose the service contract that the case should be logged under to make sure the customer is eligible for support services.|[service/Case](../../service/Case.md)|
|[contractServiceLevelCode](#contractServiceLevelCode)|Select the service level for the case to make sure the case is handled correctly.|[service/Case](../../service/Case.md)|
|[contractServiceLevelCode_display](#contractServiceLevelCode_display)||[service/Case](../../service/Case.md)|
|[customerIdType](#customerIdType)|The type of customer, either Account or Contact.|[service/Case](../../service/Case.md)|
|[customerId](#customerId)|The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.|[service/Case](../../service/Case.md)|
|[customerSatisfactionCode](#customerSatisfactionCode)|Select the customer's level of satisfaction with the handling and resolution of the case.|[service/Case](../../service/Case.md)|
|[customerSatisfactionCode_display](#customerSatisfactionCode_display)||[service/Case](../../service/Case.md)|
|[description](#description)|Type additional information to describe the case to assist the service team in reaching a resolution.|[service/Case](../../service/Case.md)|
|[entitlementId](#entitlementId)|Choose the entitlement that is applicable for the case.|[service/Case](../../service/Case.md)|
|[SLAId](#SLAId)|Choose the service level agreement (SLA) that you want to apply to the case record.|[service/Case](../../service/Case.md)|
|[firstResponseSLAStatus](#firstResponseSLAStatus)|Shows the status of the initial response time for the case according to the terms of the SLA.|[service/Case](../../service/Case.md)|
|[firstResponseSLAStatus_display](#firstResponseSLAStatus_display)||[service/Case](../../service/Case.md)|
|[followupBy](#followupBy)|Enter the date by which a customer service representative has to follow up with the customer on this case.|[service/Case](../../service/Case.md)|
|[followUpTaskCreated](#followUpTaskCreated)|This attribute is used for Sample Service Business Processes.|[service/Case](../../service/Case.md)|
|[incidentStageCode](#incidentStageCode)|Select the current stage of the service process for the case to assist service team members when they review or transfer a case.|[service/Case](../../service/Case.md)|
|[incidentStageCode_display](#incidentStageCode_display)||[service/Case](../../service/Case.md)|
|[isDecrementing](#isDecrementing)|For system use only.|[service/Case](../../service/Case.md)|
|[kbArticleId](#kbArticleId)|Choose the article that contains additional information or a resolution for the case, for reference during research or follow up with the customer.|[service/Case](../../service/Case.md)|
|[messageTypeCode](#messageTypeCode)|Shows whether the post originated as a public or private message.|[service/Case](../../service/Case.md)|
|[messageTypeCode_display](#messageTypeCode_display)||[service/Case](../../service/Case.md)|
|[priorityCode](#priorityCode)|Select the priority so that preferred customers or critical issues are handled quickly.|[service/Case](../../service/Case.md)|
|[priorityCode_display](#priorityCode_display)||[service/Case](../../service/Case.md)|
|[productId](#productId)|Choose the product associated with the case to identify warranty, service, or other product issues and be able to report the number of incidents for each product.|[service/Case](../../service/Case.md)|
|[productSerialNumber](#productSerialNumber)|Type the serial number of the product that is associated with this case, so that the number of cases per product can be reported.|[service/Case](../../service/Case.md)|
|[existingCase](#existingCase)|Select an existing case for the customer that has been populated. For internal use only.|[service/Case](../../service/Case.md)|
|[resolveBySLAStatus](#resolveBySLAStatus)|Shows the status of the resolution time for the case according to the terms of the SLA.|[service/Case](../../service/Case.md)|
|[resolveBySLAStatus_display](#resolveBySLAStatus_display)||[service/Case](../../service/Case.md)|
|[responsibleContactId](#responsibleContactId)|Choose an additional customer contact who can also help resolve the case.|[service/Case](../../service/Case.md)|
|[sentimentValue](#sentimentValue)|Value derived after assessing words commonly associated with a negative, neutral, or positive sentiment that occurs in a social post. Sentiment information can also be reported as numeric values.|[service/Case](../../service/Case.md)|
|[influenceScore](#influenceScore)|Will contain the Influencer score coming from NetBreeze.|[service/Case](../../service/Case.md)|
|[serviceStage](#serviceStage)|Select the stage, in the case resolution process, that the case is in.|[service/Case](../../service/Case.md)|
|[serviceStage_display](#serviceStage_display)||[service/Case](../../service/Case.md)|
|[severityCode](#severityCode)|Select the severity of this case to indicate the incident's impact on the customer's business.|[service/Case](../../service/Case.md)|
|[severityCode_display](#severityCode_display)||[service/Case](../../service/Case.md)|
|[SLAInvokedId](#SLAInvokedId)|Last SLA that was applied to this case. This field is for internal use only.|[service/Case](../../service/Case.md)|
|[socialProfileId](#socialProfileId)|Unique identifier of the social profile with which the case is associated.|[service/Case](../../service/Case.md)|
|[stateCode](#stateCode)|Shows whether the case is active, resolved, or canceled. Resolved and canceled cases are read-only and can't be edited unless they are reactivated.|[service/Case](../../service/Case.md)|
|[stateCode_display](#stateCode_display)||[service/Case](../../service/Case.md)|
|[statusCode](#statusCode)|Select the case's status.|[service/Case](../../service/Case.md)|
|[statusCode_display](#statusCode_display)||[service/Case](../../service/Case.md)|
|[subjectId](#subjectId)|Choose the subject for the case, such as catalog request or product complaint, so customer service managers can identify frequent requests or problem areas. Administrators can configure subjects under Business Management in the Settings area.|[service/Case](../../service/Case.md)|
|[ticketNumber](#ticketNumber)|Shows the case number for customer reference and searching capabilities. This cannot be modified.|[service/Case](../../service/Case.md)|
|[masterId](#masterId)|Choose the primary case the current case was merged into.|[service/Case](../../service/Case.md)|
|[parentCaseId](#parentCaseId)|Choose the parent case for a case.|[service/Case](../../service/Case.md)|
|[numberOfChildIncidents](#numberOfChildIncidents)|Number of child incidents associated with the incident.|[service/Case](../../service/Case.md)|
|[merged](#merged)|Tells whether the incident has been merged with another incident.|[service/Case](../../service/Case.md)|
|[routeCase](#routeCase)|Tells whether the incident has been routed to queue or not.|[service/Case](../../service/Case.md)|
|[resolveBy](#resolveBy)|Enter the date by when the case must be resolved.|[service/Case](../../service/Case.md)|
|[responseBy](#responseBy)|For internal use only.|[service/Case](../../service/Case.md)|
|[customerContacted](#customerContacted)|Tells whether customer service representative has contacted the customer or not.|[service/Case](../../service/Case.md)|
|[firstResponseSent](#firstResponseSent)|Indicates if the first response has been sent.|[service/Case](../../service/Case.md)|
|[isEscalated](#isEscalated)|Indicates if the case has been escalated.|[service/Case](../../service/Case.md)|
|[escalatedOn](#escalatedOn)|Indicates the date and time when the case was escalated.|[service/Case](../../service/Case.md)|
|[primaryContactId](#primaryContactId)|Select a primary contact for this case.|[service/Case](../../service/Case.md)|
|[onHoldTime](#onHoldTime)|Shows the duration in minutes for which the case was on hold.|[service/Case](../../service/Case.md)|
|[lastOnHoldTime](#lastOnHoldTime)|Contains the date time stamp of the last on hold time.|[service/Case](../../service/Case.md)|
|[resolveByKPIId](#resolveByKPIId)|For internal use only.|[service/Case](../../service/Case.md)|
|[firstResponseByKPIId](#firstResponseByKPIId)|For internal use only.|[service/Case](../../service/Case.md)|
|[decrementEntitlementTerm](#decrementEntitlementTerm)|Shows whether terms of the associated entitlement should be decremented or not.|[service/Case](../../service/Case.md)|
|[entityImageId](#entityImageId)||[service/Case](../../service/Case.md)|
|[accountId](#accountId)|Unique identifier of the account with which the case is associated.|[service/Case](../../service/Case.md)|
|[contactId](#contactId)|Unique identifier of the contact associated with the case.|[service/Case](../../service/Case.md)|
|[exchangeRate](#exchangeRate)|Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.|[service/Case](../../service/Case.md)|
|[transactionCurrencyId](#transactionCurrencyId)|Choose the local currency for the record to make sure budgets are reported in the correct currency.|[service/Case](../../service/Case.md)|
|[createdByExternalParty](#createdByExternalParty)|Shows the external party who created the record.|[service/Case](../../service/Case.md)|
|[modifiedByExternalParty](#modifiedByExternalParty)|Shows the external party who modified the record.|[service/Case](../../service/Case.md)|
|[adxCreatedByIPAddress](#adxCreatedByIPAddress)||[portals/Case](Case.md)|
|[adxCreatedByUsername](#adxCreatedByUsername)||[portals/Case](Case.md)|
|[adxModifiedByIPAddress](#adxModifiedByIPAddress)||[portals/Case](Case.md)|
|[adxModifiedByUsername](#adxModifiedByUsername)||[portals/Case](Case.md)|
|[partnerContact](#partnerContact)|Allows a partner contact to be assigned to a specific case.|[portals/Case](Case.md)|
|[partnerid](#partnerid)|Creates a Relationship between a Partner (account) and a case for indirect service arrangements.|[portals/Case](Case.md)|
|[publishToWeb](#publishToWeb)|If set to Yes, the case will be visible and searchable on portals connected to this organization.|[portals/Case](Case.md)|
|[resolution](#resolution)||[portals/Case](Case.md)|
|[resolutionDate](#resolutionDate)||[portals/Case](Case.md)|
|[stepsToReproduce](#stepsToReproduce)||[portals/Case](Case.md)|

## Attribute - Details

### <a name="createdOn">createdOn</a>

Date and time when the record was created.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Created On</td></tr>
<tr><td>description</td><td>Date and time when the record was created.</td></tr>
<tr><td>dataFormat</td><td>DateTimeOffset</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>createdon</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the createdOn attribute are listed below.</summary>

##### is.dataFormat.date

##### means.measurement.date

##### is.dataFormat.time

##### means.measurement.time

##### means.measurement.date.creation

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Created On</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Date and time when the record was created.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>createdon</td><td>string</td><td></td></tr>
</table>

</details>

### <a name="createdBy">createdBy</a>

Shows who created the record.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Created By</td></tr>
<tr><td>description</td><td>Shows who created the record.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>createdby</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the createdBy attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### means.userId

contains a userId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Created By</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows who created the record.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>createdby</td><td>string</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "userId",
  "name": "createdBy",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Created By"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Shows who created the record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Created By",
  "description": "Shows who created the record.",
  "isNullable": true,
  "sourceName": "createdby"
}
```

</details>

### <a name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Modified On</td></tr>
<tr><td>description</td><td>Date and time when the record was modified.</td></tr>
<tr><td>dataFormat</td><td>DateTimeOffset</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>modifiedon</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the modifiedOn attribute are listed below.</summary>

##### is.dataFormat.date

##### means.measurement.date

##### is.dataFormat.time

##### means.measurement.time

##### means.measurement.date.modify

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Modified On</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Date and time when the record was modified.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>modifiedon</td><td>string</td><td></td></tr>
</table>

</details>

### <a name="modifiedBy">modifiedBy</a>

Shows who last updated the record.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Modified By</td></tr>
<tr><td>description</td><td>Shows who last updated the record.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>modifiedby</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the modifiedBy attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### means.userId

contains a userId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Modified By</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows who last updated the record.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>modifiedby</td><td>string</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "userId",
  "name": "modifiedBy",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Modified By"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Shows who last updated the record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Modified By",
  "description": "Shows who last updated the record.",
  "isNullable": true,
  "sourceName": "modifiedby"
}
```

</details>

### <a name="createdOnBehalfBy">createdOnBehalfBy</a>

Shows who created the record on behalf of another user.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Created By (Delegate)</td></tr>
<tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>createdonbehalfby</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the createdOnBehalfBy attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### means.userId

contains a userId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Created By (Delegate)</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows who created the record on behalf of another user.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>createdonbehalfby</td><td>string</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "userId",
  "name": "createdOnBehalfBy",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Created By (Delegate)"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Shows who created the record on behalf of another user."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Created By (Delegate)",
  "description": "Shows who created the record on behalf of another user.",
  "isNullable": true,
  "sourceName": "createdonbehalfby"
}
```

</details>

### <a name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Shows who last updated the record on behalf of another user.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Modified By (Delegate)</td></tr>
<tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>modifiedonbehalfby</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the modifiedOnBehalfBy attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### means.userId

contains a userId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Modified By (Delegate)</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows who last updated the record on behalf of another user.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>modifiedonbehalfby</td><td>string</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "userId",
  "name": "modifiedOnBehalfBy",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Modified By (Delegate)"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Shows who last updated the record on behalf of another user."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Modified By (Delegate)",
  "description": "Shows who last updated the record on behalf of another user.",
  "isNullable": true,
  "sourceName": "modifiedonbehalfby"
}
```

</details>

### <a name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Record Created On</td></tr>
<tr><td>description</td><td>Date and time that the record was migrated.</td></tr>
<tr><td>dataFormat</td><td>DateTimeOffset</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>overriddencreatedon</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the overriddenCreatedOn attribute are listed below.</summary>

##### is.dataFormat.date

##### means.measurement.date

##### is.dataFormat.time

##### means.measurement.time

##### means.measurement.date.creation

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Record Created On</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Date and time that the record was migrated.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>overriddencreatedon</td><td>string</td><td></td></tr>
</table>

</details>

### <a name="importSequenceNumber">importSequenceNumber</a>

Unique identifier of the data import or data migration that created this record.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Import Sequence Number</td></tr>
<tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>maximumValue</td><td>2147483647</td></tr>
<tr><td>minimumValue</td><td>-2147483648</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>importsequencenumber</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the importSequenceNumber attribute are listed below.</summary>

##### is.dataFormat.integer

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Import Sequence Number</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the data import or data migration that created this record.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>importsequencenumber</td><td>string</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-2147483648</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="ownerIdType">ownerIdType</a>

The type of owner, either User or Team.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Owner Type</td></tr>
<tr><td>description</td><td>The type of owner, either User or Team.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
<tr><td>sourceName</td><td>owneridtype</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the ownerIdType attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.entityName

##### is.readOnly

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Owner Type</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The type of owner, either User or Team.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>owneridtype</td><td>string</td><td></td></tr>
</table>

##### is.linkedEntity.name

Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.

##### is.CDS.owner

contains a User or Team ID

</details>

### <a name="ownerId">ownerId</a>

Owner Id

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Owner</td></tr>
<tr><td>description</td><td>Owner Id</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>sourceName</td><td>ownerid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the ownerId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Owner</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Owner Id</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>ownerid</td><td>string</td><td></td></tr>
</table>

##### is.linkedEntity.identifier

Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.

##### is.CDS.owner

contains a User or Team ID

</details>

### <a name="owningBusinessUnit">owningBusinessUnit</a>

Unique identifier for the business unit that owns the record

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Owning Business Unit</td></tr>
<tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>owningbusinessunit</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the owningBusinessUnit attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Owning Business Unit</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier for the business unit that owns the record</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>owningbusinessunit</td><td>string</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "owningBusinessUnit",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Owning Business Unit"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier for the business unit that owns the record"
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Owning Business Unit",
  "description": "Unique identifier for the business unit that owns the record",
  "isNullable": true,
  "sourceName": "owningbusinessunit"
}
```

</details>

### <a name="owningUser">owningUser</a>

Unique identifier of the user that owns the activity.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Owning User</td></tr>
<tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>owninguser</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the owningUser attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### means.userId

contains a userId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Owning User</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the user that owns the activity.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>owninguser</td><td>string</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "userId",
  "name": "owningUser",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Owning User"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier for the user that owns the record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Owning User",
  "description": "Unique identifier for the user that owns the record.",
  "isNullable": true,
  "sourceName": "owninguser"
}
```

</details>

### <a name="owningTeam">owningTeam</a>

Unique identifier for the team that owns the record.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Owning Team</td></tr>
<tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>owningteam</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the owningTeam attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Owning Team</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier for the team that owns the record.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>owningteam</td><td>string</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "owningTeam",
  "appliedTraits": [
    "is.CDS.standard",
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Owning Team"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier for the team that owns the record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Owning Team",
  "description": "Unique identifier for the team that owns the record.",
  "isNullable": true,
  "sourceName": "owningteam"
}
```

</details>

### <a name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr>
<tr><td>description</td><td>For internal use only.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>maximumValue</td><td>2147483647</td></tr>
<tr><td>minimumValue</td><td>-1</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the timeZoneRuleVersionNumber attribute are listed below.</summary>

##### is.dataFormat.integer

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Time Zone Rule Version Number</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>For internal use only.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>timezoneruleversionnumber</td><td>string</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-1</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr>
<tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>maximumValue</td><td>2147483647</td></tr>
<tr><td>minimumValue</td><td>-1</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the UTCConversionTimeZoneCode attribute are listed below.</summary>

##### is.dataFormat.integer

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>UTC Conversion Time Zone Code</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Time zone code that was in use when the record was created.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>utcconversiontimezonecode</td><td>string</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-1</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="versionNumber">versionNumber</a>

Version Number

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Version Number</td></tr>
<tr><td>description</td><td>Version Number</td></tr>
<tr><td>dataFormat</td><td>Int64</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>versionnumber</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the versionNumber attribute are listed below.</summary>

##### is.dataFormat.integer

##### is.dataFormat.big

##### means.measurement.version

##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Version Number</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Version Number</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>versionnumber</td><td>string</td><td></td></tr>
</table>

</details>

### <a name="incidentId">incidentId</a>

Unique identifier of the case.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Case</td></tr>
<tr><td>description</td><td>Unique identifier of the case.</td></tr>
<tr><td>isPrimaryKey</td><td>true</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>sourceName</td><td>incidentid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the incidentId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.identifiedBy

names a specifc identity attribute to use with an entity

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>attribute</td><td>"Case_/hasAttributes/incidentId"</td><td>attribute</td><td></td></tr>
</table>

Definition:

```
"Case_/hasAttributes/incidentId"
```

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Case</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the case.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>incidentid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10000</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "identifiedBy",
  "dataType": ...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "identifiedBy",
  "dataType": "entityId",
  "name": "incidentId",
  "appliedTraits": [
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "systemrequired"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Case"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier of the case."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Case",
  "description": "Unique identifier of the case.",
  "sourceName": "incidentid",
  "sourceOrdering": 10000
}
```

</details>

### <a name="emailAddress">emailAddress</a>

The primary email address for the entity.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Email Address</td></tr>
<tr><td>description</td><td>The primary email address for the entity.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>100</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>emailaddress</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the emailAddress attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.identity.service.email

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Email Address</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The primary email address for the entity.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>emailaddress</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10024</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>100</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="title">title</a>

Type a subject or descriptive name, such as the request, issue, or company name, to identify the case in Microsoft Dynamics 365 views.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Case Title</td></tr>
<tr><td>description</td><td>Type a subject or descriptive name, such as the request, issue, or company name, to identify the case in Microsoft Dynamics 365 views.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>200</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>title</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the title attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>required</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Case Title</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type a subject or descriptive name, such as the request, issue, or company name, to identify the case in Microsoft Dynamics 365 views.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>title</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10029</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>200</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="processId">processId</a>

Contains the id of the process associated with the entity.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Process Id</td></tr>
<tr><td>description</td><td>Contains the id of the process associated with the entity.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>processid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the processId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Process Id</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Contains the id of the process associated with the entity.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>processid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10030</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="stageId">stageId</a>

Contains the id of the stage where the entity is located.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Stage Id</td></tr>
<tr><td>description</td><td>Contains the id of the stage where the entity is located.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>stageid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the stageId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Stage Id</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Contains the id of the stage where the entity is located.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>stageid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10031</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="traversedPath">traversedPath</a>

A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Traversed Path</td></tr>
<tr><td>description</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>1250</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>traversedpath</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the traversedPath attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Traversed Path</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>A comma separated list of string values representing the unique identifiers of stages in a Business Process Flow Instance in the order that they occur.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>traversedpath</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10032</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>1250</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="activitiesComplete">activitiesComplete</a>

This attribute is used for Sample Service Business Processes.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Activities Complete</td></tr>
<tr><td>description</td><td>This attribute is used for Sample Service Business Processes.</td></tr>
<tr><td>dataFormat</td><td>Boolean</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>activitiescomplete</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the activitiesComplete attribute are listed below.</summary>

##### is.dataFormat.boolean

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Activities Complete</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>This attribute is used for Sample Service Business Processes.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>activitiescomplete</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10033</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="actualServiceUnits">actualServiceUnits</a>

Type the number of service units that were actually required to resolve the case.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Actual Service Units</td></tr>
<tr><td>description</td><td>Type the number of service units that were actually required to resolve the case.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>maximumValue</td><td>1000000000</td></tr>
<tr><td>minimumValue</td><td>0</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>actualserviceunits</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the actualServiceUnits attribute are listed below.</summary>

##### is.dataFormat.integer

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Actual Service Units</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type the number of service units that were actually required to resolve the case.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>actualserviceunits</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10035</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>0</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>1000000000</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="billedServiceUnits">billedServiceUnits</a>

Type the number of service units that were billed to the customer for the case.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Billed Service Units</td></tr>
<tr><td>description</td><td>Type the number of service units that were billed to the customer for the case.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>maximumValue</td><td>1000000000</td></tr>
<tr><td>minimumValue</td><td>0</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>billedserviceunits</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the billedServiceUnits attribute are listed below.</summary>

##### is.dataFormat.integer

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Billed Service Units</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type the number of service units that were billed to the customer for the case.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>billedserviceunits</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10036</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>0</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>1000000000</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="blockedProfile">blockedProfile</a>

Details whether the profile is blocked or not.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Blocked Profile</td></tr>
<tr><td>description</td><td>Details whether the profile is blocked or not.</td></tr>
<tr><td>dataFormat</td><td>Boolean</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>blockedprofile</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the blockedProfile attribute are listed below.</summary>

##### is.dataFormat.boolean

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Blocked Profile</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Details whether the profile is blocked or not.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>blockedprofile</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10037</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="caseOriginCode">caseOriginCode</a>

Select how contact about the case was originated, such as email, phone, or web, for use in reporting and analysis.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Origin</td></tr>
<tr><td>description</td><td>Select how contact about the case was originated, such as email, phone, or web, for use in reporting and analysis.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>caseorigincode</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[
  {
    "languageTag": "en",
    "displayText": "Phone",
    "attributeValue": "1",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Email",
    "attributeValue": "2",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Web",
    "attributeValue": "3",
    "displayOrder": "2"
  },
  {
    "languageTag": "en",
    "displayText": "Facebook",
    "attributeValue": "2483",
    "displayOrder": "3"
  },
  {
    "languageTag": "en",
    "displayText": "Twitter",
    "attributeValue": "3986",
    "displayOrder": "4"
  }
]</pre></td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the caseOriginCode attribute are listed below.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr>
<tr><td>en</td><td>Phone</td><td>1</td><td>0</td></tr>
<tr><td>en</td><td>Email</td><td>2</td><td>1</td></tr>
<tr><td>en</td><td>Web</td><td>3</td><td>2</td></tr>
<tr><td>en</td><td>Facebook</td><td>2483</td><td>3</td></tr>
<tr><td>en</td><td>Twitter</td><td>3986</td><td>4</td></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Origin</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Select how contact about the case was originated, such as email, phone, or web, for use in reporting and analysis.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>caseorigincode</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10039</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="caseOriginCode_display">caseOriginCode_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the caseOriginCode_display attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>caseOriginCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>

### <a name="caseTypeCode">caseTypeCode</a>

Select the type of case to identify the incident for use in case routing and analysis.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Case Type</td></tr>
<tr><td>description</td><td>Select the type of case to identify the incident for use in case routing and analysis.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>casetypecode</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[
  {
    "languageTag": "en",
    "displayText": "Question",
    "attributeValue": "1",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Problem",
    "attributeValue": "2",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Request",
    "attributeValue": "3",
    "displayOrder": "2"
  }
]</pre></td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the caseTypeCode attribute are listed below.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr>
<tr><td>en</td><td>Question</td><td>1</td><td>0</td></tr>
<tr><td>en</td><td>Problem</td><td>2</td><td>1</td></tr>
<tr><td>en</td><td>Request</td><td>3</td><td>2</td></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Case Type</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Select the type of case to identify the incident for use in case routing and analysis.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>casetypecode</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10041</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="caseTypeCode_display">caseTypeCode_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the caseTypeCode_display attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>caseTypeCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>

### <a name="checkEmail">checkEmail</a>

This attribute is used for Sample Service Business Processes.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Check Email</td></tr>
<tr><td>description</td><td>This attribute is used for Sample Service Business Processes.</td></tr>
<tr><td>dataFormat</td><td>Boolean</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>checkemail</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the checkEmail attribute are listed below.</summary>

##### is.dataFormat.boolean

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Check Email</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>This attribute is used for Sample Service Business Processes.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>checkemail</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10043</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="contractDetailId">contractDetailId</a>

Choose the contract line that the case should be logged under to make sure the customer is charged correctly.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Contract Line</td></tr>
<tr><td>description</td><td>Choose the contract line that the case should be logged under to make sure the customer is charged correctly.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>contractdetailid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the contractDetailId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Contract Line</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Choose the contract line that the case should be logged under to make sure the customer is charged correctly.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>contractdetailid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10045</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "contractDetailId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Contract Line"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Choose the contract line that the case should be logged under to make sure the customer is charged correctly."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Contract Line",
  "description": "Choose the contract line that the case should be logged under to make sure the customer is charged correctly.",
  "isNullable": true,
  "sourceName": "contractdetailid",
  "sourceOrdering": 10045
}
```

</details>

### <a name="contractId">contractId</a>

Choose the service contract that the case should be logged under to make sure the customer is eligible for support services.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Contract</td></tr>
<tr><td>description</td><td>Choose the service contract that the case should be logged under to make sure the customer is eligible for support services.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>contractid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the contractId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Contract</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Choose the service contract that the case should be logged under to make sure the customer is eligible for support services.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>contractid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10046</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "contractId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Contract"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Choose the service contract that the case should be logged under to make sure the customer is eligible for support services."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Contract",
  "description": "Choose the service contract that the case should be logged under to make sure the customer is eligible for support services.",
  "isNullable": true,
  "sourceName": "contractid",
  "sourceOrdering": 10046
}
```

</details>

### <a name="contractServiceLevelCode">contractServiceLevelCode</a>

Select the service level for the case to make sure the case is handled correctly.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Service Level</td></tr>
<tr><td>description</td><td>Select the service level for the case to make sure the case is handled correctly.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>contractservicelevelcode</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[
  {
    "languageTag": "en",
    "displayText": "Gold",
    "attributeValue": "1",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Silver",
    "attributeValue": "2",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Bronze",
    "attributeValue": "3",
    "displayOrder": "2"
  }
]</pre></td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the contractServiceLevelCode attribute are listed below.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr>
<tr><td>en</td><td>Gold</td><td>1</td><td>0</td></tr>
<tr><td>en</td><td>Silver</td><td>2</td><td>1</td></tr>
<tr><td>en</td><td>Bronze</td><td>3</td><td>2</td></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Service Level</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Select the service level for the case to make sure the case is handled correctly.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>contractservicelevelcode</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10047</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="contractServiceLevelCode_display">contractServiceLevelCode_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the contractServiceLevelCode_display attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>contractServiceLevelCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>

### <a name="customerIdType">customerIdType</a>

The type of customer, either Account or Contact.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Customer Type</td></tr>
<tr><td>description</td><td>The type of customer, either Account or Contact.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
<tr><td>sourceName</td><td>customeridtype</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the customerIdType attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.entityName

##### is.readOnly

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Customer Type</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The type of customer, either Account or Contact.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>customeridtype</td><td>string</td><td></td></tr>
</table>

##### is.linkedEntity.name

Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.

##### is.CDS.customer

contains an Account or Contact ID

</details>

### <a name="customerId">customerId</a>

The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Customer</td></tr>
<tr><td>description</td><td>The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>customerid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the customerId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Customer</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>The customer account or contact to provide a quick link to additional customer details, such as account information, activities, and opportunities.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>customerid</td><td>string</td><td></td></tr>
</table>

##### is.linkedEntity.identifier

Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.

##### is.CDS.customer

contains an Account or Contact ID

</details>

### <a name="customerSatisfactionCode">customerSatisfactionCode</a>

Select the customer's level of satisfaction with the handling and resolution of the case.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Satisfaction</td></tr>
<tr><td>description</td><td>Select the customer's level of satisfaction with the handling and resolution of the case.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>customersatisfactioncode</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[
  {
    "languageTag": "en",
    "displayText": "Very Satisfied",
    "attributeValue": "5",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Satisfied",
    "attributeValue": "4",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Neutral",
    "attributeValue": "3",
    "displayOrder": "2"
  },
  {
    "languageTag": "en",
    "displayText": "Dissatisfied",
    "attributeValue": "2",
    "displayOrder": "3"
  },
  {
    "languageTag": "en",
    "displayText": "Very Dissatisfied",
    "attributeValue": "1",
    "displayOrder": "4"
  }
]</pre></td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the customerSatisfactionCode attribute are listed below.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr>
<tr><td>en</td><td>Very Satisfied</td><td>5</td><td>0</td></tr>
<tr><td>en</td><td>Satisfied</td><td>4</td><td>1</td></tr>
<tr><td>en</td><td>Neutral</td><td>3</td><td>2</td></tr>
<tr><td>en</td><td>Dissatisfied</td><td>2</td><td>3</td></tr>
<tr><td>en</td><td>Very Dissatisfied</td><td>1</td><td>4</td></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Satisfaction</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Select the customer's level of satisfaction with the handling and resolution of the case.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>customersatisfactioncode</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10050</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="customerSatisfactionCode_display">customerSatisfactionCode_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the customerSatisfactionCode_display attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>customerSatisfactionCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>

### <a name="description">description</a>

Type additional information to describe the case to assist the service team in reaching a resolution.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Description</td></tr>
<tr><td>description</td><td>Type additional information to describe the case to assist the service team in reaching a resolution.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>2000</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>description</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the description attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Description</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type additional information to describe the case to assist the service team in reaching a resolution.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>description</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10052</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>2000</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="entitlementId">entitlementId</a>

Choose the entitlement that is applicable for the case.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Entitlement</td></tr>
<tr><td>description</td><td>Choose the entitlement that is applicable for the case.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>entitlementid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the entitlementId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Entitlement</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Choose the entitlement that is applicable for the case.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>entitlementid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10053</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "entitlementId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Entitlement"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Choose the entitlement that is applicable for the case."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Entitlement",
  "description": "Choose the entitlement that is applicable for the case.",
  "isNullable": true,
  "sourceName": "entitlementid",
  "sourceOrdering": 10053
}
```

</details>

### <a name="SLAId">SLAId</a>

Choose the service level agreement (SLA) that you want to apply to the case record.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>SLA</td></tr>
<tr><td>description</td><td>Choose the service level agreement (SLA) that you want to apply to the case record.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>slaid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the SLAId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>SLA</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Choose the service level agreement (SLA) that you want to apply to the case record.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>slaid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10054</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "SLAId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "SLA"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Choose the service level agreement (SLA) that you want to apply to the case record."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "SLA",
  "description": "Choose the service level agreement (SLA) that you want to apply to the case record.",
  "isNullable": true,
  "sourceName": "slaid",
  "sourceOrdering": 10054
}
```

</details>

### <a name="firstResponseSLAStatus">firstResponseSLAStatus</a>

Shows the status of the initial response time for the case according to the terms of the SLA.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>First Response SLA Status</td></tr>
<tr><td>description</td><td>Shows the status of the initial response time for the case according to the terms of the SLA.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>firstresponseslastatus</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[
  {
    "languageTag": "en",
    "displayText": "In Progress",
    "attributeValue": "1",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Nearing Noncompliance",
    "attributeValue": "2",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Succeeded",
    "attributeValue": "3",
    "displayOrder": "2"
  },
  {
    "languageTag": "en",
    "displayText": "Noncompliant",
    "attributeValue": "4",
    "displayOrder": "3"
  }
]</pre></td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the firstResponseSLAStatus attribute are listed below.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr>
<tr><td>en</td><td>In Progress</td><td>1</td><td>0</td></tr>
<tr><td>en</td><td>Nearing Noncompliance</td><td>2</td><td>1</td></tr>
<tr><td>en</td><td>Succeeded</td><td>3</td><td>2</td></tr>
<tr><td>en</td><td>Noncompliant</td><td>4</td><td>3</td></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>First Response SLA Status</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows the status of the initial response time for the case according to the terms of the SLA.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>firstresponseslastatus</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10055</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="firstResponseSLAStatus_display">firstResponseSLAStatus_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the firstResponseSLAStatus_display attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>firstResponseSLAStatus</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>

### <a name="followupBy">followupBy</a>

Enter the date by which a customer service representative has to follow up with the customer on this case.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Follow Up By</td></tr>
<tr><td>description</td><td>Enter the date by which a customer service representative has to follow up with the customer on this case.</td></tr>
<tr><td>dataFormat</td><td>DateTimeOffset</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>followupby</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the followupBy attribute are listed below.</summary>

##### is.dataFormat.date

##### means.measurement.date

##### is.dataFormat.time

##### means.measurement.time

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Follow Up By</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Enter the date by which a customer service representative has to follow up with the customer on this case.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>followupby</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10057</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="followUpTaskCreated">followUpTaskCreated</a>

This attribute is used for Sample Service Business Processes.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Follow up Task Created</td></tr>
<tr><td>description</td><td>This attribute is used for Sample Service Business Processes.</td></tr>
<tr><td>dataFormat</td><td>Boolean</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>followuptaskcreated</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the followUpTaskCreated attribute are listed below.</summary>

##### is.dataFormat.boolean

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Follow up Task Created</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>This attribute is used for Sample Service Business Processes.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>followuptaskcreated</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10058</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="incidentStageCode">incidentStageCode</a>

Select the current stage of the service process for the case to assist service team members when they review or transfer a case.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Case Stage</td></tr>
<tr><td>description</td><td>Select the current stage of the service process for the case to assist service team members when they review or transfer a case.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>incidentstagecode</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[
  {
    "languageTag": "en",
    "displayText": "Default Value",
    "attributeValue": "1",
    "displayOrder": "0"
  }
]</pre></td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the incidentStageCode attribute are listed below.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr>
<tr><td>en</td><td>Default Value</td><td>1</td><td>0</td></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Case Stage</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Select the current stage of the service process for the case to assist service team members when they review or transfer a case.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>incidentstagecode</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10060</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="incidentStageCode_display">incidentStageCode_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the incidentStageCode_display attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>incidentStageCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>

### <a name="isDecrementing">isDecrementing</a>

For system use only.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Decrementing</td></tr>
<tr><td>description</td><td>For system use only.</td></tr>
<tr><td>dataFormat</td><td>Boolean</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>isdecrementing</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the isDecrementing attribute are listed below.</summary>

##### is.dataFormat.boolean

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Decrementing</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>For system use only.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>isdecrementing</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10062</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="kbArticleId">kbArticleId</a>

Choose the article that contains additional information or a resolution for the case, for reference during research or follow up with the customer.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Knowledge Base Article</td></tr>
<tr><td>description</td><td>Choose the article that contains additional information or a resolution for the case, for reference during research or follow up with the customer.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>kbarticleid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the kbArticleId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Knowledge Base Article</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Choose the article that contains additional information or a resolution for the case, for reference during research or follow up with the customer.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>kbarticleid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10064</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "kbArticleId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Knowledge Base Article"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Choose the article that contains additional information or a resolution for the case, for reference during research or follow up with the customer."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Knowledge Base Article",
  "description": "Choose the article that contains additional information or a resolution for the case, for reference during research or follow up with the customer.",
  "isNullable": true,
  "sourceName": "kbarticleid",
  "sourceOrdering": 10064
}
```

</details>

### <a name="messageTypeCode">messageTypeCode</a>

Shows whether the post originated as a public or private message.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Received As</td></tr>
<tr><td>description</td><td>Shows whether the post originated as a public or private message.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>messagetypecode</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[]</pre></td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the messageTypeCode attribute are listed below.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Received As</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows whether the post originated as a public or private message.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>messagetypecode</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10065</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="messageTypeCode_display">messageTypeCode_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the messageTypeCode_display attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>messageTypeCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>

### <a name="priorityCode">priorityCode</a>

Select the priority so that preferred customers or critical issues are handled quickly.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Priority</td></tr>
<tr><td>description</td><td>Select the priority so that preferred customers or critical issues are handled quickly.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>prioritycode</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[
  {
    "languageTag": "en",
    "displayText": "High",
    "attributeValue": "1",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Normal",
    "attributeValue": "2",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Low",
    "attributeValue": "3",
    "displayOrder": "2"
  }
]</pre></td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the priorityCode attribute are listed below.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr>
<tr><td>en</td><td>High</td><td>1</td><td>0</td></tr>
<tr><td>en</td><td>Normal</td><td>2</td><td>1</td></tr>
<tr><td>en</td><td>Low</td><td>3</td><td>2</td></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Priority</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Select the priority so that preferred customers or critical issues are handled quickly.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>prioritycode</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10067</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="priorityCode_display">priorityCode_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the priorityCode_display attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>priorityCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>

### <a name="productId">productId</a>

Choose the product associated with the case to identify warranty, service, or other product issues and be able to report the number of incidents for each product.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Product</td></tr>
<tr><td>description</td><td>Choose the product associated with the case to identify warranty, service, or other product issues and be able to report the number of incidents for each product.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>productid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the productId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Product</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Choose the product associated with the case to identify warranty, service, or other product issues and be able to report the number of incidents for each product.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>productid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10069</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "productId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Product"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Choose the product associated with the case to identify warranty, service, or other product issues and be able to report the number of incidents for each product."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Product",
  "description": "Choose the product associated with the case to identify warranty, service, or other product issues and be able to report the number of incidents for each product.",
  "isNullable": true,
  "sourceName": "productid",
  "sourceOrdering": 10069
}
```

</details>

### <a name="productSerialNumber">productSerialNumber</a>

Type the serial number of the product that is associated with this case, so that the number of cases per product can be reported.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Serial Number</td></tr>
<tr><td>description</td><td>Type the serial number of the product that is associated with this case, so that the number of cases per product can be reported.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>100</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>productserialnumber</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the productSerialNumber attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Serial Number</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Type the serial number of the product that is associated with this case, so that the number of cases per product can be reported.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>productserialnumber</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10070</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>100</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="existingCase">existingCase</a>

Select an existing case for the customer that has been populated. For internal use only.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Existing Case</td></tr>
<tr><td>description</td><td>Select an existing case for the customer that has been populated. For internal use only.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>existingcase</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the existingCase attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Existing Case</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Select an existing case for the customer that has been populated. For internal use only.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>existingcase</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10071</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "existingCase",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Existing Case"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Select an existing case for the customer that has been populated. For internal use only."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Existing Case",
  "description": "Select an existing case for the customer that has been populated. For internal use only.",
  "isNullable": true,
  "sourceName": "existingcase",
  "sourceOrdering": 10071
}
```

</details>

### <a name="resolveBySLAStatus">resolveBySLAStatus</a>

Shows the status of the resolution time for the case according to the terms of the SLA.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Resolve By SLA Status</td></tr>
<tr><td>description</td><td>Shows the status of the resolution time for the case according to the terms of the SLA.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>resolvebyslastatus</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[
  {
    "languageTag": "en",
    "displayText": "In Progress",
    "attributeValue": "1",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Nearing Noncompliance",
    "attributeValue": "2",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Succeeded",
    "attributeValue": "3",
    "displayOrder": "2"
  },
  {
    "languageTag": "en",
    "displayText": "Noncompliant",
    "attributeValue": "4",
    "displayOrder": "3"
  }
]</pre></td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the resolveBySLAStatus attribute are listed below.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr>
<tr><td>en</td><td>In Progress</td><td>1</td><td>0</td></tr>
<tr><td>en</td><td>Nearing Noncompliance</td><td>2</td><td>1</td></tr>
<tr><td>en</td><td>Succeeded</td><td>3</td><td>2</td></tr>
<tr><td>en</td><td>Noncompliant</td><td>4</td><td>3</td></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Resolve By SLA Status</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows the status of the resolution time for the case according to the terms of the SLA.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>resolvebyslastatus</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10072</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="resolveBySLAStatus_display">resolveBySLAStatus_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the resolveBySLAStatus_display attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>resolveBySLAStatus</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>

### <a name="responsibleContactId">responsibleContactId</a>

Choose an additional customer contact who can also help resolve the case.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Responsible Contact</td></tr>
<tr><td>description</td><td>Choose an additional customer contact who can also help resolve the case.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>responsiblecontactid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the responsibleContactId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Responsible Contact</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Choose an additional customer contact who can also help resolve the case.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>responsiblecontactid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10074</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "responsibleContactId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Responsible Contact"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Choose an additional customer contact who can also help resolve the case."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Responsible Contact",
  "description": "Choose an additional customer contact who can also help resolve the case.",
  "isNullable": true,
  "sourceName": "responsiblecontactid",
  "sourceOrdering": 10074
}
```

</details>

### <a name="sentimentValue">sentimentValue</a>

Value derived after assessing words commonly associated with a negative, neutral, or positive sentiment that occurs in a social post. Sentiment information can also be reported as numeric values.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Sentiment Value</td></tr>
<tr><td>description</td><td>Value derived after assessing words commonly associated with a negative, neutral, or positive sentiment that occurs in a social post. Sentiment information can also be reported as numeric values.</td></tr>
<tr><td>dataFormat</td><td>Double</td></tr>
<tr><td>maximumValue</td><td>100000000000</td></tr>
<tr><td>minimumValue</td><td>-100000000000</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>sentimentvalue</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the sentimentValue attribute are listed below.</summary>

##### is.dataFormat.floatingPoint

##### is.dataFormat.big

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Sentiment Value</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Value derived after assessing words commonly associated with a negative, neutral, or positive sentiment that occurs in a social post. Sentiment information can also be reported as numeric values.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>sentimentvalue</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10075</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-100000000000</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>100000000000</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="influenceScore">influenceScore</a>

Will contain the Influencer score coming from NetBreeze.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Influence Score</td></tr>
<tr><td>description</td><td>Will contain the Influencer score coming from NetBreeze.</td></tr>
<tr><td>dataFormat</td><td>Double</td></tr>
<tr><td>maximumValue</td><td>1000000000</td></tr>
<tr><td>minimumValue</td><td>0</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>influencescore</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the influenceScore attribute are listed below.</summary>

##### is.dataFormat.floatingPoint

##### is.dataFormat.big

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Influence Score</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Will contain the Influencer score coming from NetBreeze.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>influencescore</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10076</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>0</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>1000000000</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="serviceStage">serviceStage</a>

Select the stage, in the case resolution process, that the case is in.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Service Stage</td></tr>
<tr><td>description</td><td>Select the stage, in the case resolution process, that the case is in.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>servicestage</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[
  {
    "languageTag": "en",
    "displayText": "Identify",
    "attributeValue": "0",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Research",
    "attributeValue": "1",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Resolve",
    "attributeValue": "2",
    "displayOrder": "2"
  }
]</pre></td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the serviceStage attribute are listed below.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr>
<tr><td>en</td><td>Identify</td><td>0</td><td>0</td></tr>
<tr><td>en</td><td>Research</td><td>1</td><td>1</td></tr>
<tr><td>en</td><td>Resolve</td><td>2</td><td>2</td></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Service Stage</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Select the stage, in the case resolution process, that the case is in.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>servicestage</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10077</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="serviceStage_display">serviceStage_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the serviceStage_display attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>serviceStage</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>

### <a name="severityCode">severityCode</a>

Select the severity of this case to indicate the incident's impact on the customer's business.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Severity</td></tr>
<tr><td>description</td><td>Select the severity of this case to indicate the incident's impact on the customer's business.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>severitycode</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[
  {
    "languageTag": "en",
    "displayText": "Default Value",
    "attributeValue": "1",
    "displayOrder": "0"
  }
]</pre></td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the severityCode attribute are listed below.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr>
<tr><td>en</td><td>Default Value</td><td>1</td><td>0</td></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Severity</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Select the severity of this case to indicate the incident's impact on the customer's business.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>severitycode</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10079</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="severityCode_display">severityCode_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the severityCode_display attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>severityCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>

### <a name="SLAInvokedId">SLAInvokedId</a>

Last SLA that was applied to this case. This field is for internal use only.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Last SLA applied</td></tr>
<tr><td>description</td><td>Last SLA that was applied to this case. This field is for internal use only.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>slainvokedid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the SLAInvokedId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Last SLA applied</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Last SLA that was applied to this case. This field is for internal use only.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>slainvokedid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10081</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "SLAInvokedId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Last SLA applied"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Last SLA that was applied to this case. This field is for internal use only."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Last SLA applied",
  "description": "Last SLA that was applied to this case. This field is for internal use only.",
  "isNullable": true,
  "sourceName": "slainvokedid",
  "sourceOrdering": 10081
}
```

</details>

### <a name="socialProfileId">socialProfileId</a>

Unique identifier of the social profile with which the case is associated.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Social Profile</td></tr>
<tr><td>description</td><td>Unique identifier of the social profile with which the case is associated.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>socialprofileid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the socialProfileId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Social Profile</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the social profile with which the case is associated.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>socialprofileid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10082</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "socialProfileId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Social Profile"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Unique identifier of the social profile with which the case is associated."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Social Profile",
  "description": "Unique identifier of the social profile with which the case is associated.",
  "isNullable": true,
  "sourceName": "socialprofileid",
  "sourceOrdering": 10082
}
```

</details>

### <a name="stateCode">stateCode</a>

Shows whether the case is active, resolved, or canceled. Resolved and canceled cases are read-only and can't be edited unless they are reactivated.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Status</td></tr>
<tr><td>description</td><td>Shows whether the case is active, resolved, or canceled. Resolved and canceled cases are read-only and can't be edited unless they are reactivated.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>sourceName</td><td>statecode</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[
  {
    "languageTag": "en",
    "displayText": "Active",
    "attributeValue": "0",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Resolved",
    "attributeValue": "1",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Canceled",
    "attributeValue": "2",
    "displayOrder": "2"
  }
]</pre></td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the stateCode attribute are listed below.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr>
<tr><td>en</td><td>Active</td><td>0</td><td>0</td></tr>
<tr><td>en</td><td>Resolved</td><td>1</td><td>1</td></tr>
<tr><td>en</td><td>Canceled</td><td>2</td><td>2</td></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### means.entityState

the attribute represents the current state of the entity.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>attribute</td><td>"Case_/hasAttributes/stateCode"</td><td>attribute</td><td></td></tr>
</table>

Definition:

```
"Case_/hasAttributes/stateCode"
```

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Status</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows whether the case is active, resolved, or canceled. Resolved and canceled cases are read-only and can't be edited unless they are reactivated.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>statecode</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10083</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="stateCode_display">stateCode_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the stateCode_display attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>stateCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>

### <a name="statusCode">statusCode</a>

Select the case's status.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Status Reason</td></tr>
<tr><td>description</td><td>Select the case's status.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>statuscode</td></tr>
<tr><td>valueConstrainedToList</td><td>true</td></tr>
<tr><td>defaultValue</td><td><pre>[
  {
    "languageTag": "en",
    "displayText": "Problem Solved",
    "attributeValue": "5",
    "displayOrder": "0",
    "correlatedValue": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Information Provided",
    "attributeValue": "1000",
    "displayOrder": "1",
    "correlatedValue": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Canceled",
    "attributeValue": "6",
    "displayOrder": "2",
    "correlatedValue": "2"
  },
  {
    "languageTag": "en",
    "displayText": "Merged",
    "attributeValue": "2000",
    "displayOrder": "3",
    "correlatedValue": "2"
  },
  {
    "languageTag": "en",
    "displayText": "In Progress",
    "attributeValue": "1",
    "displayOrder": "4",
    "correlatedValue": "0"
  },
  {
    "languageTag": "en",
    "displayText": "On Hold",
    "attributeValue": "2",
    "displayOrder": "5",
    "correlatedValue": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Waiting for Details",
    "attributeValue": "3",
    "displayOrder": "6",
    "correlatedValue": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Researching",
    "attributeValue": "4",
    "displayOrder": "7",
    "correlatedValue": "0"
  }
]</pre></td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the statusCode attribute are listed below.</summary>

##### is.dataFormat.integer

##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>default</td><td><table><tr><th>correlatedValue</th></tr>
<tr><td>en</td><td>Problem Solved</td><td>5</td><td>0</td><td>1</td></tr>
<tr><td>en</td><td>Information Provided</td><td>1000</td><td>1</td><td>1</td></tr>
<tr><td>en</td><td>Canceled</td><td>6</td><td>2</td><td>2</td></tr>
<tr><td>en</td><td>Merged</td><td>2000</td><td>3</td><td>2</td></tr>
<tr><td>en</td><td>In Progress</td><td>1</td><td>4</td><td>0</td></tr>
<tr><td>en</td><td>On Hold</td><td>2</td><td>5</td><td>0</td></tr>
<tr><td>en</td><td>Waiting for Details</td><td>3</td><td>6</td><td>0</td></tr>
<tr><td>en</td><td>Researching</td><td>4</td><td>7</td><td>0</td></tr>
</table>

</td><td>any</td><td></td></tr>
</table>

##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities

##### is.correlatedWith

the attribute value is correlated with the sourceAttribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>sourceAttribute</td><td>stateCode</td><td>attributeName</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Status Reason</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Select the case's status.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>statuscode</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10085</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="statusCode_display">statusCode_display</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>isReadOnly</td><td>true</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the statusCode_display attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.reference.displayText

##### is.readOnly

##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>inSupportOf</td><td>statusCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr>
</table>

</details>

### <a name="subjectId">subjectId</a>

Choose the subject for the case, such as catalog request or product complaint, so customer service managers can identify frequent requests or problem areas. Administrators can configure subjects under Business Management in the Settings area.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Subject</td></tr>
<tr><td>description</td><td>Choose the subject for the case, such as catalog request or product complaint, so customer service managers can identify frequent requests or problem areas. Administrators can configure subjects under Business Management in the Settings area.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>subjectid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the subjectId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>subject</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Subject</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Choose the subject for the case, such as catalog request or product complaint, so customer service managers can identify frequent requests or problem areas. Administrators can configure subjects under Business Management in the Settings area.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>subjectid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10087</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="ticketNumber">ticketNumber</a>

Shows the case number for customer reference and searching capabilities. This cannot be modified.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Case Number</td></tr>
<tr><td>description</td><td>Shows the case number for customer reference and searching capabilities. This cannot be modified.</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>100</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>ticketnumber</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the ticketNumber attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Case Number</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows the case number for customer reference and searching capabilities. This cannot be modified.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>ticketnumber</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10088</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>100</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="masterId">masterId</a>

Choose the primary case the current case was merged into.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Master Case</td></tr>
<tr><td>description</td><td>Choose the primary case the current case was merged into.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>masterid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the masterId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Master Case</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Choose the primary case the current case was merged into.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>masterid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10089</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "masterId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Master Case"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Choose the primary case the current case was merged into."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Master Case",
  "description": "Choose the primary case the current case was merged into.",
  "isNullable": true,
  "sourceName": "masterid",
  "sourceOrdering": 10089
}
```

</details>

### <a name="parentCaseId">parentCaseId</a>

Choose the parent case for a case.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Parent Case</td></tr>
<tr><td>description</td><td>Choose the parent case for a case.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>parentcaseid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the parentCaseId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Parent Case</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Choose the parent case for a case.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>parentcaseid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10090</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "parentCaseId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Parent Case"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Choose the parent case for a case."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Parent Case",
  "description": "Choose the parent case for a case.",
  "isNullable": true,
  "sourceName": "parentcaseid",
  "sourceOrdering": 10090
}
```

</details>

### <a name="numberOfChildIncidents">numberOfChildIncidents</a>

Number of child incidents associated with the incident.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Child Cases</td></tr>
<tr><td>description</td><td>Number of child incidents associated with the incident.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>maximumValue</td><td>2147483647</td></tr>
<tr><td>minimumValue</td><td>0</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>numberofchildincidents</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the numberOfChildIncidents attribute are listed below.</summary>

##### is.dataFormat.integer

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Child Cases</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Number of child incidents associated with the incident.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>numberofchildincidents</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10091</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>0</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="merged">merged</a>

Tells whether the incident has been merged with another incident.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Internal Use Only</td></tr>
<tr><td>description</td><td>Tells whether the incident has been merged with another incident.</td></tr>
<tr><td>dataFormat</td><td>Boolean</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>merged</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the merged attribute are listed below.</summary>

##### is.dataFormat.boolean

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Internal Use Only</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Tells whether the incident has been merged with another incident.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>merged</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10092</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="routeCase">routeCase</a>

Tells whether the incident has been routed to queue or not.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Route Case</td></tr>
<tr><td>description</td><td>Tells whether the incident has been routed to queue or not.</td></tr>
<tr><td>dataFormat</td><td>Boolean</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>routecase</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the routeCase attribute are listed below.</summary>

##### is.dataFormat.boolean

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Route Case</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Tells whether the incident has been routed to queue or not.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>routecase</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10094</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="resolveBy">resolveBy</a>

Enter the date by when the case must be resolved.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Resolve By</td></tr>
<tr><td>description</td><td>Enter the date by when the case must be resolved.</td></tr>
<tr><td>dataFormat</td><td>DateTimeOffset</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>resolveby</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the resolveBy attribute are listed below.</summary>

##### is.dataFormat.date

##### means.measurement.date

##### is.dataFormat.time

##### means.measurement.time

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Resolve By</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Enter the date by when the case must be resolved.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>resolveby</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10096</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="responseBy">responseBy</a>

For internal use only.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>First Response By</td></tr>
<tr><td>description</td><td>For internal use only.</td></tr>
<tr><td>dataFormat</td><td>DateTimeOffset</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>responseby</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the responseBy attribute are listed below.</summary>

##### is.dataFormat.date

##### means.measurement.date

##### is.dataFormat.time

##### means.measurement.time

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>First Response By</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>For internal use only.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>responseby</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10097</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="customerContacted">customerContacted</a>

Tells whether customer service representative has contacted the customer or not.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Customer Contacted</td></tr>
<tr><td>description</td><td>Tells whether customer service representative has contacted the customer or not.</td></tr>
<tr><td>dataFormat</td><td>Boolean</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>customercontacted</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the customerContacted attribute are listed below.</summary>

##### is.dataFormat.boolean

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Customer Contacted</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Tells whether customer service representative has contacted the customer or not.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>customercontacted</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10098</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="firstResponseSent">firstResponseSent</a>

Indicates if the first response has been sent.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>First Response Sent</td></tr>
<tr><td>description</td><td>Indicates if the first response has been sent.</td></tr>
<tr><td>dataFormat</td><td>Boolean</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>firstresponsesent</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the firstResponseSent attribute are listed below.</summary>

##### is.dataFormat.boolean

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>First Response Sent</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Indicates if the first response has been sent.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>firstresponsesent</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10100</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="isEscalated">isEscalated</a>

Indicates if the case has been escalated.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Is Escalated</td></tr>
<tr><td>description</td><td>Indicates if the case has been escalated.</td></tr>
<tr><td>dataFormat</td><td>Boolean</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>isescalated</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the isEscalated attribute are listed below.</summary>

##### is.dataFormat.boolean

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Is Escalated</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Indicates if the case has been escalated.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>isescalated</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10102</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="escalatedOn">escalatedOn</a>

Indicates the date and time when the case was escalated.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Escalated On</td></tr>
<tr><td>description</td><td>Indicates the date and time when the case was escalated.</td></tr>
<tr><td>dataFormat</td><td>DateTimeOffset</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>escalatedon</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the escalatedOn attribute are listed below.</summary>

##### is.dataFormat.date

##### means.measurement.date

##### is.dataFormat.time

##### means.measurement.time

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Escalated On</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Indicates the date and time when the case was escalated.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>escalatedon</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10104</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="primaryContactId">primaryContactId</a>

Select a primary contact for this case.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Contact</td></tr>
<tr><td>description</td><td>Select a primary contact for this case.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>primarycontactid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the primaryContactId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Contact</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Select a primary contact for this case.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>primarycontactid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10105</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "primaryContactId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Contact"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Select a primary contact for this case."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Contact",
  "description": "Select a primary contact for this case.",
  "isNullable": true,
  "sourceName": "primarycontactid",
  "sourceOrdering": 10105
}
```

</details>

### <a name="onHoldTime">onHoldTime</a>

Shows the duration in minutes for which the case was on hold.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>On Hold Time (Minutes)</td></tr>
<tr><td>description</td><td>Shows the duration in minutes for which the case was on hold.</td></tr>
<tr><td>dataFormat</td><td>Int32</td></tr>
<tr><td>maximumValue</td><td>2147483647</td></tr>
<tr><td>minimumValue</td><td>-2147483648</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>onholdtime</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the onHoldTime attribute are listed below.</summary>

##### is.dataFormat.integer

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>On Hold Time (Minutes)</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows the duration in minutes for which the case was on hold.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>onholdtime</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10106</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>-2147483648</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="lastOnHoldTime">lastOnHoldTime</a>

Contains the date time stamp of the last on hold time.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Last On Hold Time</td></tr>
<tr><td>description</td><td>Contains the date time stamp of the last on hold time.</td></tr>
<tr><td>dataFormat</td><td>DateTimeOffset</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>lastonholdtime</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the lastOnHoldTime attribute are listed below.</summary>

##### is.dataFormat.date

##### means.measurement.date

##### is.dataFormat.time

##### means.measurement.time

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Last On Hold Time</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Contains the date time stamp of the last on hold time.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>lastonholdtime</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10107</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="resolveByKPIId">resolveByKPIId</a>

For internal use only.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Resolve By KPI</td></tr>
<tr><td>description</td><td>For internal use only.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>resolvebykpiid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the resolveByKPIId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Resolve By KPI</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>For internal use only.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>resolvebykpiid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10108</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "resolveByKPIId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Resolve By KPI"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "For internal use only."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Resolve By KPI",
  "description": "For internal use only.",
  "isNullable": true,
  "sourceName": "resolvebykpiid",
  "sourceOrdering": 10108
}
```

</details>

### <a name="firstResponseByKPIId">firstResponseByKPIId</a>

For internal use only.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>First Response By KPI</td></tr>
<tr><td>description</td><td>For internal use only.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>firstresponsebykpiid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the firstResponseByKPIId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>First Response By KPI</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>For internal use only.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>firstresponsebykpiid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10109</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "firstResponseByKPIId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "First Response By KPI"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "For internal use only."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "First Response By KPI",
  "description": "For internal use only.",
  "isNullable": true,
  "sourceName": "firstresponsebykpiid",
  "sourceOrdering": 10109
}
```

</details>

### <a name="decrementEntitlementTerm">decrementEntitlementTerm</a>

Shows whether terms of the associated entitlement should be decremented or not.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Decrement Entitlement Terms</td></tr>
<tr><td>description</td><td>Shows whether terms of the associated entitlement should be decremented or not.</td></tr>
<tr><td>dataFormat</td><td>Boolean</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>decremententitlementterm</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the decrementEntitlementTerm attribute are listed below.</summary>

##### is.dataFormat.boolean

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Decrement Entitlement Terms</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows whether terms of the associated entitlement should be decremented or not.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>decremententitlementterm</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10110</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="entityImageId">entityImageId</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>entityimageid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the entityImageId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>entityimageid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10112</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="accountId">accountId</a>

Unique identifier of the account with which the case is associated.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Account</td></tr>
<tr><td>description</td><td>Unique identifier of the account with which the case is associated.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>accountid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the accountId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Account</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the account with which the case is associated.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>accountid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10116</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="contactId">contactId</a>

Unique identifier of the contact associated with the case.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Contact</td></tr>
<tr><td>description</td><td>Unique identifier of the contact associated with the case.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>contactid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the contactId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Contact</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Unique identifier of the contact associated with the case.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>contactid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10119</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="exchangeRate">exchangeRate</a>

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Exchange Rate</td></tr>
<tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr>
<tr><td>dataFormat</td><td>Decimal</td></tr>
<tr><td>maximumValue</td><td>100000000000</td></tr>
<tr><td>minimumValue</td><td>1E-10</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>exchangerate</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the exchangeRate attribute are listed below.</summary>

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Exchange Rate</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>exchangerate</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10125</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>minimumValue</td><td>1E-10</td><td>decimal</td><td></td></tr>
<tr><td>maximumValue</td><td>100000000000</td><td>decimal</td><td></td></tr>
</table>

</details>

### <a name="transactionCurrencyId">transactionCurrencyId</a>

Choose the local currency for the record to make sure budgets are reported in the correct currency.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Currency</td></tr>
<tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>transactioncurrencyid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the transactionCurrencyId attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Currency</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>transactioncurrencyid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10126</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "transactionCurrencyId",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Currency"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Choose the local currency for the record to make sure budgets are reported in the correct currency."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Currency",
  "description": "Choose the local currency for the record to make sure budgets are reported in the correct currency.",
  "isNullable": true,
  "sourceName": "transactioncurrencyid",
  "sourceOrdering": 10126
}
```

</details>

### <a name="createdByExternalParty">createdByExternalParty</a>

Shows the external party who created the record.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Created By (External Party)</td></tr>
<tr><td>description</td><td>Shows the external party who created the record.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>createdbyexternalparty</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the createdByExternalParty attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Created By (External Party)</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows the external party who created the record.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>createdbyexternalparty</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10129</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="modifiedByExternalParty">modifiedByExternalParty</a>

Shows the external party who modified the record.

First included in: /core/applicationCommon/foundationCommon/crmCommon/service/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Modified By (External Party)</td></tr>
<tr><td>description</td><td>Shows the external party who modified the record.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>modifiedbyexternalparty</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the modifiedByExternalParty attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Modified By (External Party)</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Shows the external party who modified the record.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>modifiedbyexternalparty</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10132</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="adxCreatedByIPAddress">adxCreatedByIPAddress</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Created By IP Address</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>100</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>adx_createdbyipaddress</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the adxCreatedByIPAddress attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Created By IP Address</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>adx_createdbyipaddress</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10151</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>100</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="adxCreatedByUsername">adxCreatedByUsername</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Created By Username</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>100</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>adx_createdbyusername</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the adxCreatedByUsername attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.identity.name

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Created By Username</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>adx_createdbyusername</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10152</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>100</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="adxModifiedByIPAddress">adxModifiedByIPAddress</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Modified By IP Address</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>100</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>adx_modifiedbyipaddress</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the adxModifiedByIPAddress attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Modified By IP Address</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>adx_modifiedbyipaddress</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10153</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>100</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="adxModifiedByUsername">adxModifiedByUsername</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Modified By Username</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>100</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>adx_modifiedbyusername</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the adxModifiedByUsername attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### means.identity.name

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Modified By Username</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>adx_modifiedbyusername</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10154</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>100</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="partnerContact">partnerContact</a>

Allows a partner contact to be assigned to a specific case.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Partner Contact</td></tr>
<tr><td>description</td><td>Allows a partner contact to be assigned to a specific case.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>msa_partnercontactid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the partnerContact attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Partner Contact</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Allows a partner contact to be assigned to a specific case.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>msa_partnercontactid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10155</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "partnerContact",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Partner Contact"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Allows a partner contact to be assigned to a specific case."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Partner Contact",
  "description": "Allows a partner contact to be assigned to a specific case.",
  "isNullable": true,
  "sourceName": "msa_partnercontactid",
  "sourceOrdering": 10155
}
```

</details>

### <a name="partnerid">partnerid</a>

Creates a Relationship between a Partner (account) and a case for indirect service arrangements.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Partner</td></tr>
<tr><td>description</td><td>Creates a Relationship between a Partner (account) and a case for indirect service arrangements.</td></tr>
<tr><td>dataFormat</td><td>Guid</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>msa_partnerid</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the partnerid attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.dataFormat.guid

##### means.identity.entityId

##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>style</td><td>single</td><td>string</td><td></td></tr>
</table>

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Partner</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Creates a Relationship between a Partner (account) and a case for indirect service arrangements.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>msa_partnerid</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10156</td><td>integer</td><td></td></tr>
</table>

##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr>
</table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "partnerid",
  "appliedTraits": [
    {
      "traitReference": "is.CDS.lookup",
      "arguments": [
        {
          "name": "style",
          "value": "single"
        }
      ]
    },
    {
      "traitReference": "is.requiredAtLevel",
      "arguments": [
        {
          "name": "level",
          "value": "none"
        }
      ]
    },
    {
      "traitReference": "is.localized.displayedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Partner"
              ]
            ]
          }
        }
      ]
    },
    {
      "traitReference": "is.localized.describedAs",
      "arguments": [
        {
          "entityReference": {
            "entityShape": "localizedTable",
            "constantValues": [
              [
                "en",
                "Creates a Relationship between a Partner (account) and a case for indirect service arrangements."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Partner",
  "description": "Creates a Relationship between a Partner (account) and a case for indirect service arrangements.",
  "isNullable": true,
  "sourceName": "msa_partnerid",
  "sourceOrdering": 10156
}
```

</details>

### <a name="publishToWeb">publishToWeb</a>

If set to Yes, the case will be visible and searchable on portals connected to this organization.

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Publish to Web</td></tr>
<tr><td>description</td><td>If set to Yes, the case will be visible and searchable on portals connected to this organization.</td></tr>
<tr><td>dataFormat</td><td>Boolean</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>adx_publishtoweb</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the publishToWeb attribute are listed below.</summary>

##### is.dataFormat.boolean

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Publish to Web</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>If set to Yes, the case will be visible and searchable on portals connected to this organization.</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>adx_publishtoweb</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10161</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="resolution">resolution</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Resolution</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>10000</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>adx_resolution</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the resolution attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Resolution</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>adx_resolution</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10163</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>10000</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="resolutionDate">resolutionDate</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Resolution Date</td></tr>
<tr><td>dataFormat</td><td>DateTimeOffset</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>adx_resolutiondate</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the resolutionDate attribute are listed below.</summary>

##### is.dataFormat.date

##### means.measurement.date

##### is.dataFormat.time

##### means.measurement.time

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Resolution Date</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>adx_resolutiondate</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10164</td><td>integer</td><td></td></tr>
</table>

</details>

### <a name="stepsToReproduce">stepsToReproduce</a>

First included in: /core/applicationCommon/foundationCommon/crmCommon/solutions/portals/Case.cdm.json/Case

#### Properties

<table><tr><th>Name</th><th>Value</th></tr>
<tr><td>displayName</td><td>Steps to Reproduce</td></tr>
<tr><td>dataFormat</td><td>String</td></tr>
<tr><td>maximumLength</td><td>10000</td></tr>
<tr><td>isNullable</td><td>true</td></tr>
<tr><td>sourceName</td><td>adx_stepstoreproduce</td></tr>
</table>

#### Traits

<details>
<summary>List of traits for the stepsToReproduce attribute are listed below.</summary>

##### is.dataFormat.character

##### is.dataFormat.big

##### is.dataFormat.array

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>level</td><td>recommended</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr>
</table>

##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr>
<tr><td>en</td><td>Steps to Reproduce</td></tr>
</table>

</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr>
</table>

##### is.nullable

The attribute value may be set to NULL.

##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>name</td><td>adx_stepstoreproduce</td><td>string</td><td></td></tr>
</table>

##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>ordinal</td><td>10165</td><td>integer</td><td></td></tr>
</table>

##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr>
<tr><td>maximumLength</td><td>10000</td><td>integer</td><td></td></tr>
</table>

</details>


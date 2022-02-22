---
title: overview of AdministrationCore - Common Data Model | Microsoft Docs
description: AdministrationCore is a folder that contains standard entities related to the Common Data Model.
author: matgos

ms.reviewer: deonhe
ms.topic: reference
ms.date: 1/7/2021
ms.author: matgos
---

# Overview of AdministrationCore

CDM standard entities for 'AdministrationCore'  

## Entities

|Name|Description|
|---|---|
|[Account](Account.md)|Business that represents a customer or potential customer. The company that is billed in business transactions.|
|[AdditionalName](AdditionalName.md)|It consists the patient additional names.|
|[Contact](Contact.md)|Person with whom a business unit has a relationship, such as customer, supplier, and colleague.|
|[ContactLink](ContactLink.md)|Link to another patient entity that concerns the same actual patient.|
|[EndpointContact](EndpointContact.md)|Contact details for a human to contact about the subscription. The primary use of this for system administrator troubleshooting.|
|[EndpointHeader](EndpointHeader.md)|Additional headers / information to send as part of the notification.|
|[EndpointPayloadMimeType](EndpointPayloadMimeType.md)|The mime type to send the payload in . If the mime type is not specified, then the sender could send any content .|
|[EndpointPayloadType](EndpointPayloadType.md)|The payload type describes the acceptable content that can be communicated on the endpoint.|
|[PractitionerQualification](PractitionerQualification.md)|Qualifications obtained by training and certification.|
|[PractitionerRoleAvailableTime](PractitionerRoleAvailableTime.md)|A collection of times that the Service Site is available.|
|[PractitionerRoleCode](PractitionerRoleCode.md)|Roles which this practitioner is authorized to perform for the organization.|
|[PractitionerRoleEndPoint](PractitionerRoleEndPoint.md)|Technical endpoints providing access to services operated for the practitioner with this role.|
|[PractitionerRoleHealthcareService](PractitionerRoleHealthcareService.md)|The list of healthcare services that this worker provides for this role's Organization/Location(s).|
|[PractitionerRoleLocation](PractitionerRoleLocation.md)|The location(s) at which this practitioner provides care.|
|[PractitionerRoleSpecialty](PractitionerRoleSpecialty.md)|Specific specialty of the practitioner.|
|[PractitionerRoleTelecom](PractitionerRoleTelecom.md)|Contact details that are specific to the role/location/service.|
|[PractitionerSpecialty](PractitionerSpecialty.md)|Specific specialty of the practitioner.|
|[RequestGroupAction](RequestGroupAction.md)|The actions, if any, produced by the evaluation of the artifact.|
|[RequestGroupActionAction](RequestGroupActionAction.md)|Sub actions.|
|[RequestGroupActionCode](RequestGroupActionCode.md)|A code that provides meaning for the action or action group. For example, a section may have a LOINC code for a the section of a documentation template.|
|[RequestGroupActionCondition](RequestGroupActionCondition.md)|An expression that describes applicability criteria, or start/stop conditions for the action.|
|[RequestGroupActionDocumentation](RequestGroupActionDocumentation.md)|Didactic or other informational resources associated with the action that can be provided to the CDS recipient. Information resources can include inline text commentary and links to web resources.|
|[RequestGroupActionParticipant](RequestGroupActionParticipant.md)|The participant that should perform or be responsible for this action.|
|[RequestGroupActionRelatedAction](RequestGroupActionRelatedAction.md)|A relationship to another action such as "before" or "30-60 minutes after start of".|
|[RequestGroupBasedOn](RequestGroupBasedOn.md)|A plan, proposal or order that is fulfilled in whole or in part by this request.|
|[RequestGroupDefinition](RequestGroupDefinition.md)|A protocol, guideline, order set or other definition that is adhered to in whole or in part by this request.|
|[RequestGroupReplace](RequestGroupReplace.md)|Completed or terminated request(s) whose function is taken by this new request.|
|[SubstanceCategory](SubstanceCategory.md)|A code that classifies the general type of substance. This is used for searching, sorting and display purposes.|
|[SubstanceIngredient](SubstanceIngredient.md)|A substance can be composed of other substances.|
|[SubstanceInstance](SubstanceInstance.md)|Substance may be used to describe a kind of substance, or a specific package/container of the substance: an instance.|
|[Task](Task.md)|Generic activity representing work needed to be done.|

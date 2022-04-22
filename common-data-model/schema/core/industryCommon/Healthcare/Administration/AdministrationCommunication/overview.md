---
title: overview of AdministrationCommunication - Common Data Model | Microsoft Docs
description: AdministrationCommunication is a folder that contains standard entities related to the Common Data Model.
author: matgos

ms.reviewer: deonhe
ms.topic: reference
ms.date: 1/7/2021
ms.author: matgos
---

# Overview of AdministrationCommunication

CDM standard entities for 'AdministrationCommunication'  

## Entities

|Name|Description|
|---|---|
|[Communication](Communication.md)|An occurrence of information being transmitted; e.g. an alert that was sent to a responsible provider, a public health agency was notified about a reportable condition.|
|[CommunicationRequestBasedOn](CommunicationRequestBasedOn.md)|A plan or proposal that is fulfilled in whole or in part by this request.|
|[CommunicationRequestCategory](CommunicationRequestCategory.md)|The type of message to be sent such as alert, notification, reminder, instruction, etc.|
|[CommunicationRequestMedium](CommunicationRequestMedium.md)|A channel that was used for this communication (e.g. email, fax).|
|[CommunicationRequestPayload](CommunicationRequestPayload.md)|Text, attachment(s), or resource(s) to be communicated to the recipient.|
|[CommunicationRequestReason](CommunicationRequestReason.md)|Describes why the request is being made in coded or textual form.|
|[CommunicationRequestReasonReference](CommunicationRequestReasonReference.md)|Indicates another resource whose existence justifies this request.|
|[CommunicationRequestRecipient](CommunicationRequestRecipient.md)|The entity (e.g. person, organization, clinical information system, device, group, or care team) which is the intended target of the communication.|
|[CommunicationRequestReplace](CommunicationRequestReplace.md)|Completed or terminated request(s) whose function is taken by this new request.|
|[CommunicationRequestTopic](CommunicationRequestTopic.md)|The entities which were related to producing this communication request.|

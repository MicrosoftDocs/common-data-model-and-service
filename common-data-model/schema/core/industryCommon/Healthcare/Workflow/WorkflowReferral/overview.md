---
title: overview of WorkflowReferral - Common Data Model | Microsoft Docs
description: WorkflowReferral is a folder that contains standard entities related to the Common Data Model.
author: matgos
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 1/7/2021
ms.author: matgos
---

# Overview of WorkflowReferral

CDM standard entities for 'WorkflowReferral'  

## Entities

|Name|Description|
|---|---|
|[ReferralRequestBasedOn](ReferralRequestBasedOn.md)|Indicates any plans, proposals or orders that this request is intended to satisfy - in whole or in part.|
|[ReferralRequestDefinition](ReferralRequestDefinition.md)|A protocol, guideline, order set or other definition that is adhered to in whole or in part by this request.|
|[ReferralRequestReasonCode](ReferralRequestReasonCode.md)|Description of clinical condition indicating why referral/transfer of care is requested.|
|[ReferralRequestReasonReference](ReferralRequestReasonReference.md)|Indicates another resource whose existence justifies this request.|
|[ReferralRequestRecipient](ReferralRequestRecipient.md)|The healthcare provider(s) or provider organization(s) who/which is to receive the referral/transfer of care request.|
|[ReferralRequestRelevantHistory](ReferralRequestRelevantHistory.md)|Links to Provenance records for past versions of this entity or fulfilling request or event resources.|
|[ReferralRequestReplace](ReferralRequestReplace.md)|Completed or terminated request(s) whose function is taken by this new request.|
|[ReferralRequestServiceRequested](ReferralRequestServiceRequested.md)|The service(s) that is/are requested to be provided to the patient. For example: cardiac pacemaker insertion.|
|[ReferralRequestSupportingInformation](ReferralRequestSupportingInformation.md)|Any additional (administrative, financial or clinical) information required to support request for referral or transfer of care.|

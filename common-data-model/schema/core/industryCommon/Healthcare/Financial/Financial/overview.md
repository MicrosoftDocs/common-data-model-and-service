---
title: overview of Financial - Common Data Model | Microsoft Docs
description: Financial is a folder that contains standard entities related to the Common Data Model.
author: matgos
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 1/7/2021
ms.author: matgos
---

# Overview of Financial

CDM standard entities for 'Financial'  

## Entities

|Name|Description|
|---|---|
|[Account](Account.md)|Business that represents a customer or potential customer. The company that is billed in business transactions.|
|[BillingAccount](BillingAccount.md)|A financial tool for tracking value accrued for a particular purpose. In the healthcare field, used to track charges for a patient, cost centers, etc.|
|[Claim](Claim.md)|A provider issued list of services and products provided, or to be provided, to a patient which is provided to an insurer for payment recovery.|
|[ClaimCareTeam](ClaimCareTeam.md)|The members of the team who provided the overall service as well as their role and whether responsible and qualifications.|
|[ClaimDiagnosis](ClaimDiagnosis.md)|List of patient diagnosis for which care is sought.|
|[ClaimInformation](ClaimInformation.md)|Additional information codes regarding exceptions, special considerations, the condition, situation, prior or concurrent issues. Often there are mutiple jurisdiction specific valuesets which are requi|
|[ClaimItem](ClaimItem.md)|First tier of goods and services.|
|[ClaimResponse](ClaimResponse.md)||
|[ClaimResponseAddItem](ClaimResponseAddItem.md)||
|[ClaimResponseItem](ClaimResponseItem.md)||
|[ClaimResponseItemAdjudication](ClaimResponseItemAdjudication.md)||
|[ClaimResponseItemDetail](ClaimResponseItemDetail.md)|The second tier service adjudications for submitted services.|
|[ClaimsProcedure](ClaimsProcedure.md)|Ordered list of patient procedures performed to support the adjudication.|
|[CodeableConcept](CodeableConcept.md)|A Codeable Concept represents a value that is usually supplied by providing a reference to one or more terminologies, but may also be defined by the provision of text.|
|[Contract](Contract.md)||
|[Coverage](Coverage.md)|"The party(s) that are responsible for payment (or part of) of charges applied to this account (including self-pay).|
|[EligibilityRequest](EligibilityRequest.md)|The EligibilityRequest provides patient and insurance coverage information to an insurer for them to respond, in the form of an EligibilityResponse, with information regarding whether the stated cover|
|[EligibilityRequestItem](EligibilityRequestItem.md)|Eligibility request item.|
|[EligibilityResponse](EligibilityResponse.md)||
|[EligibilityResponseInsurance](EligibilityResponseInsurance.md)|The insurer may provide both the details for the requested coverage as well as details for additional coverages known to the insurer.|
|[EnrollmentRequest](EnrollmentRequest.md)|This resource provides the insurance enrollment details to the insurer regarding a specified coverage|
|[EnrollmentResponse](EnrollmentResponse.md)|This resource provides enrollment and plan details from the processing of an Enrollment resource.|
|[Insurance](Insurance.md)|Financial instrument by which payment information for health care.|
|[PaymentNotice](PaymentNotice.md)||

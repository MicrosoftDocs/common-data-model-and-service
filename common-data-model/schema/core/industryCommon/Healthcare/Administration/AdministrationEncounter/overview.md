---
title: overview of AdministrationEncounter - Common Data Model | Microsoft Docs
description: AdministrationEncounter is a folder that contains standard entities related to the Common Data Model.
author: matgos
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 1/7/2021
ms.author: matgos
---

# Overview of AdministrationEncounter

CDM standard entities for 'AdministrationEncounter'  

## Entities

|Name|Description|
|---|---|
|[EncounterAccount](EncounterAccount.md)|The set of accounts that may be used for billing for this Encounter.|
|[EncounterClassHistory](EncounterClassHistory.md)|The class history permits the tracking of the encounters transitions without needing to go through the entity history.|
|[EncounterDiagnosis](EncounterDiagnosis.md)|The list of diagnosis relevant to this encounter.|
|[EncounterEpisodeOfCare](EncounterEpisodeOfCare.md)|Where a specific encounter should be classified as a part of a specific episode(s) of care this field should be used.|
|[EncounterHospitalizationArrangement](EncounterHospitalizationArrangement.md)|Any special requests that have been made for this hospitalization encounter, such as the provision of specific equipment or other things.|
|[EncounterHospitalizationCourtesy](EncounterHospitalizationCourtesy.md)|Special courtesies (VIP, board member).|
|[EncounterHospitalizationDiet](EncounterHospitalizationDiet.md)|Used to track patient's diet restrictions and/or preference.|
|[EncounterLocation](EncounterLocation.md)|List of locations where the patient has been during this encounter.|
|[EncounterParticipant](EncounterParticipant.md)|The list of people responsible for providing the service.|
|[EncounterParticipantType](EncounterParticipantType.md)|The participant type indicates how an individual participates in an encounter.|
|[EncounterReason](EncounterReason.md)|Reason the encounter takes place, expressed as a code. For admissions, this can be used for a coded admission diagnosis.|
|[EncounterReferralRequest](EncounterReferralRequest.md)|The referral request this encounter satisfies (incoming referral).|
|[EncounterStatusHistory](EncounterStatusHistory.md)|The status history permits the encounter entity to contain the status history without needing to read through the historical versions of the entity, or even have the server store them|
|[EncounterType](EncounterType.md)|Specific type of encounter (e.g. e-mail consultation, surgical day-care, skilled nursing, rehabilitation).|
|[EpisodeOfCareAccount](EpisodeOfCareAccount.md)|The set of accounts that may be used for billing for this Episode Of Care.|
|[EpisodeOfCareCareTeam](EpisodeOfCareCareTeam.md)|The list of practitioners that may be facilitating this episode of care for specific purposes.|
|[EpisodeOfCareDiagnosis](EpisodeOfCareDiagnosis.md)|The list of diagnosis relevant to this episode of care.|
|[EpisodeOfCareHistory](EpisodeOfCareHistory.md)|The history of statuses that the Episode Of Care has been through (without requiring processing the history of the resource).|
|[EpisodeOfCareReferralRequest](EpisodeOfCareReferralRequest.md)|Referral Request(s) that are fulfilled by this Episode Of Care, incoming referrals.|
|[EpisodeOfCareType](EpisodeOfCareType.md)|A classification of the type of episode of care; e.g. specialist referral, disease management, type of funded care.|

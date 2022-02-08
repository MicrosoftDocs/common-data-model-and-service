---
title: overview of ClinicalCareTeam - Common Data Model | Microsoft Docs
description: ClinicalCareTeam is a folder that contains standard entities related to the Common Data Model.
author: matgos
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: reference
ms.date: 1/7/2021
ms.author: matgos
---

# Overview of ClinicalCareTeam

CDM standard entities for 'ClinicalCareTeam'  

## Entities

|Name|Description|
|---|---|
|[CarePlanActivity](CarePlanActivity.md)|Identifies a planned action to occur as part of the plan. For example, a medication to be used, lab tests to perform, self-monitoring, education, etc.|
|[CarePlanActivityGoal](CarePlanActivityGoal.md)|Internal reference that identifies the goals that this activity is intended to contribute towards meeting.|
|[CarePlanActivityOutcome](CarePlanActivityOutcome.md)|Identifies the outcome at the point when the status of the activity is assessed. For example, the outcome of an education activity could be patient understands (or not).|
|[CarePlanActivityOutcomeReference](CarePlanActivityOutcomeReference.md)|Details of the outcome or action resulting from the activity.|
|[CarePlanActivityPerformer](CarePlanActivityPerformer.md)|Identifies who's expected to be involved in the activity.|
|[CarePlanActivityReason](CarePlanActivityReason.md)|Provides the rationale that drove the inclusion of this particular activity as part of the plan or the reason why the activity was prohibited.|
|[CarePlanActivityReasonCode](CarePlanActivityReasonCode.md)|Provides the rationale that drove the inclusion of this particular activity as part of the plan or the reason why the activity was prohibited.|
|[CarePlanActivityReasonReference](CarePlanActivityReasonReference.md)|Provides the health condition(s) that drove the inclusion of this particular activity as part of the plan.|
|[CarePlanAddresses](CarePlanAddresses.md)|Identifies the conditions/problems/concerns/diagnoses/etc. whose management and/or mitigation are handled by this plan.|
|[CarePlanAuthor](CarePlanAuthor.md)|Identifies the individual(s) or organization who is responsible for the content of the care plan.|
|[CarePlanBasedOn](CarePlanBasedOn.md)|A care plan that is fulfilled in whole or in part by this care plan.|
|[CarePlanCareTeam](CarePlanCareTeam.md)|Identifies all people and organizations who are expected to be involved in the care envisioned by this plan.|
|[CarePlanCategory](CarePlanCategory.md)|Identifies what "kind" of plan this is to support differentiation between multiple co-existing plans; e.g. "Home health", "psychiatric", "asthma", "disease management", "wellness plan", etc.|
|[CarePlanDefinition](CarePlanDefinition.md)|Identifies the protocol, questionnaire, guideline or other specification the care plan should be conducted in accordance with.|
|[CarePlanGoal](CarePlanGoal.md)|Describes the intended objective(s) of carrying out the care plan.|
|[CarePlanGoalMeasure](CarePlanGoalMeasure.md)||
|[CarePlanGoalOutcome](CarePlanGoalOutcome.md)||
|[CarePlanPartOf](CarePlanPartOf.md)|A larger care plan of which this particular care plan is a component or step.|
|[CarePlanReplace](CarePlanReplace.md)|Completed or terminated care plan whose function is taken by this new care plan.|
|[CarePlanSupportInfo](CarePlanSupportInfo.md)|Identifies portions of the patient's record that specifically influenced the formation of the plan. These might include co-morbidities, recent procedures, limitations, recent assessments, etc.|
|[CareTeamCategory](CareTeamCategory.md)|Identifies what kind of team. This is to support differentiation between multiple co-existing teams, such as care plan team, episode of care team, longitudinal care team.|
|[CareTeamManagingOrganization](CareTeamManagingOrganization.md)|The organization responsible for the care team.|
|[CareTeamParticipant](CareTeamParticipant.md)|Identifies all people and organizations who are expected to be involved in the care team.|
|[CareTeamParticipantRole](CareTeamParticipantRole.md)|Indicates specific responsibility of an individual within the care team, such as "Primary care physician", "Trained social worker counselor", "Caregiver", etc.|
|[CareTeamReasonCode](CareTeamReasonCode.md)|Describes why the care team exists.|
|[CareTeamReasonReference](CareTeamReasonReference.md)|Condition(s) that this care team addresses.|
|[Goal](Goal.md)|Target objective for a user or a team for a specified time period.|

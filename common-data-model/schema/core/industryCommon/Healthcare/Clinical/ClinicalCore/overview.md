---
title: overview of ClinicalCore - Common Data Model | Microsoft Docs
description: ClinicalCore is a folder that contains standard entities related to the Common Data Model.
author: matgos

ms.reviewer: deonhe
ms.topic: reference
ms.date: 1/7/2021
ms.author: matgos
---

# Overview of ClinicalCore

CDM standard entities for 'ClinicalCore'  

## Entities

|Name|Description|
|---|---|
|[AllergyIntolerance](AllergyIntolerance.md)|Risk of harmful or undesirable, physiological response which is unique to an individual and associated with exposure to a substance.|
|[ClinicalImpression](ClinicalImpression.md)|A record of a clinical assessment performed to determine what problem(s) may affect the patient and before planning the treatments or management strategies that are best to manage a patient condition|
|[ClinicalImpressionAction](ClinicalImpressionAction.md)|Action taken as part of assessment procedure.|
|[ClinicalImpressionFinding](ClinicalImpressionFinding.md)|Specific findings or diagnoses that was considered likely or relevant to ongoing treatment.|
|[ClinicalImpressionInvestigation](ClinicalImpressionInvestigation.md)|One or more sets of investigations (signs, etc.). The actual grouping of investigations vary greatly depending on the type and context of the assessment.|
|[ClinicalImpressionInvestigationItem](ClinicalImpressionInvestigationItem.md)|A record of a specific investigation that was undertaken.|
|[ClinicalImpressionProblem](ClinicalImpressionProblem.md)|This a list of the relevant problems/conditions for a patient.|
|[ClinicalImpressionPrognosis](ClinicalImpressionPrognosis.md)|Estimate of likely outcome.|
|[ClinicalImpressionProtocol](ClinicalImpressionProtocol.md)|Reference to a specific published clinical protocol that was followed during this assessment, and/or that provides evidence in support of the diagnosis.|
|[ConditionBodySite](ConditionBodySite.md)|The anatomical location where this condition manifests itself.|
|[ConditionCategory](ConditionCategory.md)|A category assigned to the condition.|
|[ConditionEvidence](ConditionEvidence.md)|Supporting Evidence / manifestations that are the basis on which this condition is suspected or confirmed.|
|[ConditionStage](ConditionStage.md)|Clinical stage or grade of a condition. May include formal severity assessments.|
|[FamilyMemberHistory](FamilyMemberHistory.md)|Significant health events and conditions for a person related to the patient relevant in the context of care for the patient.|
|[FamilyMemberHistoryCondition](FamilyMemberHistoryCondition.md)|The significant Conditions (or condition) that the family member had.|
|[FamilyMemberHistoryDefinition](FamilyMemberHistoryDefinition.md)|A protocol or questionnaire that was adhered to in whole or in part by this event.|
|[FamilyMemberHistoryReason](FamilyMemberHistoryReason.md)|Describes why the family member history occurred in coded or textual form.|
|[FamilyMemberHistoryReasonReference](FamilyMemberHistoryReasonReference.md)|Indicates a Condition, Observation, Allergy Intolerance, or Questionnaire Response that justifies this family member history event.|
|[GoalAddresses](GoalAddresses.md)|The identified conditions and other health record elements that are intended to be addressed by the goal.|
|[GoalCategory](GoalCategory.md)|Indicates a category the goal falls within.|
|[GoalOutcome](GoalOutcome.md)|Identifies the change (or lack of change) at the point when the status of the goal is assessed.|
|[GoalOutcomeReference](GoalOutcomeReference.md)|Details of what's changed (or not changed).|
|[RiskAssessment](RiskAssessment.md)|An assessment of the likely outcome(s) for a patient or other subject as well as the likelihood of each outcome.|
|[RiskAssessmentBasis](RiskAssessmentBasis.md)|Indicates the source data considered as part of the assessment (Family History, Observations, Procedures, Conditions, etc.).|
|[RiskAssessmentPrediction](RiskAssessmentPrediction.md)|Describes the expected outcome for the subject.|

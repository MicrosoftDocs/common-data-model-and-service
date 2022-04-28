---
title: overview of WorkflowCore - Common Data Model | Microsoft Docs
description: WorkflowCore is a folder that contains standard entities related to the Common Data Model.
author: matgos

ms.reviewer: deonhe
ms.topic: reference
ms.date: 1/7/2021
ms.author: matgos
---

# Overview of WorkflowCore

CDM standard entities for 'WorkflowCore'  

## Entities

|Name|Description|
|---|---|
|[PlanDefinitionAction](PlanDefinitionAction.md)|An action to be taken as part of the plan.|
|[PlanDefinitionActionAction](PlanDefinitionActionAction.md)|Sub actions that are contained within the action. The behavior of this action determines the functionality of the sub-actions.|
|[PlanDefinitionActionArtifact](PlanDefinitionActionArtifact.md)|Didactic or other informational entities associated with the action that can be provided to the CDS recipient. Information entities can include inline text commentary and links to web resources.|
|[PlanDefinitionActionCode](PlanDefinitionActionCode.md)|A code that provides meaning for the action or action group. For example, a section may have a LOINC code for a the section of a documentation template.|
|[PlanDefinitionActionCondition](PlanDefinitionActionCondition.md)|An expression that describes applicability criteria, or start/stop conditions for the action.|
|[PlanDefinitionActionDynamicValue](PlanDefinitionActionDynamicValue.md)|Customization that should be applied to the statically defined entity.|
|[PlanDefinitionActionGoal](PlanDefinitionActionGoal.md)|Identifies goals that this action supports. The reference must be to a goal element defined within this plan definition.|
|[PlanDefinitionActionInput](PlanDefinitionActionInput.md)|Defines input data requirements for the action.|
|[PlanDefinitionActionOutput](PlanDefinitionActionOutput.md)|Defines the outputs of the action, if any.|
|[PlanDefinitionActionReason](PlanDefinitionActionReason.md)|A description of why this action is necessary or appropriate.|
|[PlanDefinitionActionRelatedAction](PlanDefinitionActionRelatedAction.md)|A relationship to another action such as "before" or "30-60 minutes after start of".|
|[PlanDefinitionActionTriggerDefinition](PlanDefinitionActionTriggerDefinition.md)|A description of when the action should be triggered.|
|[PlanDefinitionArtifact](PlanDefinitionArtifact.md)|Related artifacts such as additional documentation, justification, or bibliographic references.|
|[PlanDefinitionContributor](PlanDefinitionContributor.md)|A contributor to the content of the asset, including authors, editors, reviewers, and endorsers.|
|[PlanDefinitionContributorContact](PlanDefinitionContributorContact.md)|Contact details to assist a user in finding and communicating with the contributor.|
|[PlanDefinitionGoal](PlanDefinitionGoal.md)|Goals that describe what the activities within the plan are intended to achieve.|
|[PlanDefinitionGoalAddresses](PlanDefinitionGoalAddresses.md)|Identifies problems, conditions, issues, or concerns the goal is intended to address.|
|[PlanDefinitionGoalArtifact](PlanDefinitionGoalArtifact.md)|Didactic or other informational resources associated with the goal that provide further supporting information about the goal. Information resources can include inline text commentary and links to web|
|[PlanDefinitionGoalTarget](PlanDefinitionGoalTarget.md)|Indicates what should be done and within what time frame.|
|[PlanDefinitionJurisdiction](PlanDefinitionJurisdiction.md)|A legal or geographic region in which the plan definition is intended to be used.|
|[PlanDefinitionLibrary](PlanDefinitionLibrary.md)|A reference to a Library entity containing any formal logic used by the plan definition.|
|[PlanDefinitionParticipant](PlanDefinitionParticipant.md)|Indicates who should participate in performing the action described.|
|[PlanDefinitionTopic](PlanDefinitionTopic.md)|Descriptive topics related to the content of the plan definition. Topics provide a high-level categorization of the definition that can be useful for filtering and searching.|
|[PlanDefinitionUseContext](PlanDefinitionUseContext.md)|The content was developed with a focus and intent of supporting the contexts that are listed. These terms may be used to assist with indexing and searching for appropriate plan definition instances.|
|[ReferenceRangeAppliesTo](ReferenceRangeAppliesTo.md)||
|[TaskBasedOn](TaskBasedOn.md)|BasedOn refers to a higher-level authorization that triggered the creation of the task. It references a "request" entity such as a ProcedureRequest, MedicationRequest, ProcedureRequest, CarePlan, etc|
|[TaskInput](TaskInput.md)|Additional information that may be needed in the execution of the task.|
|[TaskOutput](TaskOutput.md)|Outputs produced by the Task.|
|[TaskPartOf](TaskPartOf.md)|Task that this particular task is part of.|
|[TaskPerformerType](TaskPerformerType.md)|The type of participant that can execute the task.|
|[TaskRelevantHistory](TaskRelevantHistory.md)|Links to Provenance records for past versions of this Task that identify key state transitions or updates that are likely to be relevant to a user looking at the current version of the task.|
|[TaskRestrictionRecipient](TaskRestrictionRecipient.md)|For requests that are targeted to more than on potential recipient/target, for whom is fulfillment sought.|

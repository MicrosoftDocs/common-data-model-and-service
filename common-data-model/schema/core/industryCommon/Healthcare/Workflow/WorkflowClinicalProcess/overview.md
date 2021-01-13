---
title: overview of WorkflowClinicalProcess - Common Data Model | Microsoft Docs
description: WorkflowClinicalProcess is a folder that contains standard entities related to the Common Data Model.
author: matgos
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 1/7/2021
ms.author: matgos
---

# Overview of WorkflowClinicalProcess

CDM standard entities for 'WorkflowClinicalProcess'  

## Entities

|Name|Description|
|---|---|
|[ActivityDefinitionBodySite](ActivityDefinitionBodySite.md)|Indicates the sites on the subject's body where the procedure should be performed (I.e. the target sites).|
|[ActivityDefinitionContact](ActivityDefinitionContact.md)|Contact details to assist a user in finding and communicating with the publisher.|
|[ActivityDefinitionContributor](ActivityDefinitionContributor.md)|A contributor to the content of the asset, including authors, editors, reviewers, and endorsers.|
|[ActivityDefinitionContributorContact](ActivityDefinitionContributorContact.md)|Contact details to assist a user in finding and communicating with the contributor.|
|[ActivityDefinitionDosage](ActivityDefinitionDosage.md)|Provides detailed dosage instructions in the same way that they are described for Medication Request entities.|
|[ActivityDefinitionDynamicValue](ActivityDefinitionDynamicValue.md)|Dynamic values that will be evaluated to produce values for elements of the resulting entity.|
|[ActivityDefinitionJurisdiction](ActivityDefinitionJurisdiction.md)|A legal or geographic region in which the activity definition is intended to be used.|
|[ActivityDefinitionLibrary](ActivityDefinitionLibrary.md)|A reference to a Library entity containing any formal logic used by the asset.|
|[ActivityDefinitionParticipant](ActivityDefinitionParticipant.md)|Indicates who should participate in performing the action described.|
|[ActivityDefinitionRelatedArtifact](ActivityDefinitionRelatedArtifact.md)|Related artifacts such as additional documentation, justification, or bibliographic references.|
|[ActivityDefinitionTopic](ActivityDefinitionTopic.md)|Descriptive topics related to the content of the activity. Topics provide a high-level categorization of the activity that can be useful for filtering and searching.|
|[ActivityDefinitionUseContext](ActivityDefinitionUseContext.md)|The content was developed with a focus and intent of supporting the contexts that are listed. These terms may be used to assist with indexing and searching for appropriate activity definition instance|
|[NutritionOrderAllergyIntolerance](NutritionOrderAllergyIntolerance.md)|A link to a record of allergies or intolerance which should be included in the nutrition order.|
|[NutritionOrderEnteralFormulaAdministration](NutritionOrderEnteralFormulaAdministration.md)|Formula administration instructions as structured data. This repeating structure allows for changing the administration rate or volume over time for both bolus and continuous feeding.|
|[NutritionOrderExcludeFoodModifier](NutritionOrderExcludeFoodModifier.md)|This modifier is used to convey order-specific modifiers about the type of food that should NOT be given. These can be derived from patient allergies, intolerance, or preferences such as No Red Meat,|
|[NutritionOrderFoodPreferenceModifier](NutritionOrderFoodPreferenceModifier.md)|This modifier is used to convey order-specific modifiers about the type of food that should be given. These can be derived from patient allergies, intolerance, or preferences.|
|[NutritionOrderOralDietFluidConsistencyType](NutritionOrderOralDietFluidConsistencyType.md)|The required consistency (e.g. honey-thick, nectar-thick, thin, thickened.) of liquids or fluids served to the patient.|
|[NutritionOrderOralDietNutrient](NutritionOrderOralDietNutrient.md)|Class that defines the quantity and type of nutrient modifications (for example carbohydrate, fiber or sodium) required for the oral diet.|
|[NutritionOrderOralDietSchedule](NutritionOrderOralDietSchedule.md)|The time period and frequency at which the diet should be given. The diet should be given for the combination of all schedules if more than one schedule is present.|
|[NutritionOrderOralDietTexture](NutritionOrderOralDietTexture.md)|Class that describes any texture modifications required for the patient to safely consume various types of solid foods.|
|[NutritionOrderOralDietType](NutritionOrderOralDietType.md)|The kind of diet or dietary restriction such as fiber restricted diet or diabetic diet.|
|[NutritionOrderSupplement](NutritionOrderSupplement.md)|Oral nutritional products given in order to add further nutritional value to the patient's diet.|
|[NutritionOrderSupplementSchedule](NutritionOrderSupplementSchedule.md)|The time period and frequency at which the supplement(s) should be given. The supplement should be given for the combination of all schedules if more than one schedule is present.|
|[VisionPrescriptionDispense](VisionPrescriptionDispense.md)|Deals with details of the dispense part of the supply specification.|

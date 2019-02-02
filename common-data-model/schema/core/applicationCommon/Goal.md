---
title: Goal_
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/1/2019
ms.author: tpalmer
---
# Goal

## Properties

Display Name: Goal

Description: Target objective for a user or a team for a specified time period.

Latest Version: 0.8.1

Entity Definition on GitHub: [https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/Goal.cdm.json](https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/Goal.cdm.json)

## Instances

## Attributes - Summary

<table><tr><th>Name</th><th>Description</th><th>First Included in Instance</th></tr><tr><td>[createdOn](#created-on)</td><td>Date and time when the record was created.</td><td> </td></tr><tr><td>createdBy</td><td>Shows who created the record.</td><td> </td></tr><tr><td>modifiedOn</td><td>Date and time when the record was modified.</td><td> </td></tr><tr><td>modifiedBy</td><td>Shows who last updated the record.</td><td> </td></tr><tr><td>createdOnBehalfBy</td><td>Shows who created the record on behalf of another user.</td><td> </td></tr><tr><td>modifiedOnBehalfBy</td><td>Shows who last updated the record on behalf of another user.</td><td> </td></tr><tr><td>overriddenCreatedOn</td><td>Date and time that the record was migrated.</td><td> </td></tr><tr><td>importSequenceNumber</td><td>Unique identifier of the data import or data migration that created this record.</td><td> </td></tr><tr><td>ownerIdType</td><td>The type of owner, either User or Team.</td><td> </td></tr><tr><td>ownerId</td><td>Owner Id</td><td> </td></tr><tr><td>owningBusinessUnit</td><td>Unique identifier for the business unit that owns the record</td><td> </td></tr><tr><td>owningUser</td><td>Unique identifier of the user that owns the activity.</td><td> </td></tr><tr><td>owningTeam</td><td>Unique identifier for the team that owns the record.</td><td> </td></tr><tr><td>timeZoneRuleVersionNumber</td><td>For internal use only.</td><td> </td></tr><tr><td>UTCConversionTimeZoneCode</td><td>Time zone code that was in use when the record was created.</td><td> </td></tr><tr><td>versionNumber</td><td>Version Number</td><td> </td></tr><tr><td>goalId</td><td>Unique identifier of the goal.</td><td> </td></tr><tr><td>stateCode</td><td>Shows whether the goal is open, completed, or canceled. Completed and canceled goals are read-only and can't be edited.</td><td> </td></tr><tr><td>stateCode_display</td><td>undefined</td><td> </td></tr><tr><td>statusCode</td><td>Select the goal's status.</td><td> </td></tr><tr><td>statusCode_display</td><td>undefined</td><td> </td></tr><tr><td>title</td><td>Type a title or name that describes the goal.</td><td> </td></tr><tr><td>fiscalPeriod</td><td>Select the fiscal period for the goal.</td><td> </td></tr><tr><td>fiscalPeriod_display</td><td>undefined</td><td> </td></tr><tr><td>fiscalYear</td><td>Select the fiscal year for the goal that's being tracked.</td><td> </td></tr><tr><td>fiscalYear_display</td><td>undefined</td><td> </td></tr><tr><td>goalStartDate</td><td>Enter the date and time when the period for tracking the goal begins.</td><td> </td></tr><tr><td>goalEndDate</td><td>Enter the date when the goal ends.</td><td> </td></tr><tr><td>goalOwnerIdType</td><td>The name of the entity linked by goalOwnerId</td><td> </td></tr><tr><td>goalOwnerId</td><td>Choose the user or team responsible for meeting the goal.</td><td> </td></tr><tr><td>parentGoalId</td><td>Choose a parent goal if the current goal is a child goal. This sets up a parent-child relationship for reporting and analytics.</td><td> </td></tr><tr><td>transactionCurrencyId</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td><td> </td></tr><tr><td>exchangeRate</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td><td> </td></tr><tr><td>metricId</td><td>Choose the metric for the goal. This metric determines how the goal is tracked.</td><td> </td></tr><tr><td>treeId</td><td>Unique identifier of the goal tree.</td><td> </td></tr><tr><td>depth</td><td>Depth of the goal in the tree.</td><td> </td></tr><tr><td>stretchTargetMoney</td><td>Select stretch target (money) of the goal to define a higher or difficult level of goal than the usual ones.</td><td> </td></tr><tr><td>stretchTargetMoneyBase</td><td>Shows the stretch target (money) in base currency to indicate a higher or difficult level of goal than the usual ones.</td><td> </td></tr><tr><td>stretchTargetDecimal</td><td>Select a stretch target (decimal) of the goal to define a higher or difficult level of goal than the usual ones.</td><td> </td></tr><tr><td>stretchTargetInteger</td><td>Select the stretch target (integer) of the goal to define a higher or difficult level of goal than the usual ones.</td><td> </td></tr><tr><td>targetMoney</td><td>Select a goal target (money) to track a monetary amount such as revenue from a product.</td><td> </td></tr><tr><td>targetMoneyBase</td><td>Shows the goal target of the money type in base currency.</td><td> </td></tr><tr><td>targetDecimal</td><td>Select a goal target of the decimal type to use for tracking data that include partial numbers, such as pounds sold of a product sold by weight.</td><td> </td></tr><tr><td>targetInteger</td><td>Select a goal target of the integer type to use for tracking anything countable in whole numbers, such as units sold.</td><td> </td></tr><tr><td>actualMoney</td><td>Shows the actual value (Money type) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount and the amount data type is Money.</td><td> </td></tr><tr><td>actualMoneyBase</td><td>Shows the actual value (money type) in base currency to track goal results against the target.</td><td> </td></tr><tr><td>customRollupFieldMoney</td><td>Indicates a placeholder rollup field for a money value to track a third category of results other than actuals and in-progress results.</td><td> </td></tr><tr><td>customRollupFieldMoneyBase</td><td>Indicates a placeholder rollup field for a money value in base currency to track a third category of results other than actuals and in-progress results.</td><td> </td></tr><tr><td>inProgressMoney</td><td>Shows the in-progress value (money) against the target. This value could contribute to a goal, but is not counted yet as actual.</td><td> </td></tr><tr><td>inProgressMoneyBase</td><td>Shows the in-progress value (money) in base currency to track goal results against the target.</td><td> </td></tr><tr><td>actualDecimal</td><td>Shows the actual value (Decimal type) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount and the amount data type is Decimal.</td><td> </td></tr><tr><td>customRollupFieldDecimal</td><td>Indicates a placeholder rollup field for a decimal value to track a third category of results other than actuals and in-progress results.</td><td> </td></tr><tr><td>inProgressDecimal</td><td>Shows the in-progress value (decimal) against the target. This value could contribute to a goal, but is not counted yet as actual.</td><td> </td></tr><tr><td>actualInteger</td><td>Shows the actual value (integer) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount or Count and the amount data type is Integer.</td><td> </td></tr><tr><td>customRollupFieldInteger</td><td>Indicates a placeholder rollup field for an integer value to track a third category of results other than actuals and in-progress results.</td><td> </td></tr><tr><td>inProgressInteger</td><td>Shows the in-progress value (integer) against the target. This value could contribute to a goal, but is not counted yet as actual.</td><td> </td></tr><tr><td>percentage</td><td>Shows the percentage achieved against the target goal.</td><td> </td></tr><tr><td>isFiscalPeriodGoal</td><td>Select whether the goal period is a fiscal period or custom period.</td><td> </td></tr><tr><td>considerOnlyGoalOwnersRecords</td><td>Select whether only the goal owner's records, or all records, should be rolled up for goal results.</td><td> </td></tr><tr><td>lastRolledupDate</td><td>Shows the date and time when the goal was last rolled up. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.</td><td> </td></tr><tr><td>targetString</td><td>Target value of the goal.</td><td> </td></tr><tr><td>stretchTargetString</td><td>Stretch target value for all data types.</td><td> </td></tr><tr><td>actualString</td><td>Actual Value of the goal.</td><td> </td></tr><tr><td>customRollupFieldString</td><td>Placeholder rollup field for the goal.</td><td> </td></tr><tr><td>inProgressString</td><td>In-progress value of the goal.</td><td> </td></tr><tr><td>amountDataType</td><td>Data type of the amount.</td><td> </td></tr><tr><td>amountDataType_display</td><td>undefined</td><td> </td></tr><tr><td>isAmount</td><td>Indicates whether the metric type is Count or Amount.</td><td> </td></tr><tr><td>rollupQueryActualIntegerId</td><td>Choose the query that will be used to calculate the actual data for the goal (integer).</td><td> </td></tr><tr><td>rollUpQueryActualMoneyId</td><td>Choose the query that will be used to calculate the actual data for the goal (money).</td><td> </td></tr><tr><td>rollUpQueryActualDecimalId</td><td>Choose the query that will be used to calculate the actual data for the goal (decimal).</td><td> </td></tr><tr><td>rollUpQueryCustomIntegerId</td><td>Choose the query that will be used to calculate data for the custom rollup field (integer).</td><td> </td></tr><tr><td>rollUpQueryCustomMoneyId</td><td>Choose the query that will be used to calculate data for the custom rollup field (money).</td><td> </td></tr><tr><td>rollUpQueryCustomDecimalId</td><td>Choose the query that will be used to calculate data for the custom rollup field (decimal).</td><td> </td></tr><tr><td>rollUpQueryInprogressIntegerId</td><td>Choose the query that will be used to calculate data for the in-progress rollup field (integer).</td><td> </td></tr><tr><td>rollUpQueryInprogressMoneyId</td><td>Choose the query that will be used to calculate data for the in-progress rollup field (money).</td><td> </td></tr><tr><td>rollUpQueryInprogressDecimalId</td><td>Choose the query that will be used to calculate data for the in-progress rollup field (decimal).</td><td> </td></tr><tr><td>rollupOnlyFromChildGoals</td><td>Select whether the data should be rolled up only from the child goals.</td><td> </td></tr><tr><td>goalWithErrorId</td><td>Unique identifier of the goal that caused an error in the rollup of the goal hierarchy.</td><td> </td></tr><tr><td>rollupErrorCode</td><td>Error code associated with rollup.</td><td> </td></tr><tr><td>computedTargetAsOfTodayPercentageAchieved</td><td>Shows the expected value for percentage achieved against the target goal as of the current date.</td><td> </td></tr><tr><td>computedTargetAsOfTodayMoney</td><td>Shows the expected amount for actual value (money type) against the target goal as of the current date.</td><td> </td></tr><tr><td>computedTargetAsOfTodayMoneyBase</td><td>Shows the expected amount in base currency for actual value (money type) against the target goal as of the current date.</td><td> </td></tr><tr><td>computedTargetAsOfTodayDecimal</td><td>Shows the expected amount for actual value (decimal type) against the target goal.</td><td> </td></tr><tr><td>computedTargetAsOfTodayInteger</td><td>Shows the expected amount for actual value (integer type) against the target goal as of the current date.</td><td> </td></tr><tr><td>isOverride</td><td>Indicates whether the values of system rollup fields can be updated.</td><td> </td></tr><tr><td>isOverridden</td><td>Select whether the system rollup fields are updated. If set to Yes, the next system rollup will not update the values of the rollup fields with the system calculated values.</td><td> </td></tr><tr><td>entityImageId</td><td>For internal use only.</td><td> </td></tr></table>

## Attribute - Details

### createdOn

Date and time when the record was created.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### means.measurement.date.creation


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created On</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was created.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>createdon</td><td>string</td><td>undefined</td></tr></table>


### createdBy

Shows who created the record.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Shows who created the record.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdby</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

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

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created By</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who created the record.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>createdby</td><td>string</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

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

### modifiedOn

Date and time when the record was modified.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### means.measurement.date.modify


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified On</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was modified.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>modifiedon</td><td>string</td><td>undefined</td></tr></table>


### modifiedBy

Shows who last updated the record.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Shows who last updated the record.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

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

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified By</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who last updated the record.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>modifiedby</td><td>string</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

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

### createdOnBehalfBy

Shows who created the record on behalf of another user.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Shows who created the record on behalf of another user.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

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

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created By (Delegate)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who created the record on behalf of another user.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>createdonbehalfby</td><td>string</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

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

### modifiedOnBehalfBy

Shows who last updated the record on behalf of another user.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Shows who last updated the record on behalf of another user.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

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

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified By (Delegate)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows who last updated the record on behalf of another user.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>modifiedonbehalfby</td><td>string</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

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

### overriddenCreatedOn

Date and time that the record was migrated.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### means.measurement.date.creation


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Record Created On</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time that the record was migrated.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>overriddencreatedon</td><td>string</td><td>undefined</td></tr></table>


### importSequenceNumber

Unique identifier of the data import or data migration that created this record.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Unique identifier of the data import or data migration that created this record.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Import Sequence Number</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the data import or data migration that created this record.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>importsequencenumber</td><td>string</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-2147483648</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### ownerIdType

The type of owner, either User or Team.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner Type</td></tr><tr><td>description</td><td>The type of owner, either User or Team.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>owneridtype</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.entityName


##### is.readOnly


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner Type</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The type of owner, either User or Team.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>owneridtype</td><td>string</td><td>undefined</td></tr></table>


##### is.linkedEntity.name

Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.


##### is.CDS.owner

contains a User or Team ID


### ownerId

Owner Id

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owner</td></tr><tr><td>description</td><td>Owner Id</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>ownerid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owner Id</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>ownerid</td><td>string</td><td>undefined</td></tr></table>


##### is.linkedEntity.identifier

Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.


##### is.CDS.owner

contains a User or Team ID


### owningBusinessUnit

Unique identifier for the business unit that owns the record

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Business Unit</td></tr><tr><td>description</td><td>Unique identifier for the business unit that owns the record</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningbusinessunit</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning Business Unit</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the business unit that owns the record</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>owningbusinessunit</td><td>string</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

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

### owningUser

Unique identifier of the user that owns the activity.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning User</td></tr><tr><td>description</td><td>Unique identifier of the user that owns the activity.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owninguser</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

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

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning User</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the user that owns the activity.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>owninguser</td><td>string</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "userId"...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

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

### owningTeam

Unique identifier for the team that owns the record.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Owning Team</td></tr><tr><td>description</td><td>Unique identifier for the team that owns the record.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>owningteam</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Owning Team</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for the team that owns the record.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>owningteam</td><td>string</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

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

### timeZoneRuleVersionNumber

For internal use only.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time Zone Rule Version Number</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>timezoneruleversionnumber</td><td>string</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-1</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### UTCConversionTimeZoneCode

Time zone code that was in use when the record was created.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>UTC Conversion Time Zone Code</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time zone code that was in use when the record was created.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>utcconversiontimezonecode</td><td>string</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-1</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### versionNumber

Version Number

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Version Number</td></tr><tr><td>description</td><td>Version Number</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int64</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>versionnumber</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.dataFormat.big


##### means.measurement.version


##### is.CDS.standard

identifies attributes that are part of the cdsStandard base set.


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version Number</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Version Number</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>versionnumber</td><td>string</td><td>undefined</td></tr></table>


### goalId

Unique identifier of the goal.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Goal</td></tr><tr><td>description</td><td>Unique identifier of the goal.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>goalid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.identifiedBy

names a specifc identity attribute to use with an entity

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>attribute</td><td>"Goal_/hasAttributes/goalId"</td><td>attribute</td><td>undefined</td></tr></table>

Definition:

```
"Goal_/hasAttributes/goalId"
```

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Goal</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the goal.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>goalid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>1</td><td>integer</td><td>undefined</td></tr></table>


### stateCode

Shows whether the goal is open, completed, or canceled. Completed and canceled goals are read-only and can't be edited.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Shows whether the goal is open, completed, or canceled. Completed and canceled goals are read-only and can't be edited.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td>[
  {
    "languageTag": "en",
    "displayText": "Active",
    "attributeValue": "0",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Inactive",
    "attributeValue": "1",
    "displayOrder": "1"
  }
]</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr><tr><td>en</td><td>Active</td><td>0</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td><td>1</td></tr></table>
</td><td>any</td><td>undefined</td></tr></table>


##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities


##### means.entityState

the attribute represents the current state of the entity.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>attribute</td><td>"Goal_/hasAttributes/stateCode"</td><td>attribute</td><td>undefined</td></tr></table>

Definition:

```
"Goal_/hasAttributes/stateCode"
```

##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows whether the goal is open, completed, or canceled. Completed and canceled goals are read-only and can't be edited.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>statecode</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>20</td><td>integer</td><td>undefined</td></tr></table>


### stateCode_display

undefined

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.reference.displayText


##### is.readOnly


##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>stateCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>


### statusCode

Select the goal's status.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Select the goal's status.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td>[
  {
    "languageTag": "en",
    "displayText": "Open",
    "attributeValue": "0",
    "displayOrder": "0",
    "correlatedValue": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Closed",
    "attributeValue": "1",
    "displayOrder": "1",
    "correlatedValue": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Discarded",
    "attributeValue": "2",
    "displayOrder": "2",
    "correlatedValue": "1"
  }
]</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>correlatedValue</th></tr><tr><td>en</td><td>Open</td><td>0</td><td>0</td><td>0</td></tr><tr><td>en</td><td>Closed</td><td>1</td><td>1</td><td>1</td></tr><tr><td>en</td><td>Discarded</td><td>2</td><td>2</td><td>1</td></tr></table>
</td><td>any</td><td>undefined</td></tr></table>


##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities


##### is.correlatedWith

the attribute value is correlated with the sourceAttribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>sourceAttribute</td><td>stateCode</td><td>attributeName</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status Reason</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select the goal's status.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>statuscode</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>22</td><td>integer</td><td>undefined</td></tr></table>


### statusCode_display

undefined

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.reference.displayText


##### is.readOnly


##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>statusCode</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>


### title

Type a title or name that describes the goal.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Type a title or name that describes the goal.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>title</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>required</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Type a title or name that describes the goal.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>title</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>29</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>100</td><td>integer</td><td>undefined</td></tr></table>


### fiscalPeriod

Select the fiscal period for the goal.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal Period</td></tr><tr><td>description</td><td>Select the fiscal period for the goal.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fiscalperiod</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td>[
  {
    "languageTag": "en",
    "displayText": "Quarter 1",
    "attributeValue": "1",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Quarter 2",
    "attributeValue": "2",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Quarter 3",
    "attributeValue": "3",
    "displayOrder": "2"
  },
  {
    "languageTag": "en",
    "displayText": "Quarter 4",
    "attributeValue": "4",
    "displayOrder": "3"
  },
  {
    "languageTag": "en",
    "displayText": "January",
    "attributeValue": "101",
    "displayOrder": "4"
  },
  {
    "languageTag": "en",
    "displayText": "February",
    "attributeValue": "102",
    "displayOrder": "5"
  },
  {
    "languageTag": "en",
    "displayText": "March",
    "attributeValue": "103",
    "displayOrder": "6"
  },
  {
    "languageTag": "en",
    "displayText": "April",
    "attributeValue": "104",
    "displayOrder": "7"
  },
  {
    "languageTag": "en",
    "displayText": "May",
    "attributeValue": "105",
    "displayOrder": "8"
  },
  {
    "languageTag": "en",
    "displayText": "June",
    "attributeValue": "106",
    "displayOrder": "9"
  },
  {
    "languageTag": "en",
    "displayText": "July",
    "attributeValue": "107",
    "displayOrder": "10"
  },
  {
    "languageTag": "en",
    "displayText": "August",
    "attributeValue": "108",
    "displayOrder": "11"
  },
  {
    "languageTag": "en",
    "displayText": "September",
    "attributeValue": "109",
    "displayOrder": "12"
  },
  {
    "languageTag": "en",
    "displayText": "October",
    "attributeValue": "110",
    "displayOrder": "13"
  },
  {
    "languageTag": "en",
    "displayText": "November",
    "attributeValue": "111",
    "displayOrder": "14"
  },
  {
    "languageTag": "en",
    "displayText": "December",
    "attributeValue": "112",
    "displayOrder": "15"
  },
  {
    "languageTag": "en",
    "displayText": "Semester 1",
    "attributeValue": "201",
    "displayOrder": "16"
  },
  {
    "languageTag": "en",
    "displayText": "Semester 2",
    "attributeValue": "202",
    "displayOrder": "17"
  },
  {
    "languageTag": "en",
    "displayText": "Annual",
    "attributeValue": "301",
    "displayOrder": "18"
  },
  {
    "languageTag": "en",
    "displayText": "P1",
    "attributeValue": "401",
    "displayOrder": "19"
  },
  {
    "languageTag": "en",
    "displayText": "P2",
    "attributeValue": "402",
    "displayOrder": "20"
  },
  {
    "languageTag": "en",
    "displayText": "P3",
    "attributeValue": "403",
    "displayOrder": "21"
  },
  {
    "languageTag": "en",
    "displayText": "P4",
    "attributeValue": "404",
    "displayOrder": "22"
  },
  {
    "languageTag": "en",
    "displayText": "P5",
    "attributeValue": "405",
    "displayOrder": "23"
  },
  {
    "languageTag": "en",
    "displayText": "P6",
    "attributeValue": "406",
    "displayOrder": "24"
  },
  {
    "languageTag": "en",
    "displayText": "P7",
    "attributeValue": "407",
    "displayOrder": "25"
  },
  {
    "languageTag": "en",
    "displayText": "P8",
    "attributeValue": "408",
    "displayOrder": "26"
  },
  {
    "languageTag": "en",
    "displayText": "P9",
    "attributeValue": "409",
    "displayOrder": "27"
  },
  {
    "languageTag": "en",
    "displayText": "P10",
    "attributeValue": "410",
    "displayOrder": "28"
  },
  {
    "languageTag": "en",
    "displayText": "P11",
    "attributeValue": "411",
    "displayOrder": "29"
  },
  {
    "languageTag": "en",
    "displayText": "P12",
    "attributeValue": "412",
    "displayOrder": "30"
  },
  {
    "languageTag": "en",
    "displayText": "P13",
    "attributeValue": "413",
    "displayOrder": "31"
  }
]</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr><tr><td>en</td><td>Quarter 1</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Quarter 2</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Quarter 3</td><td>3</td><td>2</td></tr><tr><td>en</td><td>Quarter 4</td><td>4</td><td>3</td></tr><tr><td>en</td><td>January</td><td>101</td><td>4</td></tr><tr><td>en</td><td>February</td><td>102</td><td>5</td></tr><tr><td>en</td><td>March</td><td>103</td><td>6</td></tr><tr><td>en</td><td>April</td><td>104</td><td>7</td></tr><tr><td>en</td><td>May</td><td>105</td><td>8</td></tr><tr><td>en</td><td>June</td><td>106</td><td>9</td></tr><tr><td>en</td><td>July</td><td>107</td><td>10</td></tr><tr><td>en</td><td>August</td><td>108</td><td>11</td></tr><tr><td>en</td><td>September</td><td>109</td><td>12</td></tr><tr><td>en</td><td>October</td><td>110</td><td>13</td></tr><tr><td>en</td><td>November</td><td>111</td><td>14</td></tr><tr><td>en</td><td>December</td><td>112</td><td>15</td></tr><tr><td>en</td><td>Semester 1</td><td>201</td><td>16</td></tr><tr><td>en</td><td>Semester 2</td><td>202</td><td>17</td></tr><tr><td>en</td><td>Annual</td><td>301</td><td>18</td></tr><tr><td>en</td><td>P1</td><td>401</td><td>19</td></tr><tr><td>en</td><td>P2</td><td>402</td><td>20</td></tr><tr><td>en</td><td>P3</td><td>403</td><td>21</td></tr><tr><td>en</td><td>P4</td><td>404</td><td>22</td></tr><tr><td>en</td><td>P5</td><td>405</td><td>23</td></tr><tr><td>en</td><td>P6</td><td>406</td><td>24</td></tr><tr><td>en</td><td>P7</td><td>407</td><td>25</td></tr><tr><td>en</td><td>P8</td><td>408</td><td>26</td></tr><tr><td>en</td><td>P9</td><td>409</td><td>27</td></tr><tr><td>en</td><td>P10</td><td>410</td><td>28</td></tr><tr><td>en</td><td>P11</td><td>411</td><td>29</td></tr><tr><td>en</td><td>P12</td><td>412</td><td>30</td></tr><tr><td>en</td><td>P13</td><td>413</td><td>31</td></tr></table>
</td><td>any</td><td>undefined</td></tr></table>


##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fiscal Period</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select the fiscal period for the goal.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>fiscalperiod</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>30</td><td>integer</td><td>undefined</td></tr></table>


### fiscalPeriod_display

undefined

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.reference.displayText


##### is.readOnly


##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>fiscalPeriod</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>


### fiscalYear

Select the fiscal year for the goal that's being tracked.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal Year</td></tr><tr><td>description</td><td>Select the fiscal year for the goal that's being tracked.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>fiscalyear</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td>[
  {
    "languageTag": "en",
    "displayText": "FY2038",
    "attributeValue": "2038",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "FY2037",
    "attributeValue": "2037",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "FY2036",
    "attributeValue": "2036",
    "displayOrder": "2"
  },
  {
    "languageTag": "en",
    "displayText": "FY2035",
    "attributeValue": "2035",
    "displayOrder": "3"
  },
  {
    "languageTag": "en",
    "displayText": "FY2034",
    "attributeValue": "2034",
    "displayOrder": "4"
  },
  {
    "languageTag": "en",
    "displayText": "FY2033",
    "attributeValue": "2033",
    "displayOrder": "5"
  },
  {
    "languageTag": "en",
    "displayText": "FY2032",
    "attributeValue": "2032",
    "displayOrder": "6"
  },
  {
    "languageTag": "en",
    "displayText": "FY2031",
    "attributeValue": "2031",
    "displayOrder": "7"
  },
  {
    "languageTag": "en",
    "displayText": "FY2030",
    "attributeValue": "2030",
    "displayOrder": "8"
  },
  {
    "languageTag": "en",
    "displayText": "FY2029",
    "attributeValue": "2029",
    "displayOrder": "9"
  },
  {
    "languageTag": "en",
    "displayText": "FY2028",
    "attributeValue": "2028",
    "displayOrder": "10"
  },
  {
    "languageTag": "en",
    "displayText": "FY2027",
    "attributeValue": "2027",
    "displayOrder": "11"
  },
  {
    "languageTag": "en",
    "displayText": "FY2026",
    "attributeValue": "2026",
    "displayOrder": "12"
  },
  {
    "languageTag": "en",
    "displayText": "FY2025",
    "attributeValue": "2025",
    "displayOrder": "13"
  },
  {
    "languageTag": "en",
    "displayText": "FY2024",
    "attributeValue": "2024",
    "displayOrder": "14"
  },
  {
    "languageTag": "en",
    "displayText": "FY2023",
    "attributeValue": "2023",
    "displayOrder": "15"
  },
  {
    "languageTag": "en",
    "displayText": "FY2022",
    "attributeValue": "2022",
    "displayOrder": "16"
  },
  {
    "languageTag": "en",
    "displayText": "FY2021",
    "attributeValue": "2021",
    "displayOrder": "17"
  },
  {
    "languageTag": "en",
    "displayText": "FY2020",
    "attributeValue": "2020",
    "displayOrder": "18"
  },
  {
    "languageTag": "en",
    "displayText": "FY2019",
    "attributeValue": "2019",
    "displayOrder": "19"
  },
  {
    "languageTag": "en",
    "displayText": "FY2018",
    "attributeValue": "2018",
    "displayOrder": "20"
  },
  {
    "languageTag": "en",
    "displayText": "FY2017",
    "attributeValue": "2017",
    "displayOrder": "21"
  },
  {
    "languageTag": "en",
    "displayText": "FY2016",
    "attributeValue": "2016",
    "displayOrder": "22"
  },
  {
    "languageTag": "en",
    "displayText": "FY2015",
    "attributeValue": "2015",
    "displayOrder": "23"
  },
  {
    "languageTag": "en",
    "displayText": "FY2014",
    "attributeValue": "2014",
    "displayOrder": "24"
  },
  {
    "languageTag": "en",
    "displayText": "FY2013",
    "attributeValue": "2013",
    "displayOrder": "25"
  },
  {
    "languageTag": "en",
    "displayText": "FY2012",
    "attributeValue": "2012",
    "displayOrder": "26"
  },
  {
    "languageTag": "en",
    "displayText": "FY2011",
    "attributeValue": "2011",
    "displayOrder": "27"
  },
  {
    "languageTag": "en",
    "displayText": "FY2010",
    "attributeValue": "2010",
    "displayOrder": "28"
  },
  {
    "languageTag": "en",
    "displayText": "FY2009",
    "attributeValue": "2009",
    "displayOrder": "29"
  },
  {
    "languageTag": "en",
    "displayText": "FY2008",
    "attributeValue": "2008",
    "displayOrder": "30"
  },
  {
    "languageTag": "en",
    "displayText": "FY2007",
    "attributeValue": "2007",
    "displayOrder": "31"
  },
  {
    "languageTag": "en",
    "displayText": "FY2006",
    "attributeValue": "2006",
    "displayOrder": "32"
  },
  {
    "languageTag": "en",
    "displayText": "FY2005",
    "attributeValue": "2005",
    "displayOrder": "33"
  },
  {
    "languageTag": "en",
    "displayText": "FY2004",
    "attributeValue": "2004",
    "displayOrder": "34"
  },
  {
    "languageTag": "en",
    "displayText": "FY2003",
    "attributeValue": "2003",
    "displayOrder": "35"
  },
  {
    "languageTag": "en",
    "displayText": "FY2002",
    "attributeValue": "2002",
    "displayOrder": "36"
  },
  {
    "languageTag": "en",
    "displayText": "FY2001",
    "attributeValue": "2001",
    "displayOrder": "37"
  },
  {
    "languageTag": "en",
    "displayText": "FY2000",
    "attributeValue": "2000",
    "displayOrder": "38"
  },
  {
    "languageTag": "en",
    "displayText": "FY1999",
    "attributeValue": "1999",
    "displayOrder": "39"
  },
  {
    "languageTag": "en",
    "displayText": "FY1998",
    "attributeValue": "1998",
    "displayOrder": "40"
  },
  {
    "languageTag": "en",
    "displayText": "FY1997",
    "attributeValue": "1997",
    "displayOrder": "41"
  },
  {
    "languageTag": "en",
    "displayText": "FY1996",
    "attributeValue": "1996",
    "displayOrder": "42"
  },
  {
    "languageTag": "en",
    "displayText": "FY1995",
    "attributeValue": "1995",
    "displayOrder": "43"
  },
  {
    "languageTag": "en",
    "displayText": "FY1994",
    "attributeValue": "1994",
    "displayOrder": "44"
  },
  {
    "languageTag": "en",
    "displayText": "FY1993",
    "attributeValue": "1993",
    "displayOrder": "45"
  },
  {
    "languageTag": "en",
    "displayText": "FY1992",
    "attributeValue": "1992",
    "displayOrder": "46"
  },
  {
    "languageTag": "en",
    "displayText": "FY1991",
    "attributeValue": "1991",
    "displayOrder": "47"
  },
  {
    "languageTag": "en",
    "displayText": "FY1990",
    "attributeValue": "1990",
    "displayOrder": "48"
  },
  {
    "languageTag": "en",
    "displayText": "FY1989",
    "attributeValue": "1989",
    "displayOrder": "49"
  },
  {
    "languageTag": "en",
    "displayText": "FY1988",
    "attributeValue": "1988",
    "displayOrder": "50"
  },
  {
    "languageTag": "en",
    "displayText": "FY1987",
    "attributeValue": "1987",
    "displayOrder": "51"
  },
  {
    "languageTag": "en",
    "displayText": "FY1986",
    "attributeValue": "1986",
    "displayOrder": "52"
  },
  {
    "languageTag": "en",
    "displayText": "FY1985",
    "attributeValue": "1985",
    "displayOrder": "53"
  },
  {
    "languageTag": "en",
    "displayText": "FY1984",
    "attributeValue": "1984",
    "displayOrder": "54"
  },
  {
    "languageTag": "en",
    "displayText": "FY1983",
    "attributeValue": "1983",
    "displayOrder": "55"
  },
  {
    "languageTag": "en",
    "displayText": "FY1982",
    "attributeValue": "1982",
    "displayOrder": "56"
  },
  {
    "languageTag": "en",
    "displayText": "FY1981",
    "attributeValue": "1981",
    "displayOrder": "57"
  },
  {
    "languageTag": "en",
    "displayText": "FY1980",
    "attributeValue": "1980",
    "displayOrder": "58"
  },
  {
    "languageTag": "en",
    "displayText": "FY1979",
    "attributeValue": "1979",
    "displayOrder": "59"
  },
  {
    "languageTag": "en",
    "displayText": "FY1978",
    "attributeValue": "1978",
    "displayOrder": "60"
  },
  {
    "languageTag": "en",
    "displayText": "FY1977",
    "attributeValue": "1977",
    "displayOrder": "61"
  },
  {
    "languageTag": "en",
    "displayText": "FY1976",
    "attributeValue": "1976",
    "displayOrder": "62"
  },
  {
    "languageTag": "en",
    "displayText": "FY1975",
    "attributeValue": "1975",
    "displayOrder": "63"
  },
  {
    "languageTag": "en",
    "displayText": "FY1974",
    "attributeValue": "1974",
    "displayOrder": "64"
  },
  {
    "languageTag": "en",
    "displayText": "FY1973",
    "attributeValue": "1973",
    "displayOrder": "65"
  },
  {
    "languageTag": "en",
    "displayText": "FY1972",
    "attributeValue": "1972",
    "displayOrder": "66"
  },
  {
    "languageTag": "en",
    "displayText": "FY1971",
    "attributeValue": "1971",
    "displayOrder": "67"
  },
  {
    "languageTag": "en",
    "displayText": "FY1970",
    "attributeValue": "1970",
    "displayOrder": "68"
  }
]</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr><tr><td>en</td><td>FY2038</td><td>2038</td><td>0</td></tr><tr><td>en</td><td>FY2037</td><td>2037</td><td>1</td></tr><tr><td>en</td><td>FY2036</td><td>2036</td><td>2</td></tr><tr><td>en</td><td>FY2035</td><td>2035</td><td>3</td></tr><tr><td>en</td><td>FY2034</td><td>2034</td><td>4</td></tr><tr><td>en</td><td>FY2033</td><td>2033</td><td>5</td></tr><tr><td>en</td><td>FY2032</td><td>2032</td><td>6</td></tr><tr><td>en</td><td>FY2031</td><td>2031</td><td>7</td></tr><tr><td>en</td><td>FY2030</td><td>2030</td><td>8</td></tr><tr><td>en</td><td>FY2029</td><td>2029</td><td>9</td></tr><tr><td>en</td><td>FY2028</td><td>2028</td><td>10</td></tr><tr><td>en</td><td>FY2027</td><td>2027</td><td>11</td></tr><tr><td>en</td><td>FY2026</td><td>2026</td><td>12</td></tr><tr><td>en</td><td>FY2025</td><td>2025</td><td>13</td></tr><tr><td>en</td><td>FY2024</td><td>2024</td><td>14</td></tr><tr><td>en</td><td>FY2023</td><td>2023</td><td>15</td></tr><tr><td>en</td><td>FY2022</td><td>2022</td><td>16</td></tr><tr><td>en</td><td>FY2021</td><td>2021</td><td>17</td></tr><tr><td>en</td><td>FY2020</td><td>2020</td><td>18</td></tr><tr><td>en</td><td>FY2019</td><td>2019</td><td>19</td></tr><tr><td>en</td><td>FY2018</td><td>2018</td><td>20</td></tr><tr><td>en</td><td>FY2017</td><td>2017</td><td>21</td></tr><tr><td>en</td><td>FY2016</td><td>2016</td><td>22</td></tr><tr><td>en</td><td>FY2015</td><td>2015</td><td>23</td></tr><tr><td>en</td><td>FY2014</td><td>2014</td><td>24</td></tr><tr><td>en</td><td>FY2013</td><td>2013</td><td>25</td></tr><tr><td>en</td><td>FY2012</td><td>2012</td><td>26</td></tr><tr><td>en</td><td>FY2011</td><td>2011</td><td>27</td></tr><tr><td>en</td><td>FY2010</td><td>2010</td><td>28</td></tr><tr><td>en</td><td>FY2009</td><td>2009</td><td>29</td></tr><tr><td>en</td><td>FY2008</td><td>2008</td><td>30</td></tr><tr><td>en</td><td>FY2007</td><td>2007</td><td>31</td></tr><tr><td>en</td><td>FY2006</td><td>2006</td><td>32</td></tr><tr><td>en</td><td>FY2005</td><td>2005</td><td>33</td></tr><tr><td>en</td><td>FY2004</td><td>2004</td><td>34</td></tr><tr><td>en</td><td>FY2003</td><td>2003</td><td>35</td></tr><tr><td>en</td><td>FY2002</td><td>2002</td><td>36</td></tr><tr><td>en</td><td>FY2001</td><td>2001</td><td>37</td></tr><tr><td>en</td><td>FY2000</td><td>2000</td><td>38</td></tr><tr><td>en</td><td>FY1999</td><td>1999</td><td>39</td></tr><tr><td>en</td><td>FY1998</td><td>1998</td><td>40</td></tr><tr><td>en</td><td>FY1997</td><td>1997</td><td>41</td></tr><tr><td>en</td><td>FY1996</td><td>1996</td><td>42</td></tr><tr><td>en</td><td>FY1995</td><td>1995</td><td>43</td></tr><tr><td>en</td><td>FY1994</td><td>1994</td><td>44</td></tr><tr><td>en</td><td>FY1993</td><td>1993</td><td>45</td></tr><tr><td>en</td><td>FY1992</td><td>1992</td><td>46</td></tr><tr><td>en</td><td>FY1991</td><td>1991</td><td>47</td></tr><tr><td>en</td><td>FY1990</td><td>1990</td><td>48</td></tr><tr><td>en</td><td>FY1989</td><td>1989</td><td>49</td></tr><tr><td>en</td><td>FY1988</td><td>1988</td><td>50</td></tr><tr><td>en</td><td>FY1987</td><td>1987</td><td>51</td></tr><tr><td>en</td><td>FY1986</td><td>1986</td><td>52</td></tr><tr><td>en</td><td>FY1985</td><td>1985</td><td>53</td></tr><tr><td>en</td><td>FY1984</td><td>1984</td><td>54</td></tr><tr><td>en</td><td>FY1983</td><td>1983</td><td>55</td></tr><tr><td>en</td><td>FY1982</td><td>1982</td><td>56</td></tr><tr><td>en</td><td>FY1981</td><td>1981</td><td>57</td></tr><tr><td>en</td><td>FY1980</td><td>1980</td><td>58</td></tr><tr><td>en</td><td>FY1979</td><td>1979</td><td>59</td></tr><tr><td>en</td><td>FY1978</td><td>1978</td><td>60</td></tr><tr><td>en</td><td>FY1977</td><td>1977</td><td>61</td></tr><tr><td>en</td><td>FY1976</td><td>1976</td><td>62</td></tr><tr><td>en</td><td>FY1975</td><td>1975</td><td>63</td></tr><tr><td>en</td><td>FY1974</td><td>1974</td><td>64</td></tr><tr><td>en</td><td>FY1973</td><td>1973</td><td>65</td></tr><tr><td>en</td><td>FY1972</td><td>1972</td><td>66</td></tr><tr><td>en</td><td>FY1971</td><td>1971</td><td>67</td></tr><tr><td>en</td><td>FY1970</td><td>1970</td><td>68</td></tr></table>
</td><td>any</td><td>undefined</td></tr></table>


##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fiscal Year</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select the fiscal year for the goal that's being tracked.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>fiscalyear</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>32</td><td>integer</td><td>undefined</td></tr></table>


### fiscalYear_display

undefined

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.reference.displayText


##### is.readOnly


##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>fiscalYear</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>


### goalStartDate

Enter the date and time when the period for tracking the goal begins.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>From</td></tr><tr><td>description</td><td>Enter the date and time when the period for tracking the goal begins.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>goalstartdate</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>From</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Enter the date and time when the period for tracking the goal begins.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>goalstartdate</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>34</td><td>integer</td><td>undefined</td></tr></table>


### goalEndDate

Enter the date when the goal ends.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>To</td></tr><tr><td>description</td><td>Enter the date when the goal ends.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>goalenddate</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>To</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Enter the date when the goal ends.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>goalenddate</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>35</td><td>integer</td><td>undefined</td></tr></table>


### goalOwnerIdType

The name of the entity linked by goalOwnerId

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>goalOwnerId Type</td></tr><tr><td>description</td><td>The name of the entity linked by goalOwnerId</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>goalowneridtype</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.entityName


##### is.readOnly


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>goalOwnerId Type</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The name of the entity linked by goalOwnerId</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>goalowneridtype</td><td>string</td><td>undefined</td></tr></table>


##### is.linkedEntity.name

Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.


### goalOwnerId

Choose the user or team responsible for meeting the goal.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Goal Owner</td></tr><tr><td>description</td><td>Choose the user or team responsible for meeting the goal.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>goalownerid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>required</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Goal Owner</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Choose the user or team responsible for meeting the goal.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>goalownerid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>36</td><td>integer</td><td>undefined</td></tr></table>


##### is.linkedEntity.identifier

Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.


### parentGoalId

Choose a parent goal if the current goal is a child goal. This sets up a parent-child relationship for reporting and analytics.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Parent Goal</td></tr><tr><td>description</td><td>Choose a parent goal if the current goal is a child goal. This sets up a parent-child relationship for reporting and analytics.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>parentgoalid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Parent Goal</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Choose a parent goal if the current goal is a child goal. This sets up a parent-child relationship for reporting and analytics.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>parentgoalid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>39</td><td>integer</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "parentGoalId",
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
                "Parent Goal"
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
                "Choose a parent goal if the current goal is a child goal. This sets up a parent-child relationship for reporting and analytics."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Parent Goal",
  "description": "Choose a parent goal if the current goal is a child goal. This sets up a parent-child relationship for reporting and analytics.",
  "isNullable": true,
  "sourceName": "parentgoalid",
  "sourceOrdering": 39
}
```

### transactionCurrencyId

Choose the local currency for the record to make sure budgets are reported in the correct currency.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Currency</td></tr><tr><td>description</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>transactioncurrencyid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Currency</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Choose the local currency for the record to make sure budgets are reported in the correct currency.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>transactioncurrencyid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>42</td><td>integer</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

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
  "sourceOrdering": 42
}
```

### exchangeRate

Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Exchange Rate</td></tr><tr><td>description</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>1E-10</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>exchangerate</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Exchange Rate</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the conversion rate of the record's currency. The exchange rate is used to convert all money fields in the record from the local currency to the system's default currency.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>exchangerate</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>44</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>1E-10</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>100000000000</td><td>decimal</td><td>undefined</td></tr></table>


### metricId

Choose the metric for the goal. This metric determines how the goal is tracked.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Goal Metric</td></tr><tr><td>description</td><td>Choose the metric for the goal. This metric determines how the goal is tracked.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>metricid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>required</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Goal Metric</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Choose the metric for the goal. This metric determines how the goal is tracked.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>metricid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>48</td><td>integer</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "metricId",
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
          "value": "required"
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
                "Goal Metric"
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
                "Choose the metric for the goal. This metric determines how the goal is tracked."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Goal Metric",
  "description": "Choose the metric for the goal. This metric determines how the goal is tracked.",
  "isNullable": true,
  "sourceName": "metricid",
  "sourceOrdering": 48
}
```

### treeId

Unique identifier of the goal tree.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Tree ID</td></tr><tr><td>description</td><td>Unique identifier of the goal tree.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>treeid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Tree ID</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the goal tree.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>treeid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>54</td><td>integer</td><td>undefined</td></tr></table>


### depth

Depth of the goal in the tree.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Depth</td></tr><tr><td>description</td><td>Depth of the goal in the tree.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>depth</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Depth</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Depth of the goal in the tree.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>depth</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>55</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### stretchTargetMoney

Select stretch target (money) of the goal to define a higher or difficult level of goal than the usual ones.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stretch Target (Money)</td></tr><tr><td>description</td><td>Select stretch target (money) of the goal to define a higher or difficult level of goal than the usual ones.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stretchtargetmoney</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### means.measurement.currency


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Stretch Target (Money)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select stretch target (money) of the goal to define a higher or difficult level of goal than the usual ones.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>stretchtargetmoney</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>106</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td>undefined</td></tr></table>


### stretchTargetMoneyBase

Shows the stretch target (money) in base currency to indicate a higher or difficult level of goal than the usual ones.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stretch Target (Money) (Base)</td></tr><tr><td>description</td><td>Shows the stretch target (money) in base currency to indicate a higher or difficult level of goal than the usual ones.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stretchtargetmoney_base</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### means.measurement.currency


##### is.calculationOf

the attribute value is the result of a calculation on the sourceAttribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>sourceAttribute</td><td>stretchTargetMoney</td><td>attributeName</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Stretch Target (Money) (Base)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the stretch target (money) in base currency to indicate a higher or difficult level of goal than the usual ones.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>stretchtargetmoney_base</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>107</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-922337203685477</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td>undefined</td></tr></table>


### stretchTargetDecimal

Select a stretch target (decimal) of the goal to define a higher or difficult level of goal than the usual ones.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stretch Target (Decimal)</td></tr><tr><td>description</td><td>Select a stretch target (decimal) of the goal to define a higher or difficult level of goal than the usual ones.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stretchtargetdecimal</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Stretch Target (Decimal)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select a stretch target (decimal) of the goal to define a higher or difficult level of goal than the usual ones.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>stretchtargetdecimal</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>108</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>100000000000</td><td>decimal</td><td>undefined</td></tr></table>


### stretchTargetInteger

Select the stretch target (integer) of the goal to define a higher or difficult level of goal than the usual ones.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stretch Target (Integer)</td></tr><tr><td>description</td><td>Select the stretch target (integer) of the goal to define a higher or difficult level of goal than the usual ones.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stretchtargetinteger</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Stretch Target (Integer)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select the stretch target (integer) of the goal to define a higher or difficult level of goal than the usual ones.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>stretchtargetinteger</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>109</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### targetMoney

Select a goal target (money) to track a monetary amount such as revenue from a product.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Target (Money)</td></tr><tr><td>description</td><td>Select a goal target (money) to track a monetary amount such as revenue from a product.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>targetmoney</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### means.measurement.currency


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Target (Money)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select a goal target (money) to track a monetary amount such as revenue from a product.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>targetmoney</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>110</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td>undefined</td></tr></table>


### targetMoneyBase

Shows the goal target of the money type in base currency.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Target (Money) (Base)</td></tr><tr><td>description</td><td>Shows the goal target of the money type in base currency.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>targetmoney_base</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### means.measurement.currency


##### is.calculationOf

the attribute value is the result of a calculation on the sourceAttribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>sourceAttribute</td><td>targetMoney</td><td>attributeName</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Target (Money) (Base)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the goal target of the money type in base currency.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>targetmoney_base</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>111</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-922337203685477</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td>undefined</td></tr></table>


### targetDecimal

Select a goal target of the decimal type to use for tracking data that include partial numbers, such as pounds sold of a product sold by weight.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Target (Decimal)</td></tr><tr><td>description</td><td>Select a goal target of the decimal type to use for tracking data that include partial numbers, such as pounds sold of a product sold by weight.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>targetdecimal</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Target (Decimal)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select a goal target of the decimal type to use for tracking data that include partial numbers, such as pounds sold of a product sold by weight.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>targetdecimal</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>112</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>100000000000</td><td>decimal</td><td>undefined</td></tr></table>


### targetInteger

Select a goal target of the integer type to use for tracking anything countable in whole numbers, such as units sold.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Target (Integer)</td></tr><tr><td>description</td><td>Select a goal target of the integer type to use for tracking anything countable in whole numbers, such as units sold.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>targetinteger</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Target (Integer)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select a goal target of the integer type to use for tracking anything countable in whole numbers, such as units sold.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>targetinteger</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>113</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### actualMoney

Shows the actual value (Money type) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount and the amount data type is Money.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual (Money)</td></tr><tr><td>description</td><td>Shows the actual value (Money type) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount and the amount data type is Money.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualmoney</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### means.measurement.currency


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Actual (Money)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the actual value (Money type) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount and the amount data type is Money.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>actualmoney</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>114</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-922337203685477</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td>undefined</td></tr></table>


### actualMoneyBase

Shows the actual value (money type) in base currency to track goal results against the target.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual (Money) (Base)</td></tr><tr><td>description</td><td>Shows the actual value (money type) in base currency to track goal results against the target.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualmoney_base</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### means.measurement.currency


##### is.calculationOf

the attribute value is the result of a calculation on the sourceAttribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>sourceAttribute</td><td>actualMoney</td><td>attributeName</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Actual (Money) (Base)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the actual value (money type) in base currency to track goal results against the target.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>actualmoney_base</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>115</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-922337203685477</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td>undefined</td></tr></table>


### customRollupFieldMoney

Indicates a placeholder rollup field for a money value to track a third category of results other than actuals and in-progress results.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Custom Rollup Field (Money)</td></tr><tr><td>description</td><td>Indicates a placeholder rollup field for a money value to track a third category of results other than actuals and in-progress results.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customrollupfieldmoney</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### means.measurement.currency


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Custom Rollup Field (Money)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates a placeholder rollup field for a money value to track a third category of results other than actuals and in-progress results.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>customrollupfieldmoney</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>116</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-922337203685477</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td>undefined</td></tr></table>


### customRollupFieldMoneyBase

Indicates a placeholder rollup field for a money value in base currency to track a third category of results other than actuals and in-progress results.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Custom Rollup Field (Money) (Base)</td></tr><tr><td>description</td><td>Indicates a placeholder rollup field for a money value in base currency to track a third category of results other than actuals and in-progress results.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customrollupfieldmoney_base</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### means.measurement.currency


##### is.calculationOf

the attribute value is the result of a calculation on the sourceAttribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>sourceAttribute</td><td>customRollupFieldMoney</td><td>attributeName</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Custom Rollup Field (Money) (Base)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates a placeholder rollup field for a money value in base currency to track a third category of results other than actuals and in-progress results.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>customrollupfieldmoney_base</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>117</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-922337203685477</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td>undefined</td></tr></table>


### inProgressMoney

Shows the in-progress value (money) against the target. This value could contribute to a goal, but is not counted yet as actual.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>In-progress (Money)</td></tr><tr><td>description</td><td>Shows the in-progress value (money) against the target. This value could contribute to a goal, but is not counted yet as actual.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>inprogressmoney</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### means.measurement.currency


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>In-progress (Money)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the in-progress value (money) against the target. This value could contribute to a goal, but is not counted yet as actual.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>inprogressmoney</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>118</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-922337203685477</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td>undefined</td></tr></table>


### inProgressMoneyBase

Shows the in-progress value (money) in base currency to track goal results against the target.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>In-progress (Money) (Base)</td></tr><tr><td>description</td><td>Shows the in-progress value (money) in base currency to track goal results against the target.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>inprogressmoney_base</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### means.measurement.currency


##### is.calculationOf

the attribute value is the result of a calculation on the sourceAttribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>sourceAttribute</td><td>inProgressMoney</td><td>attributeName</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>In-progress (Money) (Base)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the in-progress value (money) in base currency to track goal results against the target.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>inprogressmoney_base</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>119</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-922337203685477</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td>undefined</td></tr></table>


### actualDecimal

Shows the actual value (Decimal type) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount and the amount data type is Decimal.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual (Decimal)</td></tr><tr><td>description</td><td>Shows the actual value (Decimal type) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount and the amount data type is Decimal.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualdecimal</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Actual (Decimal)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the actual value (Decimal type) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount and the amount data type is Decimal.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>actualdecimal</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>120</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-100000000000</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>100000000000</td><td>decimal</td><td>undefined</td></tr></table>


### customRollupFieldDecimal

Indicates a placeholder rollup field for a decimal value to track a third category of results other than actuals and in-progress results.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Custom Rollup Field (Decimal)</td></tr><tr><td>description</td><td>Indicates a placeholder rollup field for a decimal value to track a third category of results other than actuals and in-progress results.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customrollupfielddecimal</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Custom Rollup Field (Decimal)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates a placeholder rollup field for a decimal value to track a third category of results other than actuals and in-progress results.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>customrollupfielddecimal</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>121</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-100000000000</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>100000000000</td><td>decimal</td><td>undefined</td></tr></table>


### inProgressDecimal

Shows the in-progress value (decimal) against the target. This value could contribute to a goal, but is not counted yet as actual.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>In-progress (Decimal)</td></tr><tr><td>description</td><td>Shows the in-progress value (decimal) against the target. This value could contribute to a goal, but is not counted yet as actual.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>inprogressdecimal</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>In-progress (Decimal)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the in-progress value (decimal) against the target. This value could contribute to a goal, but is not counted yet as actual.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>inprogressdecimal</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>122</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-100000000000</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>100000000000</td><td>decimal</td><td>undefined</td></tr></table>


### actualInteger

Shows the actual value (integer) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount or Count and the amount data type is Integer.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual (Integer)</td></tr><tr><td>description</td><td>Shows the actual value (integer) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount or Count and the amount data type is Integer.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualinteger</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Actual (Integer)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the actual value (integer) achieved towards the target as of the last rolled-up date. This field appears when the metric type of the goal is Amount or Count and the amount data type is Integer.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>actualinteger</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>123</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-2147483648</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### customRollupFieldInteger

Indicates a placeholder rollup field for an integer value to track a third category of results other than actuals and in-progress results.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Custom Rollup Field (Integer)</td></tr><tr><td>description</td><td>Indicates a placeholder rollup field for an integer value to track a third category of results other than actuals and in-progress results.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customrollupfieldinteger</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Custom Rollup Field (Integer)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates a placeholder rollup field for an integer value to track a third category of results other than actuals and in-progress results.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>customrollupfieldinteger</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>124</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-2147483648</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### inProgressInteger

Shows the in-progress value (integer) against the target. This value could contribute to a goal, but is not counted yet as actual.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>In-progress (Integer)</td></tr><tr><td>description</td><td>Shows the in-progress value (integer) against the target. This value could contribute to a goal, but is not counted yet as actual.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>inprogressinteger</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>In-progress (Integer)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the in-progress value (integer) against the target. This value could contribute to a goal, but is not counted yet as actual.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>inprogressinteger</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>125</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-2147483648</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### percentage

Shows the percentage achieved against the target goal.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Percentage Achieved</td></tr><tr><td>description</td><td>Shows the percentage achieved against the target goal.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>percentage</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Percentage Achieved</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the percentage achieved against the target goal.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>percentage</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>126</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-100000000000</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>100000000000</td><td>decimal</td><td>undefined</td></tr></table>


### isFiscalPeriodGoal

Select whether the goal period is a fiscal period or custom period.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Goal Period Type</td></tr><tr><td>description</td><td>Select whether the goal period is a fiscal period or custom period.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isfiscalperiodgoal</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.boolean


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Goal Period Type</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select whether the goal period is a fiscal period or custom period.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>isfiscalperiodgoal</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>127</td><td>integer</td><td>undefined</td></tr></table>


### considerOnlyGoalOwnersRecords

Select whether only the goal owner's records, or all records, should be rolled up for goal results.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Set for Rollup</td></tr><tr><td>description</td><td>Select whether only the goal owner's records, or all records, should be rolled up for goal results.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>consideronlygoalownersrecords</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.boolean


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Record Set for Rollup</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select whether only the goal owner's records, or all records, should be rolled up for goal results.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>consideronlygoalownersrecords</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>129</td><td>integer</td><td>undefined</td></tr></table>


### lastRolledupDate

Shows the date and time when the goal was last rolled up. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last Rolled Up Date</td></tr><tr><td>description</td><td>Shows the date and time when the goal was last rolled up. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>lastrolledupdate</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.date


##### means.measurement.date


##### is.dataFormat.time


##### means.measurement.time


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Last Rolled Up Date</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the date and time when the goal was last rolled up. The date and time are displayed in the time zone selected in Microsoft Dynamics 365 options.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>lastrolledupdate</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>131</td><td>integer</td><td>undefined</td></tr></table>


### targetString

Target value of the goal.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Target</td></tr><tr><td>description</td><td>Target value of the goal.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>targetstring</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Target</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Target value of the goal.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>targetstring</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>132</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>100</td><td>integer</td><td>undefined</td></tr></table>


### stretchTargetString

Stretch target value for all data types.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Stretched Target</td></tr><tr><td>description</td><td>Stretch target value for all data types.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>stretchtargetstring</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Stretched Target</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Stretch target value for all data types.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>stretchtargetstring</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>133</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>100</td><td>integer</td><td>undefined</td></tr></table>


### actualString

Actual Value of the goal.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Actual</td></tr><tr><td>description</td><td>Actual Value of the goal.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>actualstring</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Actual</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Actual Value of the goal.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>actualstring</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>134</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>100</td><td>integer</td><td>undefined</td></tr></table>


### customRollupFieldString

Placeholder rollup field for the goal.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Custom Rollup Field</td></tr><tr><td>description</td><td>Placeholder rollup field for the goal.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>customrollupfieldstring</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Custom Rollup Field</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Placeholder rollup field for the goal.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>customrollupfieldstring</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>135</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>100</td><td>integer</td><td>undefined</td></tr></table>


### inProgressString

In-progress value of the goal.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>In-Progress</td></tr><tr><td>description</td><td>In-progress value of the goal.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>inprogressstring</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>In-Progress</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>In-progress value of the goal.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>inprogressstring</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>136</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>100</td><td>integer</td><td>undefined</td></tr></table>


### amountDataType

Data type of the amount.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Amount Data Type</td></tr><tr><td>description</td><td>Data type of the amount.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>amountdatatype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td>[
  {
    "languageTag": "en",
    "displayText": "Money",
    "attributeValue": "0",
    "displayOrder": "0"
  },
  {
    "languageTag": "en",
    "displayText": "Decimal",
    "attributeValue": "1",
    "displayOrder": "1"
  },
  {
    "languageTag": "en",
    "displayText": "Integer",
    "attributeValue": "2",
    "displayOrder": "2"
  }
]</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### does.haveDefault

An attribute has a default value

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>attributeValue</th><th>displayOrder</th></tr><tr><td>en</td><td>Money</td><td>0</td><td>0</td></tr><tr><td>en</td><td>Decimal</td><td>1</td><td>1</td></tr><tr><td>en</td><td>Integer</td><td>2</td><td>2</td></tr></table>
</td><td>any</td><td>undefined</td></tr></table>


##### is.constrainedList

the values of an attribute are taken from or looked up from a fixed list of possibilities


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Amount Data Type</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Data type of the amount.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>amountdatatype</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>144</td><td>integer</td><td>undefined</td></tr></table>


### amountDataType_display

undefined

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### means.reference.displayText


##### is.readOnly


##### is.addedInSupportOf

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>inSupportOf</td><td>amountDataType</td><td>attributeName</td><td>output parameter naming the attribute that is being supported</td></tr></table>


### isAmount

Indicates whether the metric type is Count or Amount.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Metric Type</td></tr><tr><td>description</td><td>Indicates whether the metric type is Count or Amount.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isamount</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.boolean


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>required</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Metric Type</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates whether the metric type is Count or Amount.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>isamount</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>145</td><td>integer</td><td>undefined</td></tr></table>


### rollupQueryActualIntegerId

Choose the query that will be used to calculate the actual data for the goal (integer).

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Query - Actual(Integer)</td></tr><tr><td>description</td><td>Choose the query that will be used to calculate the actual data for the goal (integer).</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rollupqueryactualintegerid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rollup Query - Actual(Integer)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Choose the query that will be used to calculate the actual data for the goal (integer).</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>rollupqueryactualintegerid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>200</td><td>integer</td><td>undefined</td></tr></table>


### rollUpQueryActualMoneyId

Choose the query that will be used to calculate the actual data for the goal (money).

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Query - Actual(Money)</td></tr><tr><td>description</td><td>Choose the query that will be used to calculate the actual data for the goal (money).</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rollupqueryactualmoneyid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rollup Query - Actual(Money)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Choose the query that will be used to calculate the actual data for the goal (money).</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>rollupqueryactualmoneyid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>202</td><td>integer</td><td>undefined</td></tr></table>


### rollUpQueryActualDecimalId

Choose the query that will be used to calculate the actual data for the goal (decimal).

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Query - Actual(Decimal)</td></tr><tr><td>description</td><td>Choose the query that will be used to calculate the actual data for the goal (decimal).</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rollupqueryactualdecimalid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rollup Query - Actual(Decimal)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Choose the query that will be used to calculate the actual data for the goal (decimal).</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>rollupqueryactualdecimalid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>204</td><td>integer</td><td>undefined</td></tr></table>


### rollUpQueryCustomIntegerId

Choose the query that will be used to calculate data for the custom rollup field (integer).

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Query - Custom Rollup Field (Integer)</td></tr><tr><td>description</td><td>Choose the query that will be used to calculate data for the custom rollup field (integer).</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rollupquerycustomintegerid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rollup Query - Custom Rollup Field (Integer)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Choose the query that will be used to calculate data for the custom rollup field (integer).</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>rollupquerycustomintegerid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>206</td><td>integer</td><td>undefined</td></tr></table>


### rollUpQueryCustomMoneyId

Choose the query that will be used to calculate data for the custom rollup field (money).

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Query - Custom Rollup Field (Money)</td></tr><tr><td>description</td><td>Choose the query that will be used to calculate data for the custom rollup field (money).</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rollupquerycustommoneyid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rollup Query - Custom Rollup Field (Money)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Choose the query that will be used to calculate data for the custom rollup field (money).</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>rollupquerycustommoneyid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>208</td><td>integer</td><td>undefined</td></tr></table>


### rollUpQueryCustomDecimalId

Choose the query that will be used to calculate data for the custom rollup field (decimal).

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Query - Custom Rollup Field (Decimal)</td></tr><tr><td>description</td><td>Choose the query that will be used to calculate data for the custom rollup field (decimal).</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rollupquerycustomdecimalid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rollup Query - Custom Rollup Field (Decimal)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Choose the query that will be used to calculate data for the custom rollup field (decimal).</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>rollupquerycustomdecimalid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>210</td><td>integer</td><td>undefined</td></tr></table>


### rollUpQueryInprogressIntegerId

Choose the query that will be used to calculate data for the in-progress rollup field (integer).

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Query - In-progress(Integer)</td></tr><tr><td>description</td><td>Choose the query that will be used to calculate data for the in-progress rollup field (integer).</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rollupqueryinprogressintegerid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rollup Query - In-progress(Integer)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Choose the query that will be used to calculate data for the in-progress rollup field (integer).</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>rollupqueryinprogressintegerid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>212</td><td>integer</td><td>undefined</td></tr></table>


### rollUpQueryInprogressMoneyId

Choose the query that will be used to calculate data for the in-progress rollup field (money).

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Query - In-progress(Money)</td></tr><tr><td>description</td><td>Choose the query that will be used to calculate data for the in-progress rollup field (money).</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rollupqueryinprogressmoneyid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rollup Query - In-progress(Money)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Choose the query that will be used to calculate data for the in-progress rollup field (money).</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>rollupqueryinprogressmoneyid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>214</td><td>integer</td><td>undefined</td></tr></table>


### rollUpQueryInprogressDecimalId

Choose the query that will be used to calculate data for the in-progress rollup field (decimal).

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Query - In-progress(Decimal)</td></tr><tr><td>description</td><td>Choose the query that will be used to calculate data for the in-progress rollup field (decimal).</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rollupqueryinprogressdecimalid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rollup Query - In-progress(Decimal)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Choose the query that will be used to calculate data for the in-progress rollup field (decimal).</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>rollupqueryinprogressdecimalid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>216</td><td>integer</td><td>undefined</td></tr></table>


### rollupOnlyFromChildGoals

Select whether the data should be rolled up only from the child goals.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Roll Up Only from Child Goals</td></tr><tr><td>description</td><td>Select whether the data should be rolled up only from the child goals.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>false</td></tr><tr><td>sourceName</td><td>rolluponlyfromchildgoals</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.boolean


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>systemrequired</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Roll Up Only from Child Goals</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select whether the data should be rolled up only from the child goals.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>rolluponlyfromchildgoals</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>250</td><td>integer</td><td>undefined</td></tr></table>


### goalWithErrorId

Unique identifier of the goal that caused an error in the rollup of the goal hierarchy.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Goal With Error</td></tr><tr><td>description</td><td>Unique identifier of the goal that caused an error in the rollup of the goal hierarchy.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>goalwitherrorid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### means.identity.entityId


##### is.CDS.lookup

The attribute represents a style of lookup in CDS for Applications

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>style</td><td>single</td><td>string</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Goal With Error</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier of the goal that caused an error in the rollup of the goal hierarchy.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>goalwitherrorid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>252</td><td>integer</td><td>undefined</td></tr></table>


##### does.referenceEntity

turns all attributes from an entity into one key valued attribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>addedAttribute</td><td>{
  "relationship": "hasA",
  "dataType": "entityI...(see Definition below)</td><td>attribute</td><td>an attribute definition should be passed for this argument. the attribute will be added to the entity instead of the default one.</td></tr></table>

Definition:

```
{
  "relationship": "hasA",
  "dataType": "entityId",
  "name": "goalWithErrorId",
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
                "Goal With Error"
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
                "Unique identifier of the goal that caused an error in the rollup of the goal hierarchy."
              ]
            ]
          }
        }
      ]
    }
  ],
  "displayName": "Goal With Error",
  "description": "Unique identifier of the goal that caused an error in the rollup of the goal hierarchy.",
  "isNullable": true,
  "sourceName": "goalwitherrorid",
  "sourceOrdering": 252
}
```

### rollupErrorCode

Error code associated with rollup.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Rollup Error Code</td></tr><tr><td>description</td><td>Error code associated with rollup.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>rolluperrorcode</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Rollup Error Code</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Error code associated with rollup.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>rolluperrorcode</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>254</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-2147483648</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### computedTargetAsOfTodayPercentageAchieved

Shows the expected value for percentage achieved against the target goal as of the current date.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Today's Target (Percentage Achieved)</td></tr><tr><td>description</td><td>Shows the expected value for percentage achieved against the target goal as of the current date.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>computedtargetasoftodaypercentageachieved</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Today's Target (Percentage Achieved)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the expected value for percentage achieved against the target goal as of the current date.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>computedtargetasoftodaypercentageachieved</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>256</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>100000000000</td><td>decimal</td><td>undefined</td></tr></table>


### computedTargetAsOfTodayMoney

Shows the expected amount for actual value (money type) against the target goal as of the current date.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Today's Target (Money)</td></tr><tr><td>description</td><td>Shows the expected amount for actual value (money type) against the target goal as of the current date.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>computedtargetasoftodaymoney</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### means.measurement.currency


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Today's Target (Money)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the expected amount for actual value (money type) against the target goal as of the current date.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>computedtargetasoftodaymoney</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>257</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td>undefined</td></tr></table>


### computedTargetAsOfTodayMoneyBase

Shows the expected amount in base currency for actual value (money type) against the target goal as of the current date.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Today's Target (Money) (Base)</td></tr><tr><td>description</td><td>Shows the expected amount in base currency for actual value (money type) against the target goal as of the current date.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>922337203685477</td></tr><tr><td>minimumValue</td><td>-922337203685477</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>computedtargetasoftodaymoney_base</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### means.measurement.currency


##### is.calculationOf

the attribute value is the result of a calculation on the sourceAttribute

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>sourceAttribute</td><td>computedTargetAsOfTodayMoney</td><td>attributeName</td><td>undefined</td></tr></table>


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Today's Target (Money) (Base)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the expected amount in base currency for actual value (money type) against the target goal as of the current date.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>computedtargetasoftodaymoney_base</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>258</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>-922337203685477</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>922337203685477</td><td>decimal</td><td>undefined</td></tr></table>


### computedTargetAsOfTodayDecimal

Shows the expected amount for actual value (decimal type) against the target goal.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Today's Target (Decimal)</td></tr><tr><td>description</td><td>Shows the expected amount for actual value (decimal type) against the target goal.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>computedtargetasoftodaydecimal</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.numeric.shaped

for setting the exact precision and scale of numeric values


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Today's Target (Decimal)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the expected amount for actual value (decimal type) against the target goal.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>computedtargetasoftodaydecimal</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>259</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>100000000000</td><td>decimal</td><td>undefined</td></tr></table>


### computedTargetAsOfTodayInteger

Shows the expected amount for actual value (integer type) against the target goal as of the current date.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Today's Target (Integer)</td></tr><tr><td>description</td><td>Shows the expected amount for actual value (integer type) against the target goal as of the current date.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>computedtargetasoftodayinteger</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.integer


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Today's Target (Integer)</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Shows the expected amount for actual value (integer type) against the target goal as of the current date.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>computedtargetasoftodayinteger</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>260</td><td>integer</td><td>undefined</td></tr></table>


##### is.constrained

maximum length or value constraints

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>0</td><td>decimal</td><td>undefined</td></tr><tr><td>maximumValue</td><td>2147483647</td><td>decimal</td><td>undefined</td></tr></table>


### isOverride

Indicates whether the values of system rollup fields can be updated.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Override</td></tr><tr><td>description</td><td>Indicates whether the values of system rollup fields can be updated.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isoverride</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.boolean


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Override</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates whether the values of system rollup fields can be updated.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>isoverride</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>261</td><td>integer</td><td>undefined</td></tr></table>


### isOverridden

Select whether the system rollup fields are updated. If set to Yes, the next system rollup will not update the values of the rollup fields with the system calculated values.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Overridden</td></tr><tr><td>description</td><td>Select whether the system rollup fields are updated. If set to Yes, the next system rollup will not update the values of the rollup fields with the system calculated values.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Boolean</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>isoverridden</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.boolean


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Overridden</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Select whether the system rollup fields are updated. If set to Yes, the next system rollup will not update the values of the rollup fields with the system calculated values.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>isoverridden</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>262</td><td>integer</td><td>undefined</td></tr></table>


### entityImageId

For internal use only.

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Entity Image Id</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>isPrimaryKey</td><td>false</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>isReadOnly</td><td>false</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>entityimageid</td></tr><tr><td>valueConstrainedToList</td><td>false</td></tr></table>

#### Traits

##### is.dataFormat.character


##### is.dataFormat.big


##### is.dataFormat.array


##### is.dataFormat.guid


##### is.requiredAtLevel

The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>level</td><td>none</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>


##### is.localized.displayedAs

Holds the list of language specific display text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Entity Image Id</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.localized.describedAs

Holds the list of language specific descriptive text for an object.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table>
</td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>


##### is.nullable

The attribute value may be set to NULL.


##### is.CDS.sourceNamed

the unique name that identifies this object in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>name</td><td>entityimageid</td><td>string</td><td>undefined</td></tr></table>


##### is.CDS.ordered

the column number for an attribute with an entity in CDS for Applications.

<table><tr><th>Parameter</th><th>Value</th><th>Data Type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>265</td><td>integer</td><td>undefined</td></tr></table>



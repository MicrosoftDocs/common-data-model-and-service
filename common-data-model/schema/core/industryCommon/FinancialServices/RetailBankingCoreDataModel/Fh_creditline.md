---
title: FHLineOfCredit in RetailBankingCoreDataModel - Common Data Model | Microsoft Docs
description: A preset borrowing limit associated with a credit or charge card.
author: cdm-publisher
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 4/5/2023
ms.author: cdmditeam
---

# FH line of credit in RetailBankingCoreDataModel(FHLineOfCredit)

A preset borrowing limit associated with a credit or charge card.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/FinancialServices/RetailBankingCoreDataModel/Fh_creditline.cdm.json" target="_blank">GitHub</a>.  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

**is.CDM.entityVersion**  
    <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>"1.1"</td><td>string</td><td>semantic version number of the entity</td></tr></table>

**is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FHLineOfCredit/(resolvedAttributes)/FH_CreditlineId](#FH_CreditlineId)</td><td>attribute</td><td></td></tr></table>

**means.entityState**  
  the attribute represents the current state of the entity.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FHLineOfCredit/(resolvedAttributes)/statecode](#statecode)</td><td>attribute</td><td></td></tr></table>

**is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>A preset borrowing limit associated with a credit or charge card.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>FH line of credit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

**is.CDS.sourceNamed**  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_fh_creditline"</td><td>string</td><td></td></tr></table>

**has.entitySchemaAbstractionLevel**  
  A level of abstraction assigned to an Entity schema. Logical schema descriptions use complex dataTypes, inheritance, and entities as attributes. Resolved descriptions contain none of those things, only final trait and attribute sets are shown. A composition schema manipulates, guides or re-states parts of logical schemas to produce one resolved schema.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"resolved"</td><td>string</td><td>Possible values: logical, composition, resolved</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[FH_CreditlineId](#FH_CreditlineId)|Unique identifier for entity instances.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[statecode](#statecode)|Status of the FH Creditline.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[statuscode](#statuscode)|Reason for the status of the FH Creditline.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[name](#name)|Required name field.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[accountingClassification](#accountingClassification)|Indicates whether the financial holding is an asset or a liability.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[balance](#balance)|The balance or value of the financial holding in the original currency of the financial holding.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[balance_Base](#balance_Base)|Value of the balance in base currency.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[balanceDefault](#balanceDefault)|Balance converted to default currency of the system.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[balanceExchangerate](#balanceExchangerate)|Exchange rate between the transaction currency of the financial holding and the default currency \(1 unit of transaction currency = X units of default currency\).|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[creditLimit](#creditLimit)|The total credit limit available to the customer on the credit card.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[creditlimit_Base](#creditlimit_Base)|Value of the credit limit in base currency.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[creditLimit_default](#creditLimit_default)|Credit limit converted to default currency of the system.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[delinquencyStatus](#delinquencyStatus)|Indication of whether the customer's loan is delinquent or not \(i.e. whether any payments are overdue or not\).|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[financialHoldingCategory](#financialHoldingCategory)|The category of the financial holding \(Accounts, Long\x2dterm savings, Investments, Loans and Lines or credit\).|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[financialHoldingType](#financialHoldingType)|Subtypes under Financial Category.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[integrationKey](#integrationKey)|Used by the system integrator to uniquely define the data record .|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[interestrate](#interestrate)|The rate of interest associated with the line of credit, to be charged to the customer during a defined period/term. |<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[lastPaymentDueDate](#lastPaymentDueDate)|The date on which the last payment was due on the credit balance.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[lastStatementBalance](#lastStatementBalance)|The total amount due on the card per the last statement.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[laststatementbalance_Base](#laststatementbalance_Base)|Value of the last statement balance in base currency.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[lastStatementBalance_default](#lastStatementBalance_default)|Last statement balance converted to default currency of the system.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[lastStatementDate](#lastStatementDate)|The date on which the last statement was issued on the card.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[minimumPaymentDue](#minimumPaymentDue)|The minimum amount that is required for payment towards the card based on the monthly payment percentage of the outstanding balance.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[minimumpaymentdue_Base](#minimumpaymentdue_Base)|Value of the minimum payment due in base currency.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[minimumPaymentDue_default](#minimumPaymentDue_default)|Minimum payment due converted to default currency of the system.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[monthlyPaymentPercentage](#monthlyPaymentPercentage)|The percentage of the outstanding balance that must be paid by the customer as the 'minimum payment' by the next payment date.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[nextPaymentDate](#nextPaymentDate)|The date on which the next payment towards the financial holding is due. This can be applied to lines of credit and loans.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[nextStatementDate](#nextStatementDate)|The date on which the next statement is expected to issue on the card.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[balanceDefaultDisplayValue](#balanceDefaultDisplayValue)||<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[balanceDisplayValue](#balanceDisplayValue)|Display value shows the balance of a financial holding in accordance with the type of the financial holding. Financial holdings that are typically defined as a customer's liabilities \(such as lines of credit and loans\) are presented as positive when the customer owes money to the financial institution \(that is, a loan with an accounting value of \x2d500 will appear as 500\). In the inverse case: the display value will be negative for debit balances on a credit financial holding \(such as overpayment of a credit card\), or overdrawn account.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|
|[balancedisplayvalue_Base](#balancedisplayvalue_Base)|Value of the balance display value in base currency.|<a href="Fh_creditline.md" target="_blank">RetailBankingCoreDataModel/Fh_creditline</a>|

### <a href=#FH_CreditlineId name="FH_CreditlineId">FH_CreditlineId</a>

Unique identifier for entity instances.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>FH creditline</td></tr><tr><td>description</td><td>Unique identifier for entity instances.</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>guid</td></tr><tr><td>sourceName</td><td>msfsi_fh_creditlineid</td></tr></table>

#### Traits

<details>
<summary>List of traits for the FH_CreditlineId attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.dataFormat.guid\*\*  
  \*\*means.identity.entityId\*\*  
  \*\*is.identifiedBy\*\*  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FHLineOfCredit/(resolvedAttributes)/FH_CreditlineId](#FH_CreditlineId)</td><td>attribute</td><td></td></tr></table>

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Unique identifier for entity instances.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>FH creditline</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_fh_creditlineid"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"1"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.guid\*\*  
  \*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the createdOn attribute are listed below.</summary>

\*\*is.dataFormat.date\*\*  
  \*\*means.measurement.date\*\*  
  \*\*is.dataFormat.time\*\*  
  \*\*means.measurement.time\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"createdon"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"2"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.time\*\*  
  \*\*is.dataFormat.date\*\*  
  </details>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the modifiedOn attribute are listed below.</summary>

\*\*is.dataFormat.date\*\*  
  \*\*means.measurement.date\*\*  
  \*\*is.dataFormat.time\*\*  
  \*\*means.measurement.time\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time when the record was modified.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Modified On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"modifiedon"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"4"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.time\*\*  
  \*\*is.dataFormat.date\*\*  
  </details>

### <a href=#statecode name="statecode">statecode</a>

Status of the FH Creditline.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the FH Creditline.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the statecode attribute are listed below.</summary>

\*\*is.dataFormat.integer\*\*  
  \*\*is.dataFormat.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is.dataFormat.numeric\*\*  
  \*\*does.haveDefault\*\*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td><td>any</td><td></td></tr></table>

\*\*is.constrainedList\*\*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

\*\*means.entityState\*\*  
  the attribute represents the current state of the entity.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FHLineOfCredit/(resolvedAttributes)/statecode](#statecode)</td><td>attribute</td><td></td></tr></table>

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"systemrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status of the FH Creditline.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"statecode"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"25"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.integer\*\*  
  </details>

### <a href=#statuscode name="statuscode">statuscode</a>

Reason for the status of the FH Creditline.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the FH Creditline.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>1</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>2</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the statuscode attribute are listed below.</summary>

\*\*is.dataFormat.integer\*\*  
  \*\*is.dataFormat.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is.dataFormat.numeric\*\*  
  \*\*does.haveDefault\*\*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>1</td></tr><tr><td>en</td><td>Inactive</td><td>2</td><td>2</td></tr></table></td><td>any</td><td></td></tr></table>

\*\*is.constrainedList\*\*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

\*\*is.correlatedWith\*\*  
  the attribute value is correlated with the sourceAttribute  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>sourceAttribute</td><td>"statecode"</td><td>attributeName</td><td></td></tr></table>

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Reason for the status of the FH Creditline.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Status Reason</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"statuscode"</td><td>string</td><td></td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"27"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.integer\*\*  
  </details>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the importSequenceNumber attribute are listed below.</summary>

\*\*is.dataFormat.integer\*\*  
  \*\*is.dataFormat.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is.dataFormat.numeric\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Sequence number of the import that created this record.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Import Sequence Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-2147483648"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"importsequencenumber"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"30"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.integer\*\*  
  </details>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

#### Traits

<details>
<summary>List of traits for the overriddenCreatedOn attribute are listed below.</summary>

\*\*is.dataFormat.date\*\*  
  \*\*means.measurement.date\*\*  
  \*\*is.dataFormat.time\*\*  
  \*\*means.measurement.time\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Date and time that the record was migrated.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Record Created On</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"overriddencreatedon"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"31"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.time\*\*  
  \*\*is.dataFormat.date\*\*  
  </details>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

#### Traits

<details>
<summary>List of traits for the timeZoneRuleVersionNumber attribute are listed below.</summary>

\*\*is.dataFormat.integer\*\*  
  \*\*is.dataFormat.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is.dataFormat.numeric\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>For internal use only.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time Zone Rule Version Number</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"timezoneruleversionnumber"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"32"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.integer\*\*  
  </details>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>

#### Traits

<details>
<summary>List of traits for the UTCConversionTimeZoneCode attribute are listed below.</summary>

\*\*is.dataFormat.integer\*\*  
  \*\*is.dataFormat.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is.dataFormat.numeric\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Time zone code that was in use when the record was created.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>UTC Conversion Time Zone Code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-1"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"2147483647"</td><td>decimal</td><td></td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"utcconversiontimezonecode"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"33"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.integer\*\*  
  </details>

### <a href=#name name="name">name</a>

Required name field.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Required name field.</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_name</td></tr></table>

#### Traits

<details>
<summary>List of traits for the name attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Required name field.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Name</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_name"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"34"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#accountingClassification name="accountingClassification">accountingClassification</a>

Indicates whether the financial holding is an asset or a liability.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Accounting classification</td></tr><tr><td>description</td><td>Indicates whether the financial holding is an asset or a liability.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_accountingclassification</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Asset</td><td>1</td></tr><tr><td>en</td><td>Liability</td><td>2</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the accountingClassification attribute are listed below.</summary>

\*\*is.dataFormat.integer\*\*  
  \*\*is.dataFormat.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is.dataFormat.numeric\*\*  
  \*\*does.haveDefault\*\*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Asset</td><td>1</td></tr><tr><td>en</td><td>Liability</td><td>2</td></tr></table></td><td>any</td><td></td></tr></table>

\*\*is.constrainedList\*\*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indicates whether the financial holding is an asset or a liability.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Accounting classification</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_accountingclassification"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"35"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.integer\*\*  
  </details>

### <a href=#balance name="balance">balance</a>

The balance or value of the financial holding in the original currency of the financial holding.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Balance</td></tr><tr><td>description</td><td>The balance or value of the financial holding in the original currency of the financial holding.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_balance</td></tr></table>

#### Traits

<details>
<summary>List of traits for the balance attribute are listed below.</summary>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>precision</td><td>"19"</td><td>integer</td><td>the total number of significant digits</td></tr><tr><td>scale</td><td>"4"</td><td>integer</td><td>the number of digits to the right of the decimal place</td></tr></table>

\*\*means.measurement.currency\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The balance or value of the financial holding in the original currency of the financial holding.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Balance</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_balance"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"37"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#balance_Base name="balance_Base">balance_Base</a>

Value of the balance in base currency.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Balance (base)</td></tr><tr><td>description</td><td>Value of the balance in base currency.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_balance_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the balance_Base attribute are listed below.</summary>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>precision</td><td>"19"</td><td>integer</td><td>the total number of significant digits</td></tr><tr><td>scale</td><td>"4"</td><td>integer</td><td>the number of digits to the right of the decimal place</td></tr></table>

\*\*means.measurement.currency\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the balance in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Balance (base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_balance_base"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"41"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#balanceDefault name="balanceDefault">balanceDefault</a>

Balance converted to default currency of the system.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Balance (default)</td></tr><tr><td>description</td><td>Balance converted to default currency of the system.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_balancedefault</td></tr></table>

#### Traits

<details>
<summary>List of traits for the balanceDefault attribute are listed below.</summary>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Balance converted to default currency of the system.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Balance (default)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-100000000000"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_balancedefault"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"42"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#balanceExchangerate name="balanceExchangerate">balanceExchangerate</a>

Exchange rate between the transaction currency of the financial holding and the default currency \(1 unit of transaction currency = X units of default currency\).  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Balance exchange rate</td></tr><tr><td>description</td><td>Exchange rate between the transaction currency of the financial holding and the default currency (1 unit of transaction currency = X units of default currency).</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_balanceexchangerate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the balanceExchangerate attribute are listed below.</summary>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Exchange rate between the transaction currency of the financial holding and the default currency (1 unit of transaction currency = X units of default currency).</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Balance exchange rate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-100000000000"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_balanceexchangerate"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"43"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#creditLimit name="creditLimit">creditLimit</a>

The total credit limit available to the customer on the credit card.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit limit</td></tr><tr><td>description</td><td>The total credit limit available to the customer on the credit card.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_creditlimit</td></tr></table>

#### Traits

<details>
<summary>List of traits for the creditLimit attribute are listed below.</summary>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>precision</td><td>"19"</td><td>integer</td><td>the total number of significant digits</td></tr><tr><td>scale</td><td>"4"</td><td>integer</td><td>the number of digits to the right of the decimal place</td></tr></table>

\*\*means.measurement.currency\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The total credit limit available to the customer on the credit card.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Credit limit</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_creditlimit"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"44"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#creditlimit_Base name="creditlimit_Base">creditlimit_Base</a>

Value of the credit limit in base currency.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit limit (base)</td></tr><tr><td>description</td><td>Value of the credit limit in base currency.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_creditlimit_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the creditlimit_Base attribute are listed below.</summary>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>precision</td><td>"19"</td><td>integer</td><td>the total number of significant digits</td></tr><tr><td>scale</td><td>"4"</td><td>integer</td><td>the number of digits to the right of the decimal place</td></tr></table>

\*\*means.measurement.currency\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the credit limit in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Credit limit (base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_creditlimit_base"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"45"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#creditLimit_default name="creditLimit_default">creditLimit_default</a>

Credit limit converted to default currency of the system.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Credit limit (default)</td></tr><tr><td>description</td><td>Credit limit converted to default currency of the system.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_creditlimit_default</td></tr></table>

#### Traits

<details>
<summary>List of traits for the creditLimit_default attribute are listed below.</summary>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Credit limit converted to default currency of the system.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Credit limit (default)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-100000000000"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_creditlimit_default"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"46"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#delinquencyStatus name="delinquencyStatus">delinquencyStatus</a>

Indication of whether the customer's loan is delinquent or not \(i.e. whether any payments are overdue or not\).  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Delinquency status</td></tr><tr><td>description</td><td>Indication of whether the customer's loan is delinquent or not (i.e. whether any payments are overdue or not).</td></tr><tr><td>dataFormat</td><td>boolean</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_delinquencystatus</td></tr></table>

#### Traits

<details>
<summary>List of traits for the delinquencyStatus attribute are listed below.</summary>

\*\*is.dataFormat.boolean\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Indication of whether the customer's loan is delinquent or not (i.e. whether any payments are overdue or not).</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Delinquency status</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_delinquencystatus"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"47"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.boolean\*\*  
  </details>

### <a href=#financialHoldingCategory name="financialHoldingCategory">financialHoldingCategory</a>

The category of the financial holding \(Accounts, Long\x2dterm savings, Investments, Loans and Lines or credit\).  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Financial holding category</td></tr><tr><td>description</td><td>The category of the financial holding (Accounts, Long-term savings, Investments, Loans and Lines or credit).</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_financialholdingcategory</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Lines of credit</td><td>104800000</td></tr><tr><td>en</td><td>Loans</td><td>104800001</td></tr><tr><td>en</td><td>Investments</td><td>104800002</td></tr><tr><td>en</td><td>Long-term savings</td><td>104800003</td></tr><tr><td>en</td><td>Accounts</td><td>104800004</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the financialHoldingCategory attribute are listed below.</summary>

\*\*is.dataFormat.integer\*\*  
  \*\*is.dataFormat.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is.dataFormat.numeric\*\*  
  \*\*does.haveDefault\*\*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Lines of credit</td><td>104800000</td></tr><tr><td>en</td><td>Loans</td><td>104800001</td></tr><tr><td>en</td><td>Investments</td><td>104800002</td></tr><tr><td>en</td><td>Long-term savings</td><td>104800003</td></tr><tr><td>en</td><td>Accounts</td><td>104800004</td></tr></table></td><td>any</td><td></td></tr></table>

\*\*is.constrainedList\*\*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The category of the financial holding (Accounts, Long-term savings, Investments, Loans and Lines or credit).</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Financial holding category</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_financialholdingcategory"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"49"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.integer\*\*  
  </details>

### <a href=#financialHoldingType name="financialHoldingType">financialHoldingType</a>

Subtypes under Financial Category.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Financial holding type</td></tr><tr><td>description</td><td>Subtypes under Financial Category.</td></tr><tr><td>dataFormat</td><td>int32</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_financialholdingtype</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Revolving</td><td>104800013</td></tr><tr><td>en</td><td>Non-revolving</td><td>104800014</td></tr><tr><td>en</td><td>Other</td><td>104800201</td></tr></table></td></tr></table>

#### Traits

<details>
<summary>List of traits for the financialHoldingType attribute are listed below.</summary>

\*\*is.dataFormat.integer\*\*  
  \*\*is.dataFormat.signed\*\*  
  indicates the capability to represent values less than zero.  

\*\*is.dataFormat.numeric\*\*  
  \*\*does.haveDefault\*\*  
  An attribute has a default value  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>default</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Revolving</td><td>104800013</td></tr><tr><td>en</td><td>Non-revolving</td><td>104800014</td></tr><tr><td>en</td><td>Other</td><td>104800201</td></tr></table></td><td>any</td><td></td></tr></table>

\*\*is.constrainedList\*\*  
  the values of an attribute are taken from or looked up from a fixed list of possibilities  

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Subtypes under Financial Category.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Financial holding type</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_financialholdingtype"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"51"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.integer\*\*  
  </details>

### <a href=#integrationKey name="integrationKey">integrationKey</a>

Used by the system integrator to uniquely define the data record .  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Integration key</td></tr><tr><td>description</td><td>Used by the system integrator to uniquely define the data record .</td></tr><tr><td>dataFormat</td><td>string</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_integrationkey</td></tr></table>

#### Traits

<details>
<summary>List of traits for the integrationKey attribute are listed below.</summary>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.big\*\*  
  indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.  

\*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"applicationrequired"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Used by the system integrator to uniquely define the data record .</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Integration key</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>maximumLength</td><td>"100"</td><td>integer</td><td></td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_integrationkey"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"53"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.character\*\*  
  \*\*is.dataFormat.array\*\*  
  indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object  

</details>

### <a href=#interestrate name="interestrate">interestrate</a>

The rate of interest associated with the line of credit, to be charged to the customer during a defined period/term.   
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Interest rate</td></tr><tr><td>description</td><td>The rate of interest associated with the line of credit, to be charged to the customer during a defined period/term. </td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_interestrate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the interestrate attribute are listed below.</summary>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The rate of interest associated with the line of credit, to be charged to the customer during a defined period/term. </td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Interest rate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-100000000000"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_interestrate"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"54"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#lastPaymentDueDate name="lastPaymentDueDate">lastPaymentDueDate</a>

The date on which the last payment was due on the credit balance.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last payment due date</td></tr><tr><td>description</td><td>The date on which the last payment was due on the credit balance.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_lastpaymentduedate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the lastPaymentDueDate attribute are listed below.</summary>

\*\*is.dataFormat.date\*\*  
  \*\*means.measurement.date\*\*  
  \*\*is.dataFormat.time\*\*  
  \*\*means.measurement.time\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The date on which the last payment was due on the credit balance.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Last payment due date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_lastpaymentduedate"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"55"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.time\*\*  
  \*\*is.dataFormat.date\*\*  
  </details>

### <a href=#lastStatementBalance name="lastStatementBalance">lastStatementBalance</a>

The total amount due on the card per the last statement.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last statement balance</td></tr><tr><td>description</td><td>The total amount due on the card per the last statement.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_laststatementbalance</td></tr></table>

#### Traits

<details>
<summary>List of traits for the lastStatementBalance attribute are listed below.</summary>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>precision</td><td>"19"</td><td>integer</td><td>the total number of significant digits</td></tr><tr><td>scale</td><td>"4"</td><td>integer</td><td>the number of digits to the right of the decimal place</td></tr></table>

\*\*means.measurement.currency\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The total amount due on the card per the last statement.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Last statement balance</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_laststatementbalance"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"56"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#laststatementbalance_Base name="laststatementbalance_Base">laststatementbalance_Base</a>

Value of the last statement balance in base currency.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last statement balance (base)</td></tr><tr><td>description</td><td>Value of the last statement balance in base currency.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_laststatementbalance_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the laststatementbalance_Base attribute are listed below.</summary>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>precision</td><td>"19"</td><td>integer</td><td>the total number of significant digits</td></tr><tr><td>scale</td><td>"4"</td><td>integer</td><td>the number of digits to the right of the decimal place</td></tr></table>

\*\*means.measurement.currency\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the last statement balance in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Last statement balance (base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_laststatementbalance_base"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"57"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#lastStatementBalance_default name="lastStatementBalance_default">lastStatementBalance_default</a>

Last statement balance converted to default currency of the system.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last statement balance (default)</td></tr><tr><td>description</td><td>Last statement balance converted to default currency of the system.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_laststatementbalance_default</td></tr></table>

#### Traits

<details>
<summary>List of traits for the lastStatementBalance_default attribute are listed below.</summary>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Last statement balance converted to default currency of the system.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Last statement balance (default)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-100000000000"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_laststatementbalance_default"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"58"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#lastStatementDate name="lastStatementDate">lastStatementDate</a>

The date on which the last statement was issued on the card.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Last statement date</td></tr><tr><td>description</td><td>The date on which the last statement was issued on the card.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_laststatementdate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the lastStatementDate attribute are listed below.</summary>

\*\*is.dataFormat.date\*\*  
  \*\*means.measurement.date\*\*  
  \*\*is.dataFormat.time\*\*  
  \*\*means.measurement.time\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The date on which the last statement was issued on the card.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Last statement date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_laststatementdate"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"59"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.time\*\*  
  \*\*is.dataFormat.date\*\*  
  </details>

### <a href=#minimumPaymentDue name="minimumPaymentDue">minimumPaymentDue</a>

The minimum amount that is required for payment towards the card based on the monthly payment percentage of the outstanding balance.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Minimum payment due</td></tr><tr><td>description</td><td>The minimum amount that is required for payment towards the card based on the monthly payment percentage of the outstanding balance.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_minimumpaymentdue</td></tr></table>

#### Traits

<details>
<summary>List of traits for the minimumPaymentDue attribute are listed below.</summary>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>precision</td><td>"19"</td><td>integer</td><td>the total number of significant digits</td></tr><tr><td>scale</td><td>"4"</td><td>integer</td><td>the number of digits to the right of the decimal place</td></tr></table>

\*\*means.measurement.currency\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The minimum amount that is required for payment towards the card based on the monthly payment percentage of the outstanding balance.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Minimum payment due</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_minimumpaymentdue"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"60"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#minimumpaymentdue_Base name="minimumpaymentdue_Base">minimumpaymentdue_Base</a>

Value of the minimum payment due in base currency.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Minimum payment due (base)</td></tr><tr><td>description</td><td>Value of the minimum payment due in base currency.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_minimumpaymentdue_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the minimumpaymentdue_Base attribute are listed below.</summary>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>precision</td><td>"19"</td><td>integer</td><td>the total number of significant digits</td></tr><tr><td>scale</td><td>"4"</td><td>integer</td><td>the number of digits to the right of the decimal place</td></tr></table>

\*\*means.measurement.currency\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the minimum payment due in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Minimum payment due (base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_minimumpaymentdue_base"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"61"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#minimumPaymentDue_default name="minimumPaymentDue_default">minimumPaymentDue_default</a>

Minimum payment due converted to default currency of the system.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Minimum payment due (default)</td></tr><tr><td>description</td><td>Minimum payment due converted to default currency of the system.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_minimumpaymentdue_default</td></tr></table>

#### Traits

<details>
<summary>List of traits for the minimumPaymentDue_default attribute are listed below.</summary>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Minimum payment due converted to default currency of the system.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Minimum payment due (default)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-100000000000"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_minimumpaymentdue_default"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"62"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#monthlyPaymentPercentage name="monthlyPaymentPercentage">monthlyPaymentPercentage</a>

The percentage of the outstanding balance that must be paid by the customer as the 'minimum payment' by the next payment date.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Monthly payment percentage</td></tr><tr><td>description</td><td>The percentage of the outstanding balance that must be paid by the customer as the 'minimum payment' by the next payment date.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_monthlypaymentpercentage</td></tr></table>

#### Traits

<details>
<summary>List of traits for the monthlyPaymentPercentage attribute are listed below.</summary>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The percentage of the outstanding balance that must be paid by the customer as the 'minimum payment' by the next payment date.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Monthly payment percentage</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-100000000000"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_monthlypaymentpercentage"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"63"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#nextPaymentDate name="nextPaymentDate">nextPaymentDate</a>

The date on which the next payment towards the financial holding is due. This can be applied to lines of credit and loans.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Next payment date</td></tr><tr><td>description</td><td>The date on which the next payment towards the financial holding is due. This can be applied to lines of credit and loans.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_nextpaymentdate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the nextPaymentDate attribute are listed below.</summary>

\*\*is.dataFormat.date\*\*  
  \*\*means.measurement.date\*\*  
  \*\*is.dataFormat.time\*\*  
  \*\*means.measurement.time\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The date on which the next payment towards the financial holding is due. This can be applied to lines of credit and loans.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Next payment date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_nextpaymentdate"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"64"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.time\*\*  
  \*\*is.dataFormat.date\*\*  
  </details>

### <a href=#nextStatementDate name="nextStatementDate">nextStatementDate</a>

The date on which the next statement is expected to issue on the card.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Next statement date</td></tr><tr><td>description</td><td>The date on which the next statement is expected to issue on the card.</td></tr><tr><td>dataFormat</td><td>dateTime</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_nextstatementdate</td></tr></table>

#### Traits

<details>
<summary>List of traits for the nextStatementDate attribute are listed below.</summary>

\*\*is.dataFormat.date\*\*  
  \*\*means.measurement.date\*\*  
  \*\*is.dataFormat.time\*\*  
  \*\*means.measurement.time\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The date on which the next statement is expected to issue on the card.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Next statement date</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_nextstatementdate"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"65"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.time\*\*  
  \*\*is.dataFormat.date\*\*  
  </details>

### <a href=#balanceDefaultDisplayValue name="balanceDefaultDisplayValue">balanceDefaultDisplayValue</a>

First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Balance (default) display value</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>maximumValue</td><td>100000000000</td></tr><tr><td>minimumValue</td><td>-100000000000</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_balancedefaultdisplayvalue</td></tr></table>

#### Traits

<details>
<summary>List of traits for the balanceDefaultDisplayValue attribute are listed below.</summary>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

\*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td></td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Balance (default) display value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.constrained\*\*  
  maximum length or value constraints  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>minimumValue</td><td>"-100000000000"</td><td>decimal</td><td></td></tr><tr><td>maximumValue</td><td>"100000000000"</td><td>decimal</td><td></td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_balancedefaultdisplayvalue"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"66"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#balanceDisplayValue name="balanceDisplayValue">balanceDisplayValue</a>

Display value shows the balance of a financial holding in accordance with the type of the financial holding. Financial holdings that are typically defined as a customer's liabilities \(such as lines of credit and loans\) are presented as positive when the customer owes money to the financial institution \(that is, a loan with an accounting value of \x2d500 will appear as 500\). In the inverse case: the display value will be negative for debit balances on a credit financial holding \(such as overpayment of a credit card\), or overdrawn account.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Balance display value</td></tr><tr><td>description</td><td>Display value shows the balance of a financial holding in accordance with the type of the financial holding. Financial holdings that are typically defined as a customer's liabilities (such as lines of credit and loans) are presented as positive when the customer owes money to the financial institution (that is, a loan with an accounting value of -500 will appear as 500). In the inverse case: the display value will be negative for debit balances on a credit financial holding (such as overpayment of a credit card), or overdrawn account.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_balancedisplayvalue</td></tr></table>

#### Traits

<details>
<summary>List of traits for the balanceDisplayValue attribute are listed below.</summary>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>precision</td><td>"19"</td><td>integer</td><td>the total number of significant digits</td></tr><tr><td>scale</td><td>"4"</td><td>integer</td><td>the number of digits to the right of the decimal place</td></tr></table>

\*\*means.measurement.currency\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Display value shows the balance of a financial holding in accordance with the type of the financial holding. Financial holdings that are typically defined as a customer's liabilities (such as lines of credit and loans) are presented as positive when the customer owes money to the financial institution (that is, a loan with an accounting value of -500 will appear as 500). In the inverse case: the display value will be negative for debit balances on a credit financial holding (such as overpayment of a credit card), or overdrawn account.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Balance display value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_balancedisplayvalue"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"67"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

### <a href=#balancedisplayvalue_Base name="balancedisplayvalue_Base">balancedisplayvalue_Base</a>

Value of the balance display value in base currency.  
First included in: RetailBankingCoreDataModel/Fh_creditline \(this entity\)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Balance display value (base)</td></tr><tr><td>description</td><td>Value of the balance display value in base currency.</td></tr><tr><td>dataFormat</td><td>decimal</td></tr><tr><td>isNullable</td><td>true</td></tr><tr><td>sourceName</td><td>msfsi_balancedisplayvalue_base</td></tr></table>

#### Traits

<details>
<summary>List of traits for the balancedisplayvalue_Base attribute are listed below.</summary>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>precision</td><td>"19"</td><td>integer</td><td>the total number of significant digits</td></tr><tr><td>scale</td><td>"4"</td><td>integer</td><td>the number of digits to the right of the decimal place</td></tr></table>

\*\*means.measurement.currency\*\*  
  \*\*is.requiredAtLevel\*\*  
  The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>level</td><td>"none"</td><td>string</td><td>values can be: 'systemrequired', 'required', 'recommended', 'none'</td></tr></table>

\*\*is.localized.describedAs\*\*  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Value of the balance display value in base currency.</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.localized.displayedAs\*\*  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Balance display value (base)</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

\*\*is.nullable\*\*  
  The attribute value may be set to NULL.  

\*\*is.CDS.sourceNamed\*\*  
  the unique name that identifies this object in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>name</td><td>"msfsi_balancedisplayvalue_base"</td><td>string</td><td></td></tr></table>

\*\*is.CDS.ordered\*\*  
  the column number for an attribute with an entity in CDS for Applications.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>ordinal</td><td>"68"</td><td>integer</td><td></td></tr></table>

\*\*is.dataFormat.numeric.shaped\*\*  
  for setting the exact precision and scale of numeric values  

</details>

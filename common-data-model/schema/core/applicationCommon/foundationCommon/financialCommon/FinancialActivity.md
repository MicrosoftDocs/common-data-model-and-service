---
title: FinancialActivity
description: some description
ms.service:: common-data-model
ms.reviewer: anneta
ms.topic: article
ms.date: 2/15/2019
ms.author: tpalmer
---

# Financial Activity

Summarization of financial activity for a ledger, date, account, and dimension combination  
  
Latest version (0.8.1) of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/financialCommon/FinancialActivity.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

/core/applicationCommon/foundationCommon/financialCommon/FinancialActivity.cdm.json/FinancialActivity  

## Traits

<details>
<summary>Traits for this entity are listed below.  
</summary>

- **is.CDM.entityVersion**  
  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>versionNumber</td><td>0.8.1</td><td>string</td><td>semantic version number of the entity</td></tr></table>

- **is.identifiedBy**  
  names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FinancialActivity/hasAttributes/financialActivityId](#financialActivityId)</td><td>attribute</td><td></td></tr></table>

- **is.CDM.attributeGroup**  
  identifies standard groups of attributes in CDM entities.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>groupList</td><td><table><tr><th>attributeGroupReference</th></tr><tr><td>/core/applicationCommon/foundationCommon<br>/financeCommon/FinanceActivity.cdm.json<br>/FinanceActivity/hasAttributes<br>/attributesAddedAtThisScope</td></tr></table></td><td>entity</td><td></td></tr></table>

- **is.localized.displayedAs**  
  Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Financial Activity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
  Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Summarization of financial activity for a ledger, date, account, and dimension combination</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[financialActivityId](#financialActivityId)|The surrogate key of the record|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|
|[mainAccountCategoryKey](#mainAccountCategoryKey)|The category of the main account for this activity, denormalized for reporting|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|
|[mainAccountKey](#mainAccountKey)|The main account containing this financial activity|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|
|[companyKey](#companyKey)|The company for which this financial activity occurred|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|
|[transactionCurrencyKey](#transactionCurrencyKey)|The currency in which the source transaction occurred|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|
|[fiscalCalendarPeriodKey](#fiscalCalendarPeriodKey)|The fiscal period in which the financial activity occurred|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|
|[ledgerDimensionDisplayValue](#ledgerDimensionDisplayValue)|A denormalization of the full string representing the main account plus additional dimension values|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|
|[transactionCurrencyCode](#transactionCurrencyCode)|A denormalization of the currency code in which the source transaction occurred|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|
|[accountingCurrencyAmount](#accountingCurrencyAmount)|The amount of the financial activity expressed in the accounting currency|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|
|[accountingDate](#accountingDate)|The date on which the financial activity was recognized|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|
|[ledgerId](#ledgerId)|The ledger containing this financial activity|<a href="FinancialActivity.md" target="_blank">financialCommon/FinancialActivity</a>|

### <a href=#financialActivityId name="financialActivityId">financialActivityId</a>

The surrogate key of the record  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Financial Activity ID</td></tr><tr><td>description</td><td>The surrogate key of the record</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

#### Traits

<details>
<summary>List of traits for the financialActivityId attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.identifiedBy**  
names a specifc identity attribute to use with an entity  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>attribute</td><td>[FinancialActivity/hasAttributes/financialActivityId](#financialActivityId)</td><td>attribute</td><td></td></tr></table>

- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Financial Activity ID</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The surrogate key of the record</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

### <a href=#mainAccountCategoryKey name="mainAccountCategoryKey">mainAccountCategoryKey</a>

The category of the main account for this activity, denormalized for reporting  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main Account Category Key</td></tr><tr><td>description</td><td>The category of the main account for this activity, denormalized for reporting</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

#### Traits

<details>
<summary>List of traits for the mainAccountCategoryKey attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Main Account Category Key</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The category of the main account for this activity, denormalized for reporting</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  

</details>

### <a href=#mainAccountKey name="mainAccountKey">mainAccountKey</a>

The main account containing this financial activity  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Main Account Key</td></tr><tr><td>description</td><td>The main account containing this financial activity</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

#### Traits

<details>
<summary>List of traits for the mainAccountKey attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Main Account Key</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The main account containing this financial activity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  

</details>

### <a href=#companyKey name="companyKey">companyKey</a>

The company for which this financial activity occurred  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Company Key</td></tr><tr><td>description</td><td>The company for which this financial activity occurred</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

#### Traits

<details>
<summary>List of traits for the companyKey attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Company Key</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The company for which this financial activity occurred</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  

</details>

### <a href=#transactionCurrencyKey name="transactionCurrencyKey">transactionCurrencyKey</a>

The currency in which the source transaction occurred  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Currency Key</td></tr><tr><td>description</td><td>The currency in which the source transaction occurred</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transactionCurrencyKey attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transaction Currency Key</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The currency in which the source transaction occurred</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  

</details>

### <a href=#fiscalCalendarPeriodKey name="fiscalCalendarPeriodKey">fiscalCalendarPeriodKey</a>

The fiscal period in which the financial activity occurred  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Fiscal Calendar Period Key</td></tr><tr><td>description</td><td>The fiscal period in which the financial activity occurred</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

#### Traits

<details>
<summary>List of traits for the fiscalCalendarPeriodKey attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Fiscal Calendar Period Key</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The fiscal period in which the financial activity occurred</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  

</details>

### <a href=#ledgerDimensionDisplayValue name="ledgerDimensionDisplayValue">ledgerDimensionDisplayValue</a>

A denormalization of the full string representing the main account plus additional dimension values  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ledger Dimension Display Value</td></tr><tr><td>description</td><td>A denormalization of the full string representing the main account plus additional dimension values</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ledgerDimensionDisplayValue attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ledger Dimension Display Value</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>A denormalization of the full string representing the main account plus additional dimension values</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

### <a href=#transactionCurrencyCode name="transactionCurrencyCode">transactionCurrencyCode</a>

A denormalization of the currency code in which the source transaction occurred  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Transaction Currency Code</td></tr><tr><td>description</td><td>A denormalization of the currency code in which the source transaction occurred</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

#### Traits

<details>
<summary>List of traits for the transactionCurrencyCode attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Transaction Currency Code</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>A denormalization of the currency code in which the source transaction occurred</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

### <a href=#accountingCurrencyAmount name="accountingCurrencyAmount">accountingCurrencyAmount</a>

The amount of the financial activity expressed in the accounting currency  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>AccountingCurrencyAmount</td></tr><tr><td>description</td><td>The amount of the financial activity expressed in the accounting currency</td></tr><tr><td>dataFormat</td><td>Decimal</td></tr></table>

#### Traits

<details>
<summary>List of traits for the accountingCurrencyAmount attribute are listed below.</summary>

- **is.dataFormat.numeric.shaped**  
for setting the exact precision and scale of numeric values  

- **means.measurement.currency**  
- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>AccountingCurrencyAmount</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The amount of the financial activity expressed in the accounting currency</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

### <a href=#accountingDate name="accountingDate">accountingDate</a>

The date on which the financial activity was recognized  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>AccountingDate</td></tr><tr><td>description</td><td>The date on which the financial activity was recognized</td></tr><tr><td>dataFormat</td><td>Date</td></tr></table>

#### Traits

<details>
<summary>List of traits for the accountingDate attribute are listed below.</summary>

- **is.dataFormat.date**  
- **means.measurement.date**  
- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>AccountingDate</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The date on which the financial activity was recognized</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

</details>

### <a href=#ledgerId name="ledgerId">ledgerId</a>

The ledger containing this financial activity  
First included in: financialCommon/FinancialActivity (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Ledger</td></tr><tr><td>description</td><td>The ledger containing this financial activity</td></tr><tr><td>dataFormat</td><td>String</td></tr></table>

#### Traits

<details>
<summary>List of traits for the ledgerId attribute are listed below.</summary>

- **is.dataFormat.character**  
- **is.dataFormat.big**  
- **is.dataFormat.array**  
- **is.localized.displayedAs**  
Holds the list of language specific display text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>Ledger</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.localized.describedAs**  
Holds the list of language specific descriptive text for an object.  <table><tr><th>Parameter</th><th>Value</th><th>Data type</th><th>Explanation</th></tr><tr><td>localizedDisplayText</td><td><table><tr><th>languageTag</th><th>displayText</th></tr><tr><td>en</td><td>The ledger containing this financial activity</td></tr></table></td><td>entity</td><td>a reference to the constant entity holding the list of localized text</td></tr></table>

- **is.linkedEntity.identifier**  
Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.  

</details>

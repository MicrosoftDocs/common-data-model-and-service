---
title: A list of Common Data Model traits | Microsoft Docs
description: A list of Common Data Model traits.
author: msftman

ms.reviewer: v-iap
ms.topic: article
ms.date: 05/06/2021
ms.author: matgos
---

# List of CDM traits

This page lists the traits which are available in Common Data Model.


## <a id="does"><b>does</b></a>


**Description**


A root with a more meaningful base name for certain exhibited traits


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>does</b>|


**Properties**

None


**Parameters**

None


## <a id="does-elevateattribute"><b>does.elevateAttribute</b></a>


**Description**


Elevates (up to a entity) a trait that describes a specific attribute


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>does</b>](#does) <- <b>does.elevateAttribute</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|attribute|attribute|True


## <a id="does-havedefault"><b>does.haveDefault</b></a>


**Description**


An attribute has a default value


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>does</b>](#does) <- <b>does.haveDefault</b>|



| Properties |
|--|
|<b>defaultValue</b>|


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|default|any|True


## <a id="has"><b>has</b></a>


**Description**


A root for traits that describe properties of an object


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>has</b>|


**Properties**

None


**Parameters**

None


## <a id="has-category"><b>has.category</b></a>


**Description**


The root trait for the system of traits of hierarchical categorization


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- <b>has.category</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|categoryName|string|False
|classification|string|False
|parentCategoryName|string|False
|hierarchyLevel|integer|False
|hierarchyName|string|False


## <a id="has-category-functionalarea"><b>has.category.functionalArea</b></a>


**Description**


A level3 hierarchy item explaining the functional area for entities. Functional areas can divide entities by their purpose or use case such as auditing, reporting, recruiting, budgeting


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.category</b>](#has-category) <- [<b>has.category.level3</b>](#has-category-level3) <- <b>has.category.functionalArea</b>|


**Properties**

None


**Parameters**

None


## <a id="has-category-functionalarea-accountsreceivable"><b>has.category.functionalArea.AccountsReceivable</b></a>


**Description**


Entities from AccountsReceivable functional area


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.category</b>](#has-category) <- [<b>has.category.level3</b>](#has-category-level3) <- [<b>has.category.functionalArea</b>](#has-category-functionalarea) <- <b>has.category.functionalArea.AccountsReceivable</b>|


**Properties**

None


**Parameters**

None


## <a id="has-category-functionalarea-auditing"><b>has.category.functionalArea.Auditing</b></a>


**Description**


Entities from Auditing functional area


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.category</b>](#has-category) <- [<b>has.category.level3</b>](#has-category-level3) <- [<b>has.category.functionalArea</b>](#has-category-functionalarea) <- <b>has.category.functionalArea.Auditing</b>|


**Properties**

None


**Parameters**

None


## <a id="has-category-functionalarea-budgeting"><b>has.category.functionalArea.Budgeting</b></a>


**Description**


Entities from Budgeting functional area


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.category</b>](#has-category) <- [<b>has.category.level3</b>](#has-category-level3) <- [<b>has.category.functionalArea</b>](#has-category-functionalarea) <- <b>has.category.functionalArea.Budgeting</b>|


**Properties**

None


**Parameters**

None


## <a id="has-category-functionalarea-generalledger"><b>has.category.functionalArea.GeneralLedger</b></a>


**Description**


Entities from GeneralLedger functional area


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.category</b>](#has-category) <- [<b>has.category.level3</b>](#has-category-level3) <- [<b>has.category.functionalArea</b>](#has-category-functionalarea) <- <b>has.category.functionalArea.GeneralLedger</b>|


**Properties**

None


**Parameters**

None


## <a id="has-category-functionalarea-recruitment"><b>has.category.functionalArea.Recruitment</b></a>


**Description**


Entities from Recruitment functional area


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.category</b>](#has-category) <- [<b>has.category.level3</b>](#has-category-level3) <- [<b>has.category.functionalArea</b>](#has-category-functionalarea) <- <b>has.category.functionalArea.Recruitment</b>|


**Properties**

None


**Parameters**

None


## <a id="has-category-functionalarea-reporting"><b>has.category.functionalArea.Reporting</b></a>


**Description**


Entities from Reporting functional area


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.category</b>](#has-category) <- [<b>has.category.level3</b>](#has-category-level3) <- [<b>has.category.functionalArea</b>](#has-category-functionalarea) <- <b>has.category.functionalArea.Reporting</b>|


**Properties**

None


**Parameters**

None


## <a id="has-category-functionalarea-suppliers"><b>has.category.functionalArea.Suppliers</b></a>


**Description**


Entities from Suppliers functional area


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.category</b>](#has-category) <- [<b>has.category.level3</b>](#has-category-level3) <- [<b>has.category.functionalArea</b>](#has-category-functionalarea) <- <b>has.category.functionalArea.Suppliers</b>|


**Properties**

None


**Parameters**

None


## <a id="has-category-functionalarea-terminations"><b>has.category.functionalArea.Terminations</b></a>


**Description**


Entities from Terminations functional area


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.category</b>](#has-category) <- [<b>has.category.level3</b>](#has-category-level3) <- [<b>has.category.functionalArea</b>](#has-category-functionalarea) <- <b>has.category.functionalArea.Terminations</b>|


**Properties**

None


**Parameters**

None


## <a id="has-category-functionalarea-warehousing"><b>has.category.functionalArea.Warehousing</b></a>


**Description**


Entities from Warehousing functional area


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.category</b>](#has-category) <- [<b>has.category.level3</b>](#has-category-level3) <- [<b>has.category.functionalArea</b>](#has-category-functionalarea) <- <b>has.category.functionalArea.Warehousing</b>|


**Properties**

None


**Parameters**

None


## <a id="has-category-level1"><b>has.category.level1</b></a>


**Description**


Common explanation for level1 category items


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.category</b>](#has-category) <- <b>has.category.level1</b>|


**Properties**

None


**Parameters**

None


## <a id="has-category-level2"><b>has.category.level2</b></a>


**Description**


Common explanation for level2 category items


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.category</b>](#has-category) <- <b>has.category.level2</b>|


**Properties**

None


**Parameters**

None


## <a id="has-category-level3"><b>has.category.level3</b></a>


**Description**


Common explanation for level3 category items


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.category</b>](#has-category) <- <b>has.category.level3</b>|


**Properties**

None


**Parameters**

None


## <a id="has-category-sourcesystem"><b>has.category.sourceSystem</b></a>


**Description**


A level1 hierarchy item explaining the source system for entities. Entities from a given source system are expected to be self-consistent on identifiers and similar data domains.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.category</b>](#has-category) <- [<b>has.category.level1</b>](#has-category-level1) <- <b>has.category.sourceSystem</b>|


**Properties**

None


**Parameters**

None


## <a id="has-category-sourcesystem-dynamics365"><b>has.category.sourceSystem.Dynamics365</b></a>


**Description**


Entities from the Dynamics365 source system


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.category</b>](#has-category) <- [<b>has.category.level1</b>](#has-category-level1) <- [<b>has.category.sourceSystem</b>](#has-category-sourcesystem) <- <b>has.category.sourceSystem.Dynamics365</b>|


**Properties**

None


**Parameters**

None


## <a id="has-category-subjectarea"><b>has.category.subjectArea</b></a>


**Description**


A level2 hierarchy item explaining the subject area entities. Subject areas can represent broad business categories such as Finance, Sales and Human Resouces


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.category</b>](#has-category) <- [<b>has.category.level2</b>](#has-category-level2) <- <b>has.category.subjectArea</b>|


**Properties**

None


**Parameters**

None


## <a id="has-category-subjectarea-commerce"><b>has.category.subjectArea.Commerce</b></a>


**Description**


Entities from Commerce subject area


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.category</b>](#has-category) <- [<b>has.category.level2</b>](#has-category-level2) <- [<b>has.category.subjectArea</b>](#has-category-subjectarea) <- <b>has.category.subjectArea.Commerce</b>|


**Properties**

None


**Parameters**

None


## <a id="has-category-subjectarea-finance"><b>has.category.subjectArea.Finance</b></a>


**Description**


Entities from Finance subject area


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.category</b>](#has-category) <- [<b>has.category.level2</b>](#has-category-level2) <- [<b>has.category.subjectArea</b>](#has-category-subjectarea) <- <b>has.category.subjectArea.Finance</b>|


**Properties**

None


**Parameters**

None


## <a id="has-category-subjectarea-humanresources"><b>has.category.subjectArea.HumanResources</b></a>


**Description**


Entities from Human Resources subject area


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.category</b>](#has-category) <- [<b>has.category.level2</b>](#has-category-level2) <- [<b>has.category.subjectArea</b>](#has-category-subjectarea) <- <b>has.category.subjectArea.HumanResources</b>|


**Properties**

None


**Parameters**

None


## <a id="has-category-subjectarea-supplychain"><b>has.category.subjectArea.SupplyChain</b></a>


**Description**


Entities from Supply Chain subject area


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.category</b>](#has-category) <- [<b>has.category.level2</b>](#has-category-level2) <- [<b>has.category.subjectArea</b>](#has-category-subjectarea) <- <b>has.category.subjectArea.SupplyChain</b>|


**Properties**

None


**Parameters**

None


## <a id="has-description"><b>has.description</b></a>


**Description**


Defines a list of localizable text descriptions


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- <b>has.description</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|description|entity|False


## <a id="has-displayfolder"><b>has.displayFolder</b></a>


**Description**


Defines a localized string representing an arbitrary folder structure for display purposes.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- <b>has.displayFolder</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|displayFolder|entity|False


## <a id="has-displayname"><b>has.displayName</b></a>


**Description**


Defines a localized string defining display text for an object.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- <b>has.displayName</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|displayText|entity|False


## <a id="has-entityschemaabstractionlevel"><b>has.entitySchemaAbstractionLevel</b></a>


**Description**


A level of abstraction assigned to an Entity schema. Logical schema descriptions use complex dataTypes, inheritance, and entities as attributes. Resolved descriptions contain none of those things, only final trait and attribute sets are shown. A composition schema manipulates, guides or re-states parts of logical schemas to produce one resolved schema.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- <b>has.entitySchemaAbstractionLevel</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|level|string|False


## <a id="has-expansioninfo"><b>has.expansionInfo</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- <b>has.expansionInfo</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|expansionName|string|True


## <a id="has-expansioninfo-list"><b>has.expansionInfo.list</b></a>


**Description**


Marks the attribute that is part of a list and its ordinal.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.expansionInfo</b>](#has-expansioninfo) <- <b>has.expansionInfo.list</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|ordinal|integer|True
|memberAttribute|string|False


## <a id="has-expansioninfo-mapvalue"><b>has.expansionInfo.mapValue</b></a>


**Description**


Marks the attribute that is one of the values in a map and its ordinal.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.expansionInfo</b>](#has-expansioninfo) <- <b>has.expansionInfo.mapValue</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|ordinal|integer|True
|memberAttribute|string|False


## <a id="has-filelist"><b>has.fileList</b></a>


**Description**


Has a list of files associated with.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- <b>has.fileList</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|fileList|entity|True


## <a id="has-measurement-fundamentalcomponent"><b>has.measurement.fundamentalComponent</b></a>


**Description**


Description of one fundamental component of a derived unit


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>has.measurement.fundamentalComponent</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|fundamentalUnit|string|False
|symbol|string|False
|dimension|string|False
|fundamentalExponent|double|False
|fundamentalScale|double|False
|fundamentalOffset|double|False


## <a id="has-measurement-fundamentalcomponent-ampere"><b>has.measurement.fundamentalComponent.ampere</b></a>


**Description**


A fundamental component expressing electric current in amperes


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>has.measurement.fundamentalComponent</b>](#has-measurement-fundamentalcomponent) <- <b>has.measurement.fundamentalComponent.ampere</b>|


**Properties**

None


**Parameters**

None


## <a id="has-measurement-fundamentalcomponent-candela"><b>has.measurement.fundamentalComponent.candela</b></a>


**Description**


A fundamental component expressing luminous intensity in candelas


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>has.measurement.fundamentalComponent</b>](#has-measurement-fundamentalcomponent) <- <b>has.measurement.fundamentalComponent.candela</b>|


**Properties**

None


**Parameters**

None


## <a id="has-measurement-fundamentalcomponent-kelvin"><b>has.measurement.fundamentalComponent.kelvin</b></a>


**Description**


A fundamental component expressing thermodynamic temperature in degrees kelvin


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>has.measurement.fundamentalComponent</b>](#has-measurement-fundamentalcomponent) <- <b>has.measurement.fundamentalComponent.kelvin</b>|


**Properties**

None


**Parameters**

None


## <a id="has-measurement-fundamentalcomponent-kilogram"><b>has.measurement.fundamentalComponent.kilogram</b></a>


**Description**


A fundamental component expressing mass in kilogram


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>has.measurement.fundamentalComponent</b>](#has-measurement-fundamentalcomponent) <- <b>has.measurement.fundamentalComponent.kilogram</b>|


**Properties**

None


**Parameters**

None


## <a id="has-measurement-fundamentalcomponent-meter"><b>has.measurement.fundamentalComponent.meter</b></a>


**Description**


A fundamental component expressing length in meters


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>has.measurement.fundamentalComponent</b>](#has-measurement-fundamentalcomponent) <- <b>has.measurement.fundamentalComponent.meter</b>|


**Properties**

None


**Parameters**

None


## <a id="has-measurement-fundamentalcomponent-mole"><b>has.measurement.fundamentalComponent.mole</b></a>


**Description**


A fundamental component expressing amount in moles


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>has.measurement.fundamentalComponent</b>](#has-measurement-fundamentalcomponent) <- <b>has.measurement.fundamentalComponent.mole</b>|


**Properties**

None


**Parameters**

None


## <a id="has-measurement-fundamentalcomponent-second"><b>has.measurement.fundamentalComponent.second</b></a>


**Description**


A fundamental component expressing time in seconds


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>has.measurement.fundamentalComponent</b>](#has-measurement-fundamentalcomponent) <- <b>has.measurement.fundamentalComponent.second</b>|


**Properties**

None


**Parameters**

None


## <a id="has-origin"><b>has.origin</b></a>


**Description**


The root trait for the hierarchy related to the origin of schema.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- <b>has.origin</b>|


**Properties**

None


**Parameters**

None


## <a id="has-origin-datasource"><b>has.origin.dataSource</b></a>


**Description**


A trait defining the origination of the datasource for the schema.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.origin</b>](#has-origin) <- <b>has.origin.dataSource</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|dataSourceName|string|True


## <a id="has-origin-domain"><b>has.origin.domain</b></a>


**Description**


A trait defining the domain from which the schema originated.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.origin</b>](#has-origin) <- <b>has.origin.domain</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|domainName|string|True


## <a id="has-relational"><b>has.relational</b></a>


**Description**


The root trait for all traits related specifically to Relational activity.



| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- <b>has.relational</b>|


**Properties**

None


**Parameters**

None


## <a id="has-relational-defaultaggregation"><b>has.relational.defaultAggregation</b></a>


**Description**


Base trait for default relational aggregations associated with an Attributes.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.relational</b>](#has-relational) <- <b>has.relational.defaultAggregation</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|aggregationName|string|True


## <a id="has-relational-defaultaggregation-average"><b>has.relational.defaultAggregation.average</b></a>


**Description**


Specifies average as the default relational aggregation associated with an Attribute.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.relational</b>](#has-relational) <- [<b>has.relational.defaultAggregation</b>](#has-relational-defaultaggregation) <- <b>has.relational.defaultAggregation.average</b>|


**Properties**

None


**Parameters**

None


## <a id="has-relational-defaultaggregation-count"><b>has.relational.defaultAggregation.count</b></a>


**Description**


Specifies count as the default relational aggregation associated with an Attribute.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.relational</b>](#has-relational) <- [<b>has.relational.defaultAggregation</b>](#has-relational-defaultaggregation) <- <b>has.relational.defaultAggregation.count</b>|


**Properties**

None


**Parameters**

None


## <a id="has-relational-defaultaggregation-countdistinct"><b>has.relational.defaultAggregation.countDistinct</b></a>


**Description**


Specifies count distinct as the default relational aggregation associated with an Attribute.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.relational</b>](#has-relational) <- [<b>has.relational.defaultAggregation</b>](#has-relational-defaultaggregation) <- <b>has.relational.defaultAggregation.countDistinct</b>|


**Properties**

None


**Parameters**

None


## <a id="has-relational-defaultaggregation-maximum"><b>has.relational.defaultAggregation.maximum</b></a>


**Description**


Specifies maximum as the default relational aggregation associated with an Attribute.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.relational</b>](#has-relational) <- [<b>has.relational.defaultAggregation</b>](#has-relational-defaultaggregation) <- <b>has.relational.defaultAggregation.maximum</b>|


**Properties**

None


**Parameters**

None


## <a id="has-relational-defaultaggregation-minimum"><b>has.relational.defaultAggregation.minimum</b></a>


**Description**


Specifies minimum as the default relational aggregation associated with an Attribute.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.relational</b>](#has-relational) <- [<b>has.relational.defaultAggregation</b>](#has-relational-defaultaggregation) <- <b>has.relational.defaultAggregation.minimum</b>|


**Properties**

None


**Parameters**

None


## <a id="has-relational-defaultaggregation-sum"><b>has.relational.defaultAggregation.sum</b></a>


**Description**


Specifies sum as the default relational aggregation associated with an Attribute.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.relational</b>](#has-relational) <- [<b>has.relational.defaultAggregation</b>](#has-relational-defaultaggregation) <- <b>has.relational.defaultAggregation.sum</b>|


**Properties**

None


**Parameters**

None


## <a id="has-relational-jointype"><b>has.relational.joinType</b></a>


**Description**


Base trait for relational join types associated with a Relationship.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.relational</b>](#has-relational) <- <b>has.relational.joinType</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|joinType|string|True


## <a id="has-relational-jointype-fullouter"><b>has.relational.joinType.fullOuter</b></a>


**Description**


Specifies FULL OUTER JOIN as the default relational join type associated with this Relationship.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.relational</b>](#has-relational) <- [<b>has.relational.joinType</b>](#has-relational-jointype) <- <b>has.relational.joinType.fullOuter</b>|


**Properties**

None


**Parameters**

None


## <a id="has-relational-jointype-inner"><b>has.relational.joinType.inner</b></a>


**Description**


Specifies INNER JOIN as the default relational join type associated with this Relationship.



| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.relational</b>](#has-relational) <- [<b>has.relational.joinType</b>](#has-relational-jointype) <- <b>has.relational.joinType.inner</b>|


**Properties**

None


**Parameters**

None


## <a id="has-relational-jointype-leftanti"><b>has.relational.joinType.leftAnti</b></a>


**Description**


Specifies LEFT ANTI JOIN as the default relational join type associated with this Relationship.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.relational</b>](#has-relational) <- [<b>has.relational.joinType</b>](#has-relational-jointype) <- <b>has.relational.joinType.leftAnti</b>|


**Properties**

None


**Parameters**

None


## <a id="has-relational-jointype-leftouter"><b>has.relational.joinType.leftOuter</b></a>


**Description**


Specifies LEFT OUTER JOIN as the default relational join type associated with this Relationship.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.relational</b>](#has-relational) <- [<b>has.relational.joinType</b>](#has-relational-jointype) <- <b>has.relational.joinType.leftOuter</b>|


**Properties**

None


**Parameters**

None


## <a id="has-relational-jointype-rightanti"><b>has.relational.joinType.rightAnti</b></a>


**Description**


Specifies RIGHT ANTI JOIN as the default relational join type associated with this Relationship.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.relational</b>](#has-relational) <- [<b>has.relational.joinType</b>](#has-relational-jointype) <- <b>has.relational.joinType.rightAnti</b>|


**Properties**

None


**Parameters**

None


## <a id="has-relational-jointype-rightouter"><b>has.relational.joinType.rightOuter</b></a>


**Description**


Specifies RIGHT OUTER JOIN as the default relational join type associated with this Relationship.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.relational</b>](#has-relational) <- [<b>has.relational.joinType</b>](#has-relational-jointype) <- <b>has.relational.joinType.rightOuter</b>|


**Properties**

None


**Parameters**

None


## <a id="has-relationship"><b>has.relationship</b></a>


**Description**


The root trait for annotative traits relevant to relationships


|  Inheritance|
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- <b>has.relationship</b>|


**Properties**

None


**Parameters**

None


## <a id="has-relationship-constraint"><b>has.relationship.constraint</b></a>


**Description**


String value is a clause representing a constraint on the relationship in chosen syntax


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.relationship</b>](#has-relationship) <- <b>has.relationship.constraint</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|constraintClause|string|False


## <a id="has-schemaobjectidentifier"><b>has.schemaObjectIdentifier</b></a>


**Description**


The schema object has an identifier, which is a string, specified as the parameter of the trait. This allows writers to define additional identification values.




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- <b>has.schemaObjectIdentifier</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|identifier|string|True


## <a id="indicates-expansioninfo-count"><b>indicates.expansionInfo.count</b></a>


**Description**


Marks the attribute is the count of elements in an expansion.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.expansionInfo</b>](#has-expansioninfo) <- <b>indicates.expansionInfo.count</b>|


**Properties**

None


**Parameters**

None


## <a id="indicates-expansioninfo-mapkey"><b>indicates.expansionInfo.mapKey</b></a>


**Description**


Marks the attribute that is one of the keys in a map and its ordinal.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>has</b>](#has) <- [<b>has.expansionInfo</b>](#has-expansioninfo) <- <b>indicates.expansionInfo.mapKey</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|ordinal|integer|True


## <a id="is"><b>is</b></a>


**Description**


The root 'trait' from which all others derive.




None


**Properties**

None


**Parameters**

None


## <a id="is-addedinsupportof"><b>is.addedInSupportOf</b></a>



| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.addedInSupportOf</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|inSupportOf|attributeName|False


## <a id="is-application"><b>is.application</b></a>


**Description**


Root trait for application information


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.application</b>|


**Properties**

None


**Parameters**

None


## <a id="is-application-releaseversion"><b>is.application.releaseVersion</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.application</b>](#is-application) <- <b>is.application.releaseVersion</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|releaseVersion|string|False


## <a id="is-calculationof"><b>is.calculationOf</b></a>


**Description**


The attribute value is the result of a calculation on the sourceAttribute


|Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.correlatedWith</b>](#is-correlatedwith) <- <b>is.calculationOf</b>|


**Properties**

None


**Parameters**

None


## <a id="is-cdm"><b>is.CDM</b></a>


**Description**


Root trait for information about the CDM itself.


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.CDM</b>|


**Properties**

None


**Parameters**

None


## <a id="is-cdm-attributegroup"><b>is.CDM.attributeGroup</b></a>


**Description**


Identifies standard groups of attributes in CDM entities.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.CDM</b>](#is-cdm) <- <b>is.CDM.attributeGroup</b>|


**Properties**

| Inheritance |
|--|
|<b>cdmSchemas</b>|


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|groupList|entity|False


## <a id="is-cdm-entityversion"><b>is.CDM.entityVersion</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.CDM</b>](#is-cdm) <- <b>is.CDM.entityVersion</b>|


| Properties |
|--|
|<b>version</b>|


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|versionNumber|string|True


## <a id="is-constrained"><b>is.constrained</b></a>


**Description**


Maximum length or value constraints


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.constrained</b>|


| Properties |
|--|
|<b>maximumValue</b>|
|<b>minimumValue</b>|
|<b>maximumLength</b>|


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|maximumLength|integer|False
|minimumValue|decimal|False
|maximumValue|decimal|False


## <a id="is-constrainedlist"><b>is.constrainedList</b></a>


**Description**


The values of an attribute are taken from or looked up from a fixed list of possibilities


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.constrainedList</b>|


| Properties |
|--|
|<b>valueConstrainedToList</b>|


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|defaultList|entity|False


## <a id="is-constrainedlist-correlated"><b>is.constrainedList.correlated</b></a>


**Description**


The values of an attribute are taken from or looked up from a fixed list of possibilities that represent correlated status


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.constrainedList.correlated</b>|


**Properties**

| Properties |
|--|
|<b>valueConstrainedToList</b>|


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|defaultList|entity|False


## <a id="is-constrainedlist-string"><b>is.constrainedList.string</b></a>


**Description**


The values of an attribute are taken from or looked up from a fixed list of possibilities


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.constrainedList.string</b>|


| Properties |
|--|
|<b>valueConstrainedToList</b>|


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|defaultList|entity|False


## <a id="is-constrainedlist-wellknown"><b>is.constrainedList.wellKnown</b></a>


**Description**


The values of an attribute are taken from or looked up from a fixed list of possibilities which are defined in an identified public location.


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.constrainedList.wellKnown</b>|


| Properties |
|--|
|<b>valueConstrainedToList</b>|


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|uniqueIdentifier|string|False
|defaultList|entity|False


## <a id="is-correlatedwith"><b>is.correlatedWith</b></a>


**Description**


The attribute value is correlated with the sourceAttribute


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.correlatedWith</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|sourceAttribute|attributeName|True


## <a id="is-dataformat"><b>is.dataFormat</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.dataFormat</b>|


**Properties**

| Properties |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-dataformat-array"><b>is.dataFormat.array</b></a>


**Description**


Indicates a contiguous sequence of fundamental units that shoud be taken as a whole and considered one value. Array of Character is a String, Array of Byte is a Binary Object


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- <b>is.dataFormat.array</b>|


**Properties**

| Properties |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-dataformat-big"><b>is.dataFormat.big</b></a>


**Description**


Indicates an atomic but multi-unit version of a fundamental type such as a multi byte encoded character, a double precision float, a long integer.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- <b>is.dataFormat.big</b>|


**Properties**

| Properties |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-dataformat-boolean"><b>is.dataFormat.boolean</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- <b>is.dataFormat.boolean</b>|


**Properties**

| Properties |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-dataformat-byte"><b>is.dataFormat.byte</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- <b>is.dataFormat.byte</b>|


**Properties**

| Properties |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-dataformat-character"><b>is.dataFormat.character</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- <b>is.dataFormat.character</b>|


**Properties**

| Properties |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-dataformat-date"><b>is.dataFormat.date</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- <b>is.dataFormat.date</b>|


**Properties**

| Properties |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-dataformat-floatingpoint"><b>is.dataFormat.floatingPoint</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- <b>is.dataFormat.floatingPoint</b>|


**Properties**

| Properties |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-dataformat-guid"><b>is.dataFormat.guid</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- <b>is.dataFormat.guid</b>|


**Properties**

| Properties |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-dataformat-integer"><b>is.dataFormat.integer</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- <b>is.dataFormat.integer</b>|


**Properties**

| Properties |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-dataformat-jsinteger"><b>is.dataFormat.JSInteger</b></a>


**Description**


Represents the 54 bit integer numbers compatible with javascript


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- <b>is.dataFormat.JSInteger</b>|


**Properties**

| Properties |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-dataformat-list"><b>is.dataFormat.list</b></a>


**Description**


Marks the attribute that contains a list of attributes.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- <b>is.dataFormat.list</b>|


**Properties**

| |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-dataformat-map"><b>is.dataFormat.map</b></a>


**Description**


Marks the attribute that contains a map of attributes.


| Inheritance|
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- <b>is.dataFormat.map</b>|


**Properties**

| Properties |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-dataformat-mapkey"><b>is.dataFormat.mapKey</b></a>


**Description**


Marks the attribute that is one of the keys in a map.


| Inheritance|
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- <b>is.dataFormat.mapKey</b>|


**Properties**

| Properties |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-dataformat-mapvalue"><b>is.dataFormat.mapValue</b></a>


**Description**


Marks the attribute that is one of the values in a map.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- <b>is.dataFormat.mapValue</b>|


**Properties**

| |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-dataformat-numeric"><b>is.dataFormat.numeric</b></a>


**Inheritance**

| |
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- <b>is.dataFormat.numeric</b>|


**Properties**

| |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-dataformat-numeric-shaped"><b>is.dataFormat.numeric.shaped</b></a>


**Description**


For setting the exact precision and scale of numeric values


**Inheritance**

| |
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- [<b>is.dataFormat.numeric</b>](#is-dataformat-numeric) <- <b>is.dataFormat.numeric.shaped</b>|


**Properties**

| |
|--|
|<b>dataFormat</b>|


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|precision|integer|False
|scale|integer|False


## <a id="is-dataformat-signed"><b>is.dataFormat.signed</b></a>


**Description**


Indicates the capability to represent values less than zero.


**Inheritance**

| |
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- <b>is.dataFormat.signed</b>|


**Properties**

| |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-dataformat-small"><b>is.dataFormat.small</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- <b>is.dataFormat.small</b>|


**Properties**

| Properties |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-dataformat-time"><b>is.dataFormat.time</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- <b>is.dataFormat.time</b>|


**Properties**

| Properties |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-dataformat-timeoffset"><b>is.dataFormat.timeOffset</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- <b>is.dataFormat.timeOffset</b>|


**Properties**

| Properties |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-dataformat-unsigned"><b>is.dataFormat.unsigned</b></a>


**Description**


Indicates the capability to represent only values zero and greater.


**Inheritance**

| |
|--|
|[<b>is</b>](#is) <- [<b>is.dataFormat</b>](#is-dataformat) <- <b>is.dataFormat.unsigned</b>|


**Properties**

| |
|--|
|<b>dataFormat</b>|


**Parameters**

None


## <a id="is-formatted"><b>is.formatted</b></a>


**Description**


A root for traits that describe how data is formatted


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.formatted</b>|


**Properties**

None


**Parameters**

None


## <a id="is-formatted-date"><b>is.formatted.date</b></a>


**Description**


Date data formatted as a string in ISO 8601 format


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.formatted</b>](#is-formatted) <- <b>is.formatted.date</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|format|stringFormat|False


## <a id="is-formatted-datetime"><b>is.formatted.dateTime</b></a>


**Description**


DateTime data formatted as a string in ISO 8601 format


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.formatted</b>](#is-formatted) <- <b>is.formatted.dateTime</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|format|stringFormat|False


## <a id="is-formatted-forculture"><b>is.formatted.forCulture</b></a>


**Description**


Values are stored using the specified culture


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.formatted</b>](#is-formatted) <- <b>is.formatted.forCulture</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|culture|cultureTag|True


## <a id="is-formatted-text"><b>is.formatted.text</b></a>


**Description**


String data is formatted according to the format parameter


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.formatted</b>](#is-formatted) <- <b>is.formatted.text</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|format|stringFormat|True


## <a id="is-formatted-time"><b>is.formatted.time</b></a>


**Description**


Time data formatted as a string in ISO 8601 format


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.formatted</b>](#is-formatted) <- <b>is.formatted.time</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|format|stringFormat|False


## <a id="is-hidden"><b>is.hidden</b></a>


**Description**


All attributes with this trait should be hidden from view of the entity consumer.




None


**Properties**

None


**Parameters**

None


## <a id="is-identifiedby"><b>is.identifiedBy</b></a>


**Description**


Names a specifc identity attribute to use with an entity


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>does</b>](#does) <- [<b>does.elevateAttribute</b>](#does-elevateattribute) <- <b>is.identifiedBy</b>|


**Properties**

| Properties |
|--|
|<b>primaryKey</b>|
|<b>isPrimaryKey</b>|


**Parameters**

None


## <a id="is-incurrency"><b>is.inCurrency</b></a>


**Description**


The data represents an amount of the specified currency


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.inCurrency</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|code|currencyCode|True


## <a id="is-intimezone"><b>is.inTimeZone</b></a>


**Description**


The associated data is assumed to be in the specified time zone


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.inTimeZone</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|timeZoneName|timezone|True
|format|stringFormat|True


## <a id="is-intimezone-microsoftformat"><b>is.inTimeZone.MicrosoftFormat</b></a>


**Description**


The associated data is assumed to be in the specified time zone. timeZoneName value is a Microsoft standard time zone name. see https://support.microsoft.com/en-us/help/973627


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.inTimeZone</b>](#is-intimezone) <- <b>is.inTimeZone.MicrosoftFormat</b>|


**Properties**

None


**Parameters**

None


## <a id="is-intimezone-tzdatabaseformat"><b>is.inTimeZone.tzDatabaseFormat</b></a>


**Description**


The associated data is assumed to be in the specified time zone. timeZoneName value is a Time Zone Database standard time zone name. see https://www.iana.org/time-zones


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.inTimeZone</b>](#is-intimezone) <- <b>is.inTimeZone.tzDatabaseFormat</b>|


**Properties**

None


**Parameters**

None


## <a id="is-linkedentity"><b>is.linkedEntity</b></a>


**Description**


Base for traits that are used to decorate the attributes and artifacts created by the traits on the hasFlexibleRelationshipWithEntity relationship.




None


**Properties**

None


**Parameters**

None


## <a id="is-linkedentity-array"><b>is.linkedEntity.array</b></a>


**Description**


Identifies the case when one entity links to (uses as an attribute) an array of other entities.




None


**Properties**

None


**Parameters**

None


## <a id="is-linkedentity-array-count"><b>is.linkedEntity.array.count</b></a>


**Description**


Marks an attribute that contains the count of items in the array of linked (used as an attribute) entities




None


**Properties**

None


**Parameters**

None


## <a id="is-linkedentity-identifier"><b>is.linkedEntity.identifier</b></a>


**Description**


Marks the attribute(s) that hold foreign key references to a linked (used as an attribute) entity. This attribute is added to the resolved entity to enumerate the referenced entities.


| Inheritance |
|--|
|[<b>is.linkedEntity</b>](#is-linkedentity) <- <b>is.linkedEntity.identifier</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|entityReferences|entity|False


## <a id="is-linkedentity-name"><b>is.linkedEntity.name</b></a>


**Description**


Marks an attribute that contains the entity name or 'class' for the situation where one entity links to (uses as an attribute) a set of possible entities.


| Inheritance |
|--|
|[<b>is.linkedEntity</b>](#is-linkedentity) <- <b>is.linkedEntity.name</b>|


**Properties**

None


**Parameters**

None


## <a id="is-localized"><b>is.localized</b></a>


**Description**


Associates a list of localized string with an object


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.localized</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|localizedDisplayText|entity|False


## <a id="is-localized-describedas"><b>is.localized.describedAs</b></a>


**Description**


Holds the list of language specific descriptive text for an object.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.localized</b>](#is-localized) <- <b>is.localized.describedAs</b>|


**Properties**

| Properties |
|--|
|<b>description</b>|


**Parameters**

None


## <a id="is-localized-displayedas"><b>is.localized.displayedAs</b></a>


**Description**


Holds the list of language specific display text for an object.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.localized</b>](#is-localized) <- <b>is.localized.displayedAs</b>|


| Properties |
|--|
|<b>displayName</b>|


**Parameters**

None


## <a id="is-locatable"><b>is.locatable</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>does</b>](#does) <- [<b>does.elevateAttribute</b>](#does-elevateattribute) <- <b>is.locatable</b>|


**Properties**

None


**Parameters**

None


## <a id="is-managedby"><b>is.managedBy</b></a>


**Description**


The value denotes information about a service/entity who is owning a model.


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.managedBy</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|application|string|False


## <a id="is-modelconversion"><b>is.modelConversion</b></a>


**Description**


Represents a correlation with model.json to CDM model conversion.


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.modelConversion</b>|


**Properties**

None


**Parameters**

None


## <a id="is-modelconversion-modelversion"><b>is.modelConversion.modelVersion</b></a>


**Description**


The value denotes the version number set in a converted model.json file


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.modelConversion</b>](#is-modelconversion) <- <b>is.modelConversion.modelVersion</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|version|string|False


## <a id="is-modelconversion-otherannotations"><b>is.modelConversion.otherAnnotations</b></a>


**Description**


The value denotes model.json annotations which have not been recognized.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.modelConversion</b>](#is-modelconversion) <- <b>is.modelConversion.otherAnnotations</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|annotations|object|False


## <a id="is-modelconversion-referencemodelmap"><b>is.modelConversion.referenceModelMap</b></a>


**Description**


The value denotes a reference model map containing multiple id-location pairs used for reference entity resolution.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.modelConversion</b>](#is-modelconversion) <- <b>is.modelConversion.referenceModelMap</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|referenceModelMap|object|False


## <a id="is-named"><b>is.named</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>does</b>](#does) <- [<b>does.elevateAttribute</b>](#does-elevateattribute) <- <b>is.named</b>|


**Properties**

None


**Parameters**

None


## <a id="is-nullable"><b>is.nullable</b></a>


**Description**


The attribute value may be set to NULL.


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.nullable</b>|


| Properties |
|--|
|<b>isNullable</b>|


**Parameters**

None


## <a id="is-ordered"><b>is.ordered</b></a>



| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>does</b>](#does) <- [<b>does.elevateAttribute</b>](#does-elevateattribute) <- <b>is.ordered</b>|


**Properties**

None


**Parameters**

None


## <a id="is-partition"><b>is.partition</b></a>


**Description**


The base trait for partition specific traits.


|Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.partition</b>|


**Properties**

None


**Parameters**

None


## <a id="is-partition-compressed"><b>is.partition.compressed</b></a>


**Description**


The value is the compression format represented.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.partition</b>](#is-partition) <- <b>is.partition.compressed</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|compressionFormatName|string|True


## <a id="is-partition-culture"><b>is.partition.culture</b></a>


**Description**


The value denotes culture in the partition files.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.partition</b>](#is-partition) <- <b>is.partition.culture</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|culture|string|False


## <a id="is-partition-format"><b>is.partition.format</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.partition</b>](#is-partition) <- <b>is.partition.format</b>|


**Properties**

None


**Parameters**

None


## <a id="is-partition-format-csv"><b>is.partition.format.CSV</b></a>


**Description**


The value is the file format settings of a partition CSV file.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.partition</b>](#is-partition) <- [<b>is.partition.format</b>](#is-partition-format) <- <b>is.partition.format.CSV</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|columnHeaders|boolean|False
|csvStyle|string|False
|delimiter|string|False
|quoteStyle|string|False
|encoding|string|False
|escape|char|False
|newline|char|False
|quote|char|False
|skipLines|integer|False
|raggedRight|boolean|False


## <a id="is-partition-format-deltalake"><b>is.partition.format.deltaLake</b></a>


**Description**


The partition path points to one complete folder of Spark Delta Lake data. Options allow for time travel access to the data.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.partition</b>](#is-partition) <- [<b>is.partition.format</b>](#is-partition-format) <- <b>is.partition.format.deltaLake</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|versionAsOf|integer|False
|timestampAsOf|dateTime|False


## <a id="is-partition-format-json"><b>is.partition.format.json</b></a>


**Description**


The value is the file format settings of a partition JSON file. The "type" parameter value must be one of the following: "single", "lines", "concatenated", or "array". See [this link](https://learn.microsoft.com/en-us/azure/data-factory/format-json#json-file-patterns) for more information.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.partition</b>](#is-partition) <- [<b>is.partition.format</b>](#is-partition-format) <- <b>is.partition.format.json</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|type|string|True


## <a id="is-partition-format-parquet"><b>is.partition.format.parquet</b></a>


**Description**


The value is the file format settings of a partition parquet file.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.partition</b>](#is-partition) <- [<b>is.partition.format</b>](#is-partition-format) <- <b>is.partition.format.parquet</b>|


**Properties**

None


**Parameters**

None


## <a id="is-partition-incremental"><b>is.partition.incremental</b></a>


**Description**


The base trait for describing incremental partitions and incremental partition patterns.


**Inheritance**

| |
|--|
|[<b>is</b>](#is) <- [<b>is.partition</b>](#is-partition) <- <b>is.partition.incremental</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|type|string|True
|incrementPartitionPatternName|string|False
|fullDataPartitionPatternName|string|False


## <a id="is-readonly"><b>is.readOnly</b></a>



**Description**


The base trait for describing incremental partitions and incremental partition patterns.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>is.partition</b>](#is-partition) <- <b>is.partition.incremental</b>|


**Properties**

None

**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|type|string|True
|incrementPartitionPatternName|string|False
|fullDataPartitionPatternNa|string|False


## <a id="is-readonly"><b>is.readOnly</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.readOnly</b>|


| Properties |
|--|
|<b>isReadOnly</b>|


**Parameters**

None


## <a id="is-relationship"><b>is.relationship</b></a>


**Description**


Root trait for structural traits relevant to relationships


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.relationship</b>|


**Properties**

None


**Parameters**

None


## <a id="is-relationship-default"><b>is.relationship.default</b></a>


**Description**


The default relationship when there are multiple relationships between two entities.


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.relationship.default</b>|


**Properties**

None


**Parameters**

None


## <a id="is-required"><b>is.required</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.required</b>|


**Properties**

None


**Parameters**

None


## <a id="is-requiredatlevel"><b>is.requiredAtLevel</b></a>


**Description**


The requirement level for setting values into this attribute in CDS for Applications or for including this attribute in entities created in CDS for Analytics


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.requiredAtLevel</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|level|string|True


## <a id="is-secret"><b>is.secret</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.secret</b>|


**Properties**

None


**Parameters**

None


## <a id="is-sensitive"><b>is.sensitive</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.sensitive</b>|


**Properties**

None


**Parameters**

None


## <a id="is-virtual-attribute"><b>is.virtual.attribute</b></a>


**Description**


Marks an attribute added to an entity to document or represent a concept, often regarding other attributes. When working with data, be aware that virtual attributes might never have corresponding data values in an entity's partition or might only have data values if special measures are taken to manifest them.


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>is.virtual.attribute</b>|


**Properties**

None


**Parameters**

None


## <a id="means"><b>means</b></a>


**Description**


A root with a more meaningful base name for certain semantic meaning traits


| Inheritance |
|--|
|[<b>is</b>](#is) <- <b>means</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar"><b>means.calendar</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- <b>means.calendar</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-day"><b>means.calendar.day</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- <b>means.calendar.day</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-dayofhalfyear"><b>means.calendar.dayOfHalfyear</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.day</b>](#means-calendar-day) <- <b>means.calendar.dayOfHalfyear</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-dayofmonth"><b>means.calendar.dayOfMonth</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.day</b>](#means-calendar-day) <- <b>means.calendar.dayOfMonth</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-dayofmonthorperiod"><b>means.calendar.dayOfMonthOrPeriod</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.day</b>](#means-calendar-day) <- <b>means.calendar.dayOfMonthOrPeriod</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-dayofquarter"><b>means.calendar.dayOfQuarter</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.day</b>](#means-calendar-day) <- <b>means.calendar.dayOfQuarter</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-dayoftendays"><b>means.calendar.dayOfTendays</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.day</b>](#means-calendar-day) <- <b>means.calendar.dayOfTendays</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-dayoftrimester"><b>means.calendar.dayOfTrimester</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.day</b>](#means-calendar-day) <- <b>means.calendar.dayOfTrimester</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-dayofweek"><b>means.calendar.dayOfWeek</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.day</b>](#means-calendar-day) <- <b>means.calendar.dayOfWeek</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-dayofyear"><b>means.calendar.dayOfYear</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.day</b>](#means-calendar-day) <- <b>means.calendar.dayOfYear</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-fiscal"><b>means.calendar.fiscal</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- <b>means.calendar.fiscal</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-iso8601"><b>means.calendar.ISO8601</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- <b>means.calendar.ISO8601</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-manufacturing"><b>means.calendar.manufacturing</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- <b>means.calendar.manufacturing</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-month"><b>means.calendar.month</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- <b>means.calendar.month</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-monthofhalfyear"><b>means.calendar.monthOfHalfyear</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.month</b>](#means-calendar-month) <- <b>means.calendar.monthOfHalfyear</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-monthofquarter"><b>means.calendar.monthOfQuarter</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.month</b>](#means-calendar-month) <- <b>means.calendar.monthOfQuarter</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-monthoftrimester"><b>means.calendar.monthOfTrimester</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.month</b>](#means-calendar-month) <- <b>means.calendar.monthOfTrimester</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-monthofyear"><b>means.calendar.monthOfYear</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.month</b>](#means-calendar-month) <- <b>means.calendar.monthOfYear</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-quarter"><b>means.calendar.quarter</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- <b>means.calendar.quarter</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-quarterofhalfyear"><b>means.calendar.quarterOfHalfyear</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.quarter</b>](#means-calendar-quarter) <- <b>means.calendar.quarterOfHalfyear</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-quarterofyear"><b>means.calendar.quarterOfYear</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.quarter</b>](#means-calendar-quarter) <- <b>means.calendar.quarterOfYear</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-reporting"><b>means.calendar.reporting</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- <b>means.calendar.reporting</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-tenday"><b>means.calendar.tenday</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- <b>means.calendar.tenday</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-tendayofhalfyear"><b>means.calendar.tendayOfHalfyear</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.tenday</b>](#means-calendar-tenday) <- <b>means.calendar.tendayOfHalfyear</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-tendayofmonth"><b>means.calendar.tendayOfMonth</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.tenday</b>](#means-calendar-tenday) <- <b>means.calendar.tendayOfMonth</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-tendayofquarter"><b>means.calendar.tendayOfQuarter</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.tenday</b>](#means-calendar-tenday) <- <b>means.calendar.tendayOfQuarter</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-tendayoftrimester"><b>means.calendar.tendayOfTrimester</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.tenday</b>](#means-calendar-tenday) <- <b>means.calendar.tendayOfTrimester</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-tendayofyear"><b>means.calendar.tendayOfYear</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.tenday</b>](#means-calendar-tenday) <- <b>means.calendar.tendayOfYear</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-trimester"><b>means.calendar.trimester</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- <b>means.calendar.trimester</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-trimesterofyear"><b>means.calendar.trimesterOfYear</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.trimester</b>](#means-calendar-trimester) <- <b>means.calendar.trimesterOfYear</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-week"><b>means.calendar.week</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- <b>means.calendar.week</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-weekofhalfyear"><b>means.calendar.weekOfHalfyear</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.week</b>](#means-calendar-week) <- <b>means.calendar.weekOfHalfyear</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-weekofmonth"><b>means.calendar.weekOfMonth</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.week</b>](#means-calendar-week) <- <b>means.calendar.weekOfMonth</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-weekofquarter"><b>means.calendar.weekOfQuarter</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.week</b>](#means-calendar-week) <- <b>means.calendar.weekOfQuarter</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-weekoftrimester"><b>means.calendar.weekOfTrimester</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.week</b>](#means-calendar-week) <- <b>means.calendar.weekOfTrimester</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-weekofyear"><b>means.calendar.weekOfYear</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- [<b>means.calendar.week</b>](#means-calendar-week) <- <b>means.calendar.weekOfYear</b>|


**Properties**

None


**Parameters**

None


## <a id="means-calendar-year"><b>means.calendar.year</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.calendar</b>](#means-calendar) <- <b>means.calendar.year</b>|


**Properties**

None


**Parameters**

None


## <a id="means-category"><b>means.category</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- <b>means.category</b>|


**Properties**

None


**Parameters**

None


## <a id="means-content"><b>means.content</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- <b>means.content</b>|


**Properties**

None


**Parameters**

None


## <a id="means-content-binary"><b>means.content.binary</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.content</b>](#means-content) <- <b>means.content.binary</b>|


**Properties**

None


**Parameters**

None


## <a id="means-content-binary-image"><b>means.content.binary.image</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.content</b>](#means-content) <- [<b>means.content.binary</b>](#means-content-binary) <- <b>means.content.binary.image</b>|


**Properties**

None


**Parameters**

None


## <a id="means-content-binary-image-bmp"><b>means.content.binary.image.BMP</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.content</b>](#means-content) <- [<b>means.content.binary</b>](#means-content-binary) <- [<b>means.content.binary.image</b>](#means-content-binary-image) <- <b>means.content.binary.image.BMP</b>|


**Properties**

None


**Parameters**

None


## <a id="means-content-binary-image-gif"><b>means.content.binary.image.GIF</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.content</b>](#means-content) <- [<b>means.content.binary</b>](#means-content-binary) <- [<b>means.content.binary.image</b>](#means-content-binary-image) <- <b>means.content.binary.image.GIF</b>|


**Properties**

None


**Parameters**

None


## <a id="means-content-binary-image-jpg"><b>means.content.binary.image.JPG</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.content</b>](#means-content) <- [<b>means.content.binary</b>](#means-content-binary) <- [<b>means.content.binary.image</b>](#means-content-binary-image) <- <b>means.content.binary.image.JPG</b>|


**Properties**

None


**Parameters**

None


## <a id="means-content-binary-image-png"><b>means.content.binary.image.PNG</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.content</b>](#means-content) <- [<b>means.content.binary</b>](#means-content-binary) <- [<b>means.content.binary.image</b>](#means-content-binary-image) <- <b>means.content.binary.image.PNG</b>|


**Properties**

None


**Parameters**

None


## <a id="means-content-binary-image-tiff"><b>means.content.binary.image.TIFF</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.content</b>](#means-content) <- [<b>means.content.binary</b>](#means-content-binary) <- [<b>means.content.binary.image</b>](#means-content-binary-image) <- <b>means.content.binary.image.TIFF</b>|


**Properties**

None


**Parameters**

None


## <a id="means-content-text"><b>means.content.text</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.content</b>](#means-content) <- <b>means.content.text</b>|


**Properties**

None


**Parameters**

None


## <a id="means-content-text-csv"><b>means.content.text.CSV</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.content</b>](#means-content) <- [<b>means.content.text</b>](#means-content-text) <- <b>means.content.text.CSV</b>|


**Properties**

None


**Parameters**

None


## <a id="means-content-text-html"><b>means.content.text.HTML</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.content</b>](#means-content) <- [<b>means.content.text</b>](#means-content-text) <- <b>means.content.text.HTML</b>|


**Properties**

None


**Parameters**

None


## <a id="means-content-text-json"><b>means.content.text.JSON</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.content</b>](#means-content) <- [<b>means.content.text</b>](#means-content-text) <- <b>means.content.text.JSON</b>|


**Properties**

None


**Parameters**

None


## <a id="means-content-text-xml"><b>means.content.text.XML</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.content</b>](#means-content) <- [<b>means.content.text</b>](#means-content-text) <- <b>means.content.text.XML</b>|


**Properties**

None


**Parameters**

None


## <a id="means-demographic"><b>means.demographic</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- <b>means.demographic</b>|


**Properties**

None


**Parameters**

None


## <a id="means-demographic-age"><b>means.demographic.age</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.demographic</b>](#means-demographic) <- <b>means.demographic.age</b>|


**Properties**

None


**Parameters**

None


## <a id="means-demographic-birthdate"><b>means.demographic.birthDate</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.demographic</b>](#means-demographic) <- <b>means.demographic.birthDate</b>|


**Properties**

None


**Parameters**

None


## <a id="means-demographic-education"><b>means.demographic.education</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.demographic</b>](#means-demographic) <- <b>means.demographic.education</b>|


**Properties**

None


**Parameters**

None


## <a id="means-demographic-ethnicity"><b>means.demographic.ethnicity</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.demographic</b>](#means-demographic) <- <b>means.demographic.ethnicity</b>|


**Properties**

None


**Parameters**

None


## <a id="means-demographic-gender"><b>means.demographic.gender</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.demographic</b>](#means-demographic) <- <b>means.demographic.gender</b>|


**Properties**

None


**Parameters**

None


## <a id="means-demographic-income"><b>means.demographic.income</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.demographic</b>](#means-demographic) <- <b>means.demographic.income</b>|


**Properties**

None


**Parameters**

None


## <a id="means-demographic-maritalstatus"><b>means.demographic.maritalStatus</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.demographic</b>](#means-demographic) <- <b>means.demographic.maritalStatus</b>|


**Properties**

None


**Parameters**

None


## <a id="means-entityname"><b>means.entityName</b></a>


**Description**


A string value is the name of a CDM entity.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- <b>means.entityName</b>|


**Properties**

None


**Parameters**

None


## <a id="means-entityname-specific"><b>means.entityName.specific</b></a>


**Description**


Holds the name of specific CDM entity as a parameter of the trait.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.entityName</b>](#means-entityname) <- <b>means.entityName.specific</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|entity|entityName|False


## <a id="means-entitystate"><b>means.entityState</b></a>


**Description**


The attribute represents the current state of the entity.


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>does</b>](#does) <- [<b>does.elevateAttribute</b>](#does-elevateattribute) <- <b>means.entityState</b>|


**Properties**

None


**Parameters**

None


## <a id="means-filename"><b>means.fileName</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- <b>means.fileName</b>|


**Properties**

None


**Parameters**

None


## <a id="means-formatting"><b>means.formatting</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- <b>means.formatting</b>|


**Properties**

None


**Parameters**

None


## <a id="means-formatting-color"><b>means.formatting.color</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.formatting</b>](#means-formatting) <- <b>means.formatting.color</b>|


**Properties**

None


**Parameters**

None


## <a id="means-formatting-font"><b>means.formatting.font</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.formatting</b>](#means-formatting) <- <b>means.formatting.font</b>|


**Properties**

None


**Parameters**

None


## <a id="means-formatting-font-effects"><b>means.formatting.font.effects</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.formatting</b>](#means-formatting) <- [<b>means.formatting.font</b>](#means-formatting-font) <- <b>means.formatting.font.effects</b>|


**Properties**

None


**Parameters**

None


## <a id="means-formatting-font-size"><b>means.formatting.font.size</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.formatting</b>](#means-formatting) <- [<b>means.formatting.font</b>](#means-formatting-font) <- <b>means.formatting.font.size</b>|


**Properties**

None


**Parameters**

None


## <a id="means-formatting-heading"><b>means.formatting.heading</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.formatting</b>](#means-formatting) <- <b>means.formatting.heading</b>|


**Properties**

None


**Parameters**

None


## <a id="means-formatting-order"><b>means.formatting.order</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.formatting</b>](#means-formatting) <- <b>means.formatting.order</b>|


**Properties**

None


**Parameters**

None


## <a id="means-formatting-stringformat"><b>means.formatting.stringFormat</b></a>


**Description**


Indicates this value represents the format of a string


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.formatting</b>](#means-formatting) <- <b>means.formatting.stringFormat</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea"><b>means.idea</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- <b>means.idea</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-account"><b>means.idea.account</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.account</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-accountleads"><b>means.idea.accountLeads</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.accountLeads</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-activityparty"><b>means.idea.activityParty</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.activityParty</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-activitypointer"><b>means.idea.activityPointer</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.activityPointer</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-annotation"><b>means.idea.annotation</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.annotation</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-appointment"><b>means.idea.appointment</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.appointment</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-brand"><b>means.idea.brand</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.brand</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-businessunit"><b>means.idea.businessUnit</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.businessUnit</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-campaign"><b>means.idea.campaign</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.campaign</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-campaignactivity"><b>means.idea.campaignActivity</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.campaignActivity</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-campaignitem"><b>means.idea.campaignItem</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.campaignItem</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-campaignresponse"><b>means.idea.campaignResponse</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.campaignResponse</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-channel"><b>means.idea.channel</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.channel</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-characteristic"><b>means.idea.characteristic</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.characteristic</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-company"><b>means.idea.company</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- [<b>means.idea.organization</b>](#means-idea-organization) <- <b>means.idea.company</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-competitor"><b>means.idea.competitor</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.competitor</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-competitoraddress"><b>means.idea.competitorAddress</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.competitorAddress</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-competitorproduct"><b>means.idea.competitorProduct</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.competitorProduct</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-connection"><b>means.idea.connection</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.connection</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-connectionrole"><b>means.idea.connectionRole</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.connectionRole</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-contract"><b>means.idea.contract</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.contract</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-contractdetail"><b>means.idea.contractDetail</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.contractDetail</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-customer"><b>means.idea.customer</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.customer</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-customeraddress"><b>means.idea.customerAddress</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.customerAddress</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-customerrelationship"><b>means.idea.customerRelationship</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.customerRelationship</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-discount"><b>means.idea.discount</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.discount</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-discounttype"><b>means.idea.discountType</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.discountType</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-email"><b>means.idea.email</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.email</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-employer"><b>means.idea.employer</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.employer</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-entitlement"><b>means.idea.entitlement</b></a>


| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.entitlement</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-equipment"><b>means.idea.equipment</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.equipment</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-fax"><b>means.idea.fax</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.fax</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-feedback"><b>means.idea.feedback</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.feedback</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-goal"><b>means.idea.goal</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.goal</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-incident"><b>means.idea.incident</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.incident</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-invoice"><b>means.idea.invoice</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.invoice</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-invoicedetail"><b>means.idea.invoiceDetail</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.invoiceDetail</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-kbarticle"><b>means.idea.KbArticle</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.KbArticle</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-knowledgearticle"><b>means.idea.knowledgeArticle</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.knowledgeArticle</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-lead"><b>means.idea.lead</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.lead</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-leadaddress"><b>means.idea.leadAddress</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.leadAddress</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-letter"><b>means.idea.letter</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.letter</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-metric"><b>means.idea.metric</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.metric</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-opportunity"><b>means.idea.opportunity</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.opportunity</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-organization"><b>means.idea.organization</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.organization</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-organization-unit"><b>means.idea.organization.unit</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.organization.unit</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-owner"><b>means.idea.owner</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.owner</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-person"><b>means.idea.person</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.person</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-person-contact"><b>means.idea.person.contact</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- [<b>means.idea.person</b>](#means-idea-person) <- <b>means.idea.person.contact</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-person-employee"><b>means.idea.person.employee</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- [<b>means.idea.person</b>](#means-idea-person) <- <b>means.idea.person.employee</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-person-representative"><b>means.idea.person.representative</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- [<b>means.idea.person</b>](#means-idea-person) <- <b>means.idea.person.representative</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-phonecall"><b>means.idea.phoneCall</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.phoneCall</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-place"><b>means.idea.place</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.place</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-position"><b>means.idea.position</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.position</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-pricelevel"><b>means.idea.priceLevel</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.priceLevel</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-product"><b>means.idea.product</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.product</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-productgroup"><b>means.idea.productGroup</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.productGroup</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-project"><b>means.idea.project</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.project</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-promotion"><b>means.idea.promotion</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.promotion</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-quote"><b>means.idea.quote</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.quote</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-ratingmodel"><b>means.idea.ratingModel</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.ratingModel</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-resource"><b>means.idea.resource</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.resource</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-resourcegroup"><b>means.idea.resourceGroup</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.resourceGroup</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-salesliterature"><b>means.idea.salesLiterature</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.salesLiterature</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-salesorder"><b>means.idea.salesOrder</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.salesOrder</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-scenario"><b>means.idea.scenario</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.scenario</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-schedule"><b>means.idea.schedule</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.schedule</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-service"><b>means.idea.service</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.service</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-service "><b>means.idea.service </b></a>


**Description**


Deprecated. extra space at the end was an error.




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- [<b>means.idea.service</b>](#means-idea-service) <- <b>means.idea.service </b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-serviceappointment"><b>means.idea.serviceAppointment</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.serviceAppointment</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-site"><b>means.idea.site</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.site</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-sla"><b>means.idea.SLA</b></a>


**Description**


A Service Level Agreement




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.SLA</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-socialactivity"><b>means.idea.socialActivity</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.socialActivity</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-socialprofile"><b>means.idea.socialProfile</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.socialProfile</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-systemuser"><b>means.idea.systemUser</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.systemUser</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-task"><b>means.idea.task</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.task</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-team"><b>means.idea.team</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.team</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-territory"><b>means.idea.territory</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.territory</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-uom"><b>means.idea.UoM</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.UoM</b>|


**Properties**

None


**Parameters**

None


## <a id="means-idea-utility"><b>means.idea.utility</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.idea</b>](#means-idea) <- <b>means.idea.utility</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity"><b>means.identity</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- <b>means.identity</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-barcode"><b>means.identity.barCode</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- <b>means.identity.barCode</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-brand"><b>means.identity.brand</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- <b>means.identity.brand</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-company-name"><b>means.identity.company.name</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- [<b>means.identity.name</b>](#means-identity-name) <- <b>means.identity.company.name</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-entityid"><b>means.identity.entityId</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- <b>means.identity.entityId</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-governmentid"><b>means.identity.governmentID</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- <b>means.identity.governmentID</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-ip4address"><b>means.identity.IP4Address</b></a>


**Description**


Internet Protocol V4 Address




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- <b>means.identity.IP4Address</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-ip6address"><b>means.identity.IP6Address</b></a>


**Description**


Internet Protocol V6 Address




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- <b>means.identity.IP6Address</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-name"><b>means.identity.name</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- <b>means.identity.name</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-person-firstname"><b>means.identity.person.firstName</b></a>


**Description**


A person's given or first name.




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- [<b>means.identity.name</b>](#means-identity-name) <- <b>means.identity.person.firstName</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-person-fullname"><b>means.identity.person.fullName</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- [<b>means.identity.name</b>](#means-identity-name) <- <b>means.identity.person.fullName</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-person-lastname"><b>means.identity.person.lastName</b></a>


**Description**


A person's surname, family name or last name.




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- [<b>means.identity.name</b>](#means-identity-name) <- <b>means.identity.person.lastName</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-person-middlename"><b>means.identity.person.middleName</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- [<b>means.identity.name</b>](#means-identity-name) <- <b>means.identity.person.middleName</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-person-prefix"><b>means.identity.person.prefix</b></a>


**Description**


A salutation such as a title, rank or honorific to place before a person's name




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- [<b>means.identity.name</b>](#means-identity-name) <- <b>means.identity.person.prefix</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-person-suffix"><b>means.identity.person.suffix</b></a>


**Description**


Follows a person's name and provides additional information about their position, education or honorific




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- [<b>means.identity.name</b>](#means-identity-name) <- <b>means.identity.person.suffix</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-rownumber"><b>means.identity.rowNumber</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- <b>means.identity.rowNumber</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-scd-originalidentity"><b>means.identity.scd.originalIdentity</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- <b>means.identity.scd.originalIdentity</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-scd-surogateidentity"><b>means.identity.scd.surogateIdentity</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- <b>means.identity.scd.surogateIdentity</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-service"><b>means.identity.service</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- <b>means.identity.service</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-service-email"><b>means.identity.service.email</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- <b>means.identity.service.email</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-service-facebook"><b>means.identity.service.facebook</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- <b>means.identity.service.facebook</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-service-phone"><b>means.identity.service.phone</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- <b>means.identity.service.phone</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-service-phone-cell"><b>means.identity.service.phone.cell</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- <b>means.identity.service.phone.cell</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-service-phone-fax"><b>means.identity.service.phone.fax</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- <b>means.identity.service.phone.fax</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-service-twitter"><b>means.identity.service.twitter</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- <b>means.identity.service.twitter</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-sku"><b>means.identity.SKU</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- <b>means.identity.SKU</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-tickersymbol"><b>means.identity.tickerSymbol</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- <b>means.identity.tickerSymbol</b>|


**Properties**

None


**Parameters**

None


## <a id="means-identity-title"><b>means.identity.title</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.identity</b>](#means-identity) <- <b>means.identity.title</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location"><b>means.location</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- <b>means.location</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-address"><b>means.location.address</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- <b>means.location.address</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-address-building"><b>means.location.address.building</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.address</b>](#means-location-address) <- <b>means.location.address.building</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-address-floor"><b>means.location.address.floor</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.address</b>](#means-location-address) <- <b>means.location.address.floor</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-address-house"><b>means.location.address.house</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.address</b>](#means-location-address) <- <b>means.location.address.house</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-address-room"><b>means.location.address.room</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.address</b>](#means-location-address) <- <b>means.location.address.room</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-address-street"><b>means.location.address.street</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.address</b>](#means-location-address) <- <b>means.location.address.street</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-address-street-line1"><b>means.location.address.street.line1</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.address</b>](#means-location-address) <- [<b>means.location.address.street</b>](#means-location-address-street) <- <b>means.location.address.street.line1</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-address-street-line2"><b>means.location.address.street.line2</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.address</b>](#means-location-address) <- [<b>means.location.address.street</b>](#means-location-address-street) <- <b>means.location.address.street.line2</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-address-street-line3"><b>means.location.address.street.line3</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.address</b>](#means-location-address) <- [<b>means.location.address.street</b>](#means-location-address-street) <- <b>means.location.address.street.line3</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-city"><b>means.location.city</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- <b>means.location.city</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-continent"><b>means.location.continent</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- <b>means.location.continent</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-country"><b>means.location.country</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- <b>means.location.country</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-county"><b>means.location.county</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.address</b>](#means-location-address) <- <b>means.location.county</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-geo"><b>means.location.geo</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- <b>means.location.geo</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-geo-boundary"><b>means.location.geo.boundary</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.geo</b>](#means-location-geo) <- <b>means.location.geo.boundary</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-geo-boundary-bottom"><b>means.location.geo.boundary.bottom</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.geo</b>](#means-location-geo) <- [<b>means.location.geo.boundary</b>](#means-location-geo-boundary) <- <b>means.location.geo.boundary.bottom</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-geo-boundary-front"><b>means.location.geo.boundary.front</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.geo</b>](#means-location-geo) <- [<b>means.location.geo.boundary</b>](#means-location-geo-boundary) <- <b>means.location.geo.boundary.front</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-geo-boundary-left"><b>means.location.geo.boundary.left</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.geo</b>](#means-location-geo) <- [<b>means.location.geo.boundary</b>](#means-location-geo-boundary) <- <b>means.location.geo.boundary.left</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-geo-boundary-polygon"><b>means.location.geo.boundary.polygon</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.geo</b>](#means-location-geo) <- [<b>means.location.geo.boundary</b>](#means-location-geo-boundary) <- <b>means.location.geo.boundary.polygon</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-geo-boundary-rear"><b>means.location.geo.boundary.rear</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.geo</b>](#means-location-geo) <- [<b>means.location.geo.boundary</b>](#means-location-geo-boundary) <- <b>means.location.geo.boundary.rear</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-geo-boundary-right"><b>means.location.geo.boundary.right</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.geo</b>](#means-location-geo) <- [<b>means.location.geo.boundary</b>](#means-location-geo-boundary) <- <b>means.location.geo.boundary.right</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-geo-boundary-top"><b>means.location.geo.boundary.top</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.geo</b>](#means-location-geo) <- [<b>means.location.geo.boundary</b>](#means-location-geo-boundary) <- <b>means.location.geo.boundary.top</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-geo-centroid"><b>means.location.geo.centroid</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.geo</b>](#means-location-geo) <- <b>means.location.geo.centroid</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-geo-centroid-x"><b>means.location.geo.centroid.X</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.geo</b>](#means-location-geo) <- [<b>means.location.geo.centroid</b>](#means-location-geo-centroid) <- <b>means.location.geo.centroid.X</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-geo-centroid-y"><b>means.location.geo.centroid.y</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.geo</b>](#means-location-geo) <- [<b>means.location.geo.centroid</b>](#means-location-geo-centroid) <- <b>means.location.geo.centroid.y</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-geo-centroid-z"><b>means.location.geo.centroid.z</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- [<b>means.location.geo</b>](#means-location-geo) <- [<b>means.location.geo.centroid</b>](#means-location-geo-centroid) <- <b>means.location.geo.centroid.z</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-latitude"><b>means.location.latitude</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- <b>means.location.latitude</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-longitude"><b>means.location.longitude</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- <b>means.location.longitude</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-point"><b>means.location.point</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- <b>means.location.point</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-postalcode"><b>means.location.postalCode</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- <b>means.location.postalCode</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-province"><b>means.location.province</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- <b>means.location.province</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-region"><b>means.location.region</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- <b>means.location.region</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-stateorprovince"><b>means.location.stateOrProvince</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- <b>means.location.stateOrProvince</b>|


**Properties**

None


**Parameters**

None


## <a id="means-location-timezone"><b>means.location.timezone</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.location</b>](#means-location) <- <b>means.location.timezone</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement"><b>means.measurement</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- <b>means.measurement</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-age"><b>means.measurement.age</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.age</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-code"><b>means.measurement.code</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.code</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-color"><b>means.measurement.color</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.color</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-count"><b>means.measurement.count</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.count</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-currency"><b>means.measurement.currency</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.currency</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-currency-cost"><b>means.measurement.currency.cost</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.currency</b>](#means-measurement-currency) <- <b>means.measurement.currency.cost</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-currency-isocode"><b>means.measurement.currency.iSOCode</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.currency.iSOCode</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-currency-price"><b>means.measurement.currency.price</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.currency</b>](#means-measurement-currency) <- <b>means.measurement.currency.price</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-currency-revenue"><b>means.measurement.currency.revenue</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.currency</b>](#means-measurement-currency) <- <b>means.measurement.currency.revenue</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-currency-type"><b>means.measurement.currency.type</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.currency.type</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-currency-type-destination"><b>means.measurement.currency.type.destination</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.currency.type</b>](#means-measurement-currency-type) <- <b>means.measurement.currency.type.destination</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-currency-type-source"><b>means.measurement.currency.type.source</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.currency.type</b>](#means-measurement-currency-type) <- <b>means.measurement.currency.type.source</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-currencycode"><b>means.measurement.currencyCode</b></a>


**Description**


Indicates this value represents an ISO 4217 currency code




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.currencyCode</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-date"><b>means.measurement.date</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.date</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-date-completion"><b>means.measurement.date.completion</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.date</b>](#means-measurement-date) <- <b>means.measurement.date.completion</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-date-creation"><b>means.measurement.date.creation</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.date</b>](#means-measurement-date) <- <b>means.measurement.date.creation</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-date-end"><b>means.measurement.date.end</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.date</b>](#means-measurement-date) <- <b>means.measurement.date.end</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-date-end-scd"><b>means.measurement.date.end.scd</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.date</b>](#means-measurement-date) <- <b>means.measurement.date.end.scd</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-date-modify"><b>means.measurement.date.modify</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.date</b>](#means-measurement-date) <- <b>means.measurement.date.modify</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-date-occurrence"><b>means.measurement.date.occurrence</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.date</b>](#means-measurement-date) <- <b>means.measurement.date.occurrence</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-date-remove"><b>means.measurement.date.remove</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.date</b>](#means-measurement-date) <- <b>means.measurement.date.remove</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-date-start"><b>means.measurement.date.start</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.date</b>](#means-measurement-date) <- <b>means.measurement.date.start</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-date-start-scd"><b>means.measurement.date.start.scd</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.date</b>](#means-measurement-date) <- <b>means.measurement.date.start.scd</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-date-target"><b>means.measurement.date.target</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.date</b>](#means-measurement-date) <- <b>means.measurement.date.target</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-density"><b>means.measurement.density</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.density</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-dimension"><b>means.measurement.dimension</b></a>


**Description**


Measurement of some physical dimension




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.dimension</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|dimension|string|False


## <a id="means-measurement-dimension-amount"><b>means.measurement.dimension.amount</b></a>


**Description**


Measurement of amount of substance




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- <b>means.measurement.dimension.amount</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-dimension-angle"><b>means.measurement.dimension.angle</b></a>


**Description**


Measurement of geometric angle




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- <b>means.measurement.dimension.angle</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-dimension-capacitance"><b>means.measurement.dimension.capacitance</b></a>


**Description**


Measurement of electical capacitance




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- <b>means.measurement.dimension.capacitance</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-dimension-datarate"><b>means.measurement.dimension.dataRate</b></a>


**Description**


Measurement of data rate




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- <b>means.measurement.dimension.dataRate</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-dimension-electriccharge"><b>means.measurement.dimension.electricCharge</b></a>


**Description**


Measurement of electric charge, quantity of electricity




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- <b>means.measurement.dimension.electricCharge</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-dimension-electriccurrent"><b>means.measurement.dimension.electricCurrent</b></a>


**Description**


Measurement of electic current




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- <b>means.measurement.dimension.electricCurrent</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-dimension-electromotiveforce"><b>means.measurement.dimension.electromotiveForce</b></a>


**Description**


Measurement of volatage, EMF, electrical potential difference




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- <b>means.measurement.dimension.electromotiveForce</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-dimension-energy"><b>means.measurement.dimension.energy</b></a>


**Description**


Measurement of energy, work, heat




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- <b>means.measurement.dimension.energy</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-dimension-force"><b>means.measurement.dimension.force</b></a>


**Description**


Measurement of force




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- <b>means.measurement.dimension.force</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-dimension-frequency"><b>means.measurement.dimension.frequency</b></a>


**Description**


Measurement of frequency




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- <b>means.measurement.dimension.frequency</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-dimension-length"><b>means.measurement.dimension.length</b></a>


**Description**


Measurement of length




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- <b>means.measurement.dimension.length</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-dimension-luminousintensity"><b>means.measurement.dimension.luminousIntensity</b></a>


**Description**


Measurement of electic current




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- <b>means.measurement.dimension.luminousIntensity</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-dimension-mass"><b>means.measurement.dimension.mass</b></a>


**Description**


Measurement of mass




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- <b>means.measurement.dimension.mass</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-dimension-power"><b>means.measurement.dimension.power</b></a>


**Description**


Measurement of power, radiant flex




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- <b>means.measurement.dimension.power</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-dimension-pressure"><b>means.measurement.dimension.pressure</b></a>


**Description**


Measurement of pressure or stress




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- <b>means.measurement.dimension.pressure</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-dimension-resistance"><b>means.measurement.dimension.resistance</b></a>


**Description**


Measurement of electrical resistance, impedance, reactance




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- <b>means.measurement.dimension.resistance</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-dimension-temperature"><b>means.measurement.dimension.temperature</b></a>


**Description**


Measurement of thermodynamic temperature




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- <b>means.measurement.dimension.temperature</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-dimension-time"><b>means.measurement.dimension.time</b></a>


**Description**


Measurement of time




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- <b>means.measurement.dimension.time</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-distance"><b>means.measurement.distance</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- [<b>means.measurement.dimension.length</b>](#means-measurement-dimension-length) <- <b>means.measurement.distance</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-distance-cm"><b>means.measurement.distance.cm</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- [<b>means.measurement.dimension.length</b>](#means-measurement-dimension-length) <- [<b>means.measurement.distance</b>](#means-measurement-distance) <- <b>means.measurement.distance.cm</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-distance-inches"><b>means.measurement.distance.inches</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- [<b>means.measurement.dimension.length</b>](#means-measurement-dimension-length) <- [<b>means.measurement.distance</b>](#means-measurement-distance) <- <b>means.measurement.distance.inches</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-duration"><b>means.measurement.duration</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.duration</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-duration-days"><b>means.measurement.duration.days</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.duration</b>](#means-measurement-duration) <- <b>means.measurement.duration.days</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-duration-hours"><b>means.measurement.duration.hours</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.duration</b>](#means-measurement-duration) <- <b>means.measurement.duration.hours</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-duration-minutes"><b>means.measurement.duration.minutes</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.duration</b>](#means-measurement-duration) <- <b>means.measurement.duration.minutes</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-duration-months"><b>means.measurement.duration.months</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.duration</b>](#means-measurement-duration) <- <b>means.measurement.duration.months</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-duration-quarters"><b>means.measurement.duration.quarters</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.duration</b>](#means-measurement-duration) <- <b>means.measurement.duration.quarters</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-duration-seconds"><b>means.measurement.duration.seconds</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.duration</b>](#means-measurement-duration) <- <b>means.measurement.duration.seconds</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-duration-trimesters"><b>means.measurement.duration.trimesters</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.duration</b>](#means-measurement-duration) <- <b>means.measurement.duration.trimesters</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-duration-weeks"><b>means.measurement.duration.weeks</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.duration</b>](#means-measurement-duration) <- <b>means.measurement.duration.weeks</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-duration-years"><b>means.measurement.duration.years</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.duration</b>](#means-measurement-duration) <- <b>means.measurement.duration.years</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-percent"><b>means.measurement.percent</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.percent</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-percent-ownership"><b>means.measurement.percent.ownership</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.percent.ownership</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-percent-voterright"><b>means.measurement.percent.voterright</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.percent.voterright</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-prefix"><b>means.measurement.prefix</b></a>


**Description**


Unit prefixes denoting a factor of one thousandth




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.prefix</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|scaleExponent|double|False


## <a id="means-measurement-prefix-centi"><b>means.measurement.prefix.centi</b></a>


**Description**


Denotes one thousanth of the unit; 10E-2




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.prefix</b>](#means-measurement-prefix) <- <b>means.measurement.prefix.centi</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-prefix-giga"><b>means.measurement.prefix.giga</b></a>


**Description**


Denotes one thousanth of the unit; 10E9




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.prefix</b>](#means-measurement-prefix) <- <b>means.measurement.prefix.giga</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-prefix-kilo"><b>means.measurement.prefix.kilo</b></a>


**Description**


Denotes one thousanth of the unit; 10E3




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.prefix</b>](#means-measurement-prefix) <- <b>means.measurement.prefix.kilo</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-prefix-mega"><b>means.measurement.prefix.mega</b></a>


**Description**


Denotes one thousanth of the unit; 10E6




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.prefix</b>](#means-measurement-prefix) <- <b>means.measurement.prefix.mega</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-prefix-micro"><b>means.measurement.prefix.micro</b></a>


**Description**


Denotes one thousanth of the unit; 10E-6




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.prefix</b>](#means-measurement-prefix) <- <b>means.measurement.prefix.micro</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-prefix-milli"><b>means.measurement.prefix.milli</b></a>


**Description**


Denotes one thousanth of the unit; 10E-3




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.prefix</b>](#means-measurement-prefix) <- <b>means.measurement.prefix.milli</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-prefix-nano"><b>means.measurement.prefix.nano</b></a>


**Description**


Denotes one thousanth of the unit; 10E-9




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.prefix</b>](#means-measurement-prefix) <- <b>means.measurement.prefix.nano</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-prefix-pico"><b>means.measurement.prefix.pico</b></a>


**Description**


Denotes one thousanth of the unit; 10E-12




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.prefix</b>](#means-measurement-prefix) <- <b>means.measurement.prefix.pico</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-probability"><b>means.measurement.probability</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.probability</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-range"><b>means.measurement.range</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.range</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-range-high"><b>means.measurement.range.high</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.range</b>](#means-measurement-range) <- <b>means.measurement.range.high</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-range-low"><b>means.measurement.range.low</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.range</b>](#means-measurement-range) <- <b>means.measurement.range.low</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-rate"><b>means.measurement.rate</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.rate</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-rate-type"><b>means.measurement.rate.type</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.rate.type</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-sequence"><b>means.measurement.sequence</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.sequence</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-size"><b>means.measurement.size</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.size</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-size-depth"><b>means.measurement.size.depth</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.size</b>](#means-measurement-size) <- <b>means.measurement.size.depth</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-size-height"><b>means.measurement.size.height</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.size</b>](#means-measurement-size) <- <b>means.measurement.size.height</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-size-volume"><b>means.measurement.size.volume</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.size</b>](#means-measurement-size) <- <b>means.measurement.size.volume</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-size-width"><b>means.measurement.size.width</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.size</b>](#means-measurement-size) <- <b>means.measurement.size.width</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-temperature"><b>means.measurement.temperature</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- [<b>means.measurement.dimension.temperature</b>](#means-measurement-dimension-temperature) <- <b>means.measurement.temperature</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-time"><b>means.measurement.time</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.time</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-degree"><b>means.measurement.units.degree</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.units.degree</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-si"><b>means.measurement.units.si</b></a>


**Description**


Measurments in international system of units




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- <b>means.measurement.units.si</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|unit|string|False
|dimension|string|False
|symbol|string|False


## <a id="means-measurement-units-si-ampere"><b>means.measurement.units.si.ampere</b></a>


**Description**


Measurement of electric current in amperes




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement.units.si</b>](#means-measurement-units-si) <- <b>means.measurement.units.si.ampere</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-si-bitpersecond"><b>means.measurement.units.si.bitPerSecond</b></a>


**Description**


Measurement of data rate in bits per second




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement.units.si</b>](#means-measurement-units-si) <- <b>means.measurement.units.si.bitPerSecond</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-si-candela"><b>means.measurement.units.si.candela</b></a>


**Description**


Measurement of luminous intensity in candelas




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement.units.si</b>](#means-measurement-units-si) <- <b>means.measurement.units.si.candela</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-si-celsius"><b>means.measurement.units.si.celsius</b></a>


**Description**


Measurement of temperature in degrees celsius




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement.units.si</b>](#means-measurement-units-si) <- <b>means.measurement.units.si.celsius</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-si-coulomb"><b>means.measurement.units.si.coulomb</b></a>


**Description**


Measurement of electric charge or amount of electricity in coulombs




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement.units.si</b>](#means-measurement-units-si) <- <b>means.measurement.units.si.coulomb</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-si-farad"><b>means.measurement.units.si.farad</b></a>


**Description**


Measurement of electric capacitance in farads




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement.units.si</b>](#means-measurement-units-si) <- <b>means.measurement.units.si.farad</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-si-gram"><b>means.measurement.units.si.gram</b></a>


**Description**


Measurement of mass in grams




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement.units.si</b>](#means-measurement-units-si) <- <b>means.measurement.units.si.gram</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-si-hertz"><b>means.measurement.units.si.hertz</b></a>


**Description**


Measurement of frequency in hertz




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement.units.si</b>](#means-measurement-units-si) <- <b>means.measurement.units.si.hertz</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-si-joule"><b>means.measurement.units.si.joule</b></a>


**Description**


Measurement of energy, work or heat in joules




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement.units.si</b>](#means-measurement-units-si) <- <b>means.measurement.units.si.joule</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-si-kelvin"><b>means.measurement.units.si.kelvin</b></a>


**Description**


Measurement of thermodynamic temperature in degrees kelvin




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement.units.si</b>](#means-measurement-units-si) <- <b>means.measurement.units.si.kelvin</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-si-kilogram"><b>means.measurement.units.si.kilogram</b></a>


**Description**


Measurement of mass in kilogram




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement.units.si</b>](#means-measurement-units-si) <- <b>means.measurement.units.si.kilogram</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-si-meter"><b>means.measurement.units.si.meter</b></a>


**Description**


Measurement of length in meters




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement.units.si</b>](#means-measurement-units-si) <- <b>means.measurement.units.si.meter</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-si-mole"><b>means.measurement.units.si.mole</b></a>


**Description**


Measurement of amount in moles




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement.units.si</b>](#means-measurement-units-si) <- <b>means.measurement.units.si.mole</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-si-newton"><b>means.measurement.units.si.newton</b></a>


**Description**


Measurement of force or weight in newtons




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement.units.si</b>](#means-measurement-units-si) <- <b>means.measurement.units.si.newton</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-si-ohm"><b>means.measurement.units.si.ohm</b></a>


**Description**


Measurement of electrical resistance, impedance, reactance in ohms




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement.units.si</b>](#means-measurement-units-si) <- <b>means.measurement.units.si.ohm</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-si-pascal"><b>means.measurement.units.si.pascal</b></a>


**Description**


Measurement of pressure or stress in pascals




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement.units.si</b>](#means-measurement-units-si) <- <b>means.measurement.units.si.pascal</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-si-radian"><b>means.measurement.units.si.radian</b></a>


**Description**


Measurement of angle in radians




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement.units.si</b>](#means-measurement-units-si) <- <b>means.measurement.units.si.radian</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-si-second"><b>means.measurement.units.si.second</b></a>


**Description**


Measurement of time in seconds




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement.units.si</b>](#means-measurement-units-si) <- <b>means.measurement.units.si.second</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-si-volt"><b>means.measurement.units.si.volt</b></a>


**Description**


Measurement of voltage, EMF, electrical potantial difference in volts




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement.units.si</b>](#means-measurement-units-si) <- <b>means.measurement.units.si.volt</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-units-si-watt"><b>means.measurement.units.si.watt</b></a>


**Description**


Measurement of power or radiant flux in watts




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement.units.si</b>](#means-measurement-units-si) <- <b>means.measurement.units.si.watt</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-version"><b>means.measurement.version</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- <b>means.measurement.version</b>|


**Properties**

None


**Parameters**

None


## <a id="means-measurement-weight"><b>means.measurement.weight</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.measurement</b>](#means-measurement) <- [<b>means.measurement.dimension</b>](#means-measurement-dimension) <- [<b>means.measurement.dimension.force</b>](#means-measurement-dimension-force) <- <b>means.measurement.weight</b>|


**Properties**

None


**Parameters**

None


## <a id="means-qualification"><b>means.qualification</b></a>


**Description**


Augments the meaning of entities or attributes with a qualification




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- <b>means.qualification</b>|


**Properties**

None


**Parameters**

None


## <a id="means-qualification-estimate"><b>means.qualification.estimate</b></a>


**Description**


Values are an estimate only.




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.qualification</b>](#means-qualification) <- <b>means.qualification.estimate</b>|


**Properties**

None


**Parameters**

None


## <a id="means-reference"><b>means.reference</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- <b>means.reference</b>|


**Properties**

None


**Parameters**

None


## <a id="means-reference-caption"><b>means.reference.caption</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.reference</b>](#means-reference) <- <b>means.reference.caption</b>|


**Properties**

None


**Parameters**

None


## <a id="means-reference-culture"><b>means.reference.culture</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.reference</b>](#means-reference) <- <b>means.reference.culture</b>|


**Properties**

None


**Parameters**

None


## <a id="means-reference-culture-tag"><b>means.reference.culture.tag</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.reference</b>](#means-reference) <- [<b>means.reference.culture</b>](#means-reference-culture) <- <b>means.reference.culture.tag</b>|


**Properties**

None


**Parameters**

None


## <a id="means-reference-definition"><b>means.reference.definition</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.reference</b>](#means-reference) <- <b>means.reference.definition</b>|


**Properties**

None


**Parameters**

None


## <a id="means-reference-description"><b>means.reference.description</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.reference</b>](#means-reference) <- <b>means.reference.description</b>|


**Properties**

None


**Parameters**

None


## <a id="means-reference-displaytext"><b>means.reference.displayText</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.reference</b>](#means-reference) <- <b>means.reference.displayText</b>|


**Properties**

None


**Parameters**

None


## <a id="means-reference-documentation"><b>means.reference.documentation</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.reference</b>](#means-reference) <- <b>means.reference.documentation</b>|


**Properties**

None


**Parameters**

None


## <a id="means-reference-language"><b>means.reference.language</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.reference</b>](#means-reference) <- <b>means.reference.language</b>|


**Properties**

None


**Parameters**

None


## <a id="means-reference-language-tag"><b>means.reference.language.tag</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.reference</b>](#means-reference) <- [<b>means.reference.language</b>](#means-reference-language) <- <b>means.reference.language.tag</b>|


**Properties**

None


**Parameters**

None


## <a id="means-reference-phonetic"><b>means.reference.phonetic</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.reference</b>](#means-reference) <- <b>means.reference.phonetic</b>|


**Properties**

None


**Parameters**

None


## <a id="means-reference-regarding"><b>means.reference.regarding</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.reference</b>](#means-reference) <- <b>means.reference.regarding</b>|


**Properties**

None


**Parameters**

None


## <a id="means-reference-uri"><b>means.reference.URI</b></a>


**Description**


A Uniform Resource Identifier




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.reference</b>](#means-reference) <- <b>means.reference.URI</b>|


**Properties**

None


**Parameters**

None


## <a id="means-reference-url"><b>means.reference.URL</b></a>


**Description**


A Uniform Resource Locator. A web address.




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.reference</b>](#means-reference) <- <b>means.reference.URL</b>|


**Properties**

None


**Parameters**

None


## <a id="means-reference-url-image"><b>means.reference.URL.image</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.reference</b>](#means-reference) <- [<b>means.reference.URL</b>](#means-reference-url) <- <b>means.reference.URL.image</b>|


**Properties**

None


**Parameters**

None


## <a id="means-relationship"><b>means.relationship</b></a>


**Description**


Root trait for semantic traits relevant to relationships




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- <b>means.relationship</b>|


**Properties**

None


**Parameters**

None


## <a id="means-relationship-child"><b>means.relationship.child</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.relationship</b>](#means-relationship) <- <b>means.relationship.child</b>|


**Properties**

None


**Parameters**

None


## <a id="means-relationship-inverseverbphrase"><b>means.relationship.inverseVerbPhrase</b></a>


**Description**


The Verb Phrase used to model the relationship between the TO entity and the FROM entity.




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.relationship</b>](#means-relationship) <- <b>means.relationship.inverseVerbPhrase</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|verbPhrase|entity|False


## <a id="means-relationship-parent"><b>means.relationship.parent</b></a>




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.relationship</b>](#means-relationship) <- <b>means.relationship.parent</b>|


**Properties**

None


**Parameters**

None


## <a id="means-relationship-verbphrase"><b>means.relationship.verbPhrase</b></a>


**Description**


The Verb Phrase used to model the relationship between the FROM entity and the TO entity.




| Inheritance |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.relationship</b>](#means-relationship) <- <b>means.relationship.verbPhrase</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|verbPhrase|entity|False


## <a id="means-time"><b>means.time</b></a>


**Inheritance**

| |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- <b>means.time</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|units|string|False
|hasUTC|boolean|False


## <a id="means-time-parquet-micro"><b>means.time.parquet.micro</b></a>


**Inheritance**

| |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.time</b>](#means-time) <- <b>means.time.parquet.micro</b>|


**Properties**

None


**Parameters**

None


## <a id="means-time-parquet-milli"><b>means.time.parquet.milli</b></a>


**Inheritance**

| |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.time</b>](#means-time) <- <b>means.time.parquet.milli</b>|


**Properties**

None


**Parameters**

None


## <a id="means-time-parquet-nano"><b>means.time.parquet.nano</b></a>


**Inheritance**

| |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.time</b>](#means-time) <- <b>means.time.parquet.nano</b>|


**Properties**

None


**Parameters**

None


## <a id="means-timestamp"><b>means.timestamp</b></a>


**Inheritance**

| |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- <b>means.timestamp</b>|


**Properties**

None


**Parameters**

| **Name** | **Type** | **Required** |
|--|--|--|
|units|string|False
|offsetFromDate|dateTime|False
|hasUTC|boolean|False


## <a id="means-timestamp-parquet-micro"><b>means.timestamp.parquet.micro</b></a>


**Inheritance**

| |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.timestamp</b>](#means-timestamp) <- <b>means.timestamp.parquet.micro</b>|


**Properties**

None


**Parameters**

None


## <a id="means-timestamp-parquet-milli"><b>means.timestamp.parquet.milli</b></a>


**Inheritance**

| |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.timestamp</b>](#means-timestamp) <- <b>means.timestamp.parquet.milli</b>|


**Properties**

None


**Parameters**

None


## <a id="means-timestamp-parquet-nano"><b>means.timestamp.parquet.nano</b></a>


**Inheritance**

| |
|--|
|[<b>is</b>](#is) <- [<b>means</b>](#means) <- [<b>means.timestamp</b>](#means-timestamp) <- <b>means.timestamp.parquet.nano</b>|


**Properties**

None


**Parameters**

None


## <a id="means-userid"><b>means.userId</b></a>


**Description**


Contains a userId




None


**Properties**

None


**Parameters**

None


## <a id="privacy"><b>privacy</b></a>


**Description**


A privacy related trait.




None


**Properties**

None


**Parameters**

None


## <a id="privacy-consentrequirements"><b>privacy.consentRequirements</b></a>


**Description**


The consent requirements or consent settings for data




| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- <b>privacy.consentRequirements</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-consentrequirements-customercontrols"><b>privacy.consentRequirements.customerControls</b></a>




| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.consentRequirements</b>](#privacy-consentrequirements) <- <b>privacy.consentRequirements.customerControls</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-consentrequirements-customercontrols-notrequired"><b>privacy.consentRequirements.customerControls.notRequired</b></a>




| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.consentRequirements</b>](#privacy-consentrequirements) <- [<b>privacy.consentRequirements.customerControls</b>](#privacy-consentrequirements-customercontrols) <- <b>privacy.consentRequirements.customerControls.notRequired</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-consentrequirements-customercontrols-required"><b>privacy.consentRequirements.customerControls.required</b></a>




| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.consentRequirements</b>](#privacy-consentrequirements) <- [<b>privacy.consentRequirements.customerControls</b>](#privacy-consentrequirements-customercontrols) <- <b>privacy.consentRequirements.customerControls.required</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-consentrequirements-legitimateinterest"><b>privacy.consentRequirements.legitimateInterest</b></a>




| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.consentRequirements</b>](#privacy-consentrequirements) <- <b>privacy.consentRequirements.legitimateInterest</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-consentrequirements-notice"><b>privacy.consentRequirements.notice</b></a>




| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.consentRequirements</b>](#privacy-consentrequirements) <- <b>privacy.consentRequirements.notice</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-consentrequirements-notice-discoverable"><b>privacy.consentRequirements.notice.discoverable</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.consentRequirements</b>](#privacy-consentrequirements) <- [<b>privacy.consentRequirements.notice</b>](#privacy-consentrequirements-notice) <- <b>privacy.consentRequirements.notice.discoverable</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-consentrequirements-notice-prominent"><b>privacy.consentRequirements.notice.prominent</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.consentRequirements</b>](#privacy-consentrequirements) <- [<b>privacy.consentRequirements.notice</b>](#privacy-consentrequirements-notice) <- <b>privacy.consentRequirements.notice.prominent</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-consentrequirements-notpermitted"><b>privacy.consentRequirements.notPermitted</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.consentRequirements</b>](#privacy-consentrequirements) <- <b>privacy.consentRequirements.notPermitted</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-consentrequirements-optin"><b>privacy.consentRequirements.optIn</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.consentRequirements</b>](#privacy-consentrequirements) <- <b>privacy.consentRequirements.optIn</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-consentrequirements-optout"><b>privacy.consentRequirements.optOut</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.consentRequirements</b>](#privacy-consentrequirements) <- <b>privacy.consentRequirements.optOut</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory"><b>privacy.dataCategory</b></a>


**Description**


The root trait for expressing 'Controller' data categories


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- <b>privacy.dataCategory</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-bizops"><b>privacy.dataCategory.bizOps</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- <b>privacy.dataCategory.bizOps</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-bizops-corporatecommunication"><b>privacy.dataCategory.bizOps.corporateCommunication</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.bizOps</b>](#privacy-datacategory-bizops) <- <b>privacy.dataCategory.bizOps.corporateCommunication</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-bizops-financeaccountingandrecords"><b>privacy.dataCategory.bizOps.financeAccountingAndRecords</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.bizOps</b>](#privacy-datacategory-bizops) <- <b>privacy.dataCategory.bizOps.financeAccountingAndRecords</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-customerowned"><b>privacy.dataCategory.customerOwned</b></a>


**Description**


The root trait for expressing 'Processor' data categories


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- <b>privacy.dataCategory.customerOwned</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-customerowned-account"><b>privacy.dataCategory.customerOwned.account</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.customerOwned</b>](#privacy-datacategory-customerowned) <- <b>privacy.dataCategory.customerOwned.account</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-customerowned-account-customercontact"><b>privacy.dataCategory.customerOwned.account.customerContact</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.customerOwned</b>](#privacy-datacategory-customerowned) <- [<b>privacy.dataCategory.customerOwned.account</b>](#privacy-datacategory-customerowned-account) <- <b>privacy.dataCategory.customerOwned.account.customerContact</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-customerowned-account-licensingandpurchase"><b>privacy.dataCategory.customerOwned.account.licensingAndPurchase</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.customerOwned</b>](#privacy-datacategory-customerowned) <- [<b>privacy.dataCategory.customerOwned.account</b>](#privacy-datacategory-customerowned-account) <- <b>privacy.dataCategory.customerOwned.account.licensingAndPurchase</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-customerowned-account-paymentinstrument"><b>privacy.dataCategory.customerOwned.account.paymentInstrument</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.customerOwned</b>](#privacy-datacategory-customerowned) <- [<b>privacy.dataCategory.customerOwned.account</b>](#privacy-datacategory-customerowned-account) <- <b>privacy.dataCategory.customerOwned.account.paymentInstrument</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-customerowned-content"><b>privacy.dataCategory.customerOwned.content</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.customerOwned</b>](#privacy-datacategory-customerowned) <- <b>privacy.dataCategory.customerOwned.content</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-customerowned-content-contactlist"><b>privacy.dataCategory.customerOwned.content.contactList</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.customerOwned</b>](#privacy-datacategory-customerowned) <- [<b>privacy.dataCategory.customerOwned.content</b>](#privacy-datacategory-customerowned-content) <- <b>privacy.dataCategory.customerOwned.content.contactList</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-customerowned-content-credentials"><b>privacy.dataCategory.customerOwned.content.credentials</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.customerOwned</b>](#privacy-datacategory-customerowned) <- [<b>privacy.dataCategory.customerOwned.content</b>](#privacy-datacategory-customerowned-content) <- <b>privacy.dataCategory.customerOwned.content.credentials</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-customerowned-content-provided"><b>privacy.dataCategory.customerOwned.content.provided</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.customerOwned</b>](#privacy-datacategory-customerowned) <- [<b>privacy.dataCategory.customerOwned.content</b>](#privacy-datacategory-customerowned-content) <- <b>privacy.dataCategory.customerOwned.content.provided</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-customerowned-corporatecommunication"><b>privacy.dataCategory.customerOwned.corporateCommunication</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.customerOwned</b>](#privacy-datacategory-customerowned) <- <b>privacy.dataCategory.customerOwned.corporateCommunication</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-customerowned-enduseridentifying"><b>privacy.dataCategory.customerOwned.endUserIdentifying</b></a>



| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.customerOwned</b>](#privacy-datacategory-customerowned) <- <b>privacy.dataCategory.customerOwned.endUserIdentifying</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-customerowned-financeaccountingandrecords"><b>privacy.dataCategory.customerOwned.financeAccountingAndRecords</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.customerOwned</b>](#privacy-datacategory-customerowned) <- <b>privacy.dataCategory.customerOwned.financeAccountingAndRecords</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-customerowned-publicpersonaldata"><b>privacy.dataCategory.customerOwned.publicPersonalData</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.customerOwned</b>](#privacy-datacategory-customerowned) <- <b>privacy.dataCategory.customerOwned.publicPersonalData</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-customerowned-support"><b>privacy.dataCategory.customerOwned.support</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.customerOwned</b>](#privacy-datacategory-customerowned) <- <b>privacy.dataCategory.customerOwned.support</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-customerowned-support-content"><b>privacy.dataCategory.customerOwned.support.content</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.customerOwned</b>](#privacy-datacategory-customerowned) <- [<b>privacy.dataCategory.customerOwned.support</b>](#privacy-datacategory-customerowned-support) <- <b>privacy.dataCategory.customerOwned.support.content</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-customerowned-support-interaction"><b>privacy.dataCategory.customerOwned.support.interaction</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.customerOwned</b>](#privacy-datacategory-customerowned) <- [<b>privacy.dataCategory.customerOwned.support</b>](#privacy-datacategory-customerowned-support) <- <b>privacy.dataCategory.customerOwned.support.interaction</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-employment"><b>privacy.dataCategory.employment</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- <b>privacy.dataCategory.employment</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-employment-commuteandtravel"><b>privacy.dataCategory.employment.commuteAndTravel</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.employment</b>](#privacy-datacategory-employment) <- <b>privacy.dataCategory.employment.commuteAndTravel</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-employment-compensationandbenefits"><b>privacy.dataCategory.employment.compensationAndBenefits</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.employment</b>](#privacy-datacategory-employment) <- <b>privacy.dataCategory.employment.compensationAndBenefits</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-employment-learninganddevelopment"><b>privacy.dataCategory.employment.learningAndDevelopment</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.employment</b>](#privacy-datacategory-employment) <- <b>privacy.dataCategory.employment.learningAndDevelopment</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-employment-profesionalandpersonalprofile"><b>privacy.dataCategory.employment.profesionalAndPersonalProfile</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.employment</b>](#privacy-datacategory-employment) <- <b>privacy.dataCategory.employment.profesionalAndPersonalProfile</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-employment-recruitment"><b>privacy.dataCategory.employment.recruitment</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.employment</b>](#privacy-datacategory-employment) <- <b>privacy.dataCategory.employment.recruitment</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-employment-workcontacts"><b>privacy.dataCategory.employment.workContacts</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.employment</b>](#privacy-datacategory-employment) <- <b>privacy.dataCategory.employment.workContacts</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-employment-workplaceinteractions"><b>privacy.dataCategory.employment.workplaceInteractions</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.employment</b>](#privacy-datacategory-employment) <- <b>privacy.dataCategory.employment.workplaceInteractions</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-employment-workprofile"><b>privacy.dataCategory.employment.workProfile</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.employment</b>](#privacy-datacategory-employment) <- <b>privacy.dataCategory.employment.workProfile</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-employment-workrecognition"><b>privacy.dataCategory.employment.workRecognition</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.employment</b>](#privacy-datacategory-employment) <- <b>privacy.dataCategory.employment.workRecognition</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-employment-worktime"><b>privacy.dataCategory.employment.workTime</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.employment</b>](#privacy-datacategory-employment) <- <b>privacy.dataCategory.employment.workTime</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser"><b>privacy.dataCategory.endUser</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- <b>privacy.dataCategory.endUser</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-account"><b>privacy.dataCategory.endUser.account</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- <b>privacy.dataCategory.endUser.account</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-account-customercontact"><b>privacy.dataCategory.endUser.account.customerContact</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.account</b>](#privacy-datacategory-enduser-account) <- <b>privacy.dataCategory.endUser.account.customerContact</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-account-licensingandpurchase"><b>privacy.dataCategory.endUser.account.licensingAndPurchase</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.account</b>](#privacy-datacategory-enduser-account) <- <b>privacy.dataCategory.endUser.account.licensingAndPurchase</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-account-paymentinstrument"><b>privacy.dataCategory.endUser.account.paymentInstrument</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.account</b>](#privacy-datacategory-enduser-account) <- <b>privacy.dataCategory.endUser.account.paymentInstrument</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-attributes"><b>privacy.dataCategory.endUser.attributes</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- <b>privacy.dataCategory.endUser.attributes</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-attributes-demographic"><b>privacy.dataCategory.endUser.attributes.demographic</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.attributes</b>](#privacy-datacategory-enduser-attributes) <- <b>privacy.dataCategory.endUser.attributes.demographic</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-attributes-feedbackandratings"><b>privacy.dataCategory.endUser.attributes.feedbackAndRatings</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.attributes</b>](#privacy-datacategory-enduser-attributes) <- <b>privacy.dataCategory.endUser.attributes.feedbackAndRatings</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-attributes-interestsandfavorites"><b>privacy.dataCategory.endUser.attributes.interestsAndFavorites</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.attributes</b>](#privacy-datacategory-enduser-attributes) <- <b>privacy.dataCategory.endUser.attributes.interestsAndFavorites</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-attributes-socialactivity"><b>privacy.dataCategory.endUser.attributes.socialActivity</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.attributes</b>](#privacy-datacategory-enduser-attributes) <- <b>privacy.dataCategory.endUser.attributes.socialActivity</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-content"><b>privacy.dataCategory.endUser.content</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- <b>privacy.dataCategory.endUser.content</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-content-contactlist"><b>privacy.dataCategory.endUser.content.contactList</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.content</b>](#privacy-datacategory-enduser-content) <- <b>privacy.dataCategory.endUser.content.contactList</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-content-credentials"><b>privacy.dataCategory.endUser.content.credentials</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.content</b>](#privacy-datacategory-enduser-content) <- <b>privacy.dataCategory.endUser.content.credentials</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-content-provided"><b>privacy.dataCategory.endUser.content.provided</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.content</b>](#privacy-datacategory-enduser-content) <- <b>privacy.dataCategory.endUser.content.provided</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-interactions"><b>privacy.dataCategory.endUser.interactions</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- <b>privacy.dataCategory.endUser.interactions</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-interactions-browsinghistory"><b>privacy.dataCategory.endUser.interactions.browsingHistory</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.interactions</b>](#privacy-datacategory-enduser-interactions) <- <b>privacy.dataCategory.endUser.interactions.browsingHistory</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-interactions-cloudservice"><b>privacy.dataCategory.endUser.interactions.cloudService</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.interactions</b>](#privacy-datacategory-enduser-interactions) <- <b>privacy.dataCategory.endUser.interactions.cloudService</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-interactions-contentconsumption"><b>privacy.dataCategory.endUser.interactions.contentConsumption</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.interactions</b>](#privacy-datacategory-enduser-interactions) <- <b>privacy.dataCategory.endUser.interactions.contentConsumption</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-interactions-deviceconnectivityandconfiguration"><b>privacy.dataCategory.endUser.interactions.deviceConnectivityAndConfiguration</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.interactions</b>](#privacy-datacategory-enduser-interactions) <- <b>privacy.dataCategory.endUser.interactions.deviceConnectivityAndConfiguration</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-interactions-environmentalsensor"><b>privacy.dataCategory.endUser.interactions.environmentalSensor</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.interactions</b>](#privacy-datacategory-enduser-interactions) <- <b>privacy.dataCategory.endUser.interactions.environmentalSensor</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-interactions-fitnessandactivity"><b>privacy.dataCategory.endUser.interactions.fitnessAndActivity</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.interactions</b>](#privacy-datacategory-enduser-interactions) <- <b>privacy.dataCategory.endUser.interactions.fitnessAndActivity</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-interactions-inkingtypingandspeach"><b>privacy.dataCategory.endUser.interactions.inkingTypingAndSpeach</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.interactions</b>](#privacy-datacategory-enduser-interactions) <- <b>privacy.dataCategory.endUser.interactions.inkingTypingAndSpeach</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-interactions-precicelocation"><b>privacy.dataCategory.endUser.interactions.preciceLocation</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.interactions</b>](#privacy-datacategory-enduser-interactions) <- <b>privacy.dataCategory.endUser.interactions.preciceLocation</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-interactions-productandserviceperformance"><b>privacy.dataCategory.endUser.interactions.productAndServicePerformance</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.interactions</b>](#privacy-datacategory-enduser-interactions) <- <b>privacy.dataCategory.endUser.interactions.productAndServicePerformance</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-interactions-productandserviceusage"><b>privacy.dataCategory.endUser.interactions.productAndServiceUsage</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.interactions</b>](#privacy-datacategory-enduser-interactions) <- <b>privacy.dataCategory.endUser.interactions.productAndServiceUsage</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-interactions-searchrequests"><b>privacy.dataCategory.endUser.interactions.searchRequests</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.interactions</b>](#privacy-datacategory-enduser-interactions) <- <b>privacy.dataCategory.endUser.interactions.searchRequests</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-interactions-softwaresetandinventory"><b>privacy.dataCategory.endUser.interactions.softwareSetAndInventory</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.interactions</b>](#privacy-datacategory-enduser-interactions) <- <b>privacy.dataCategory.endUser.interactions.softwareSetAndInventory</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-support"><b>privacy.dataCategory.endUser.support</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- <b>privacy.dataCategory.endUser.support</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-support-content"><b>privacy.dataCategory.endUser.support.content</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.support</b>](#privacy-datacategory-enduser-support) <- <b>privacy.dataCategory.endUser.support.content</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datacategory-enduser-support-interaction"><b>privacy.dataCategory.endUser.support.interaction</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataCategory</b>](#privacy-datacategory) <- [<b>privacy.dataCategory.endUser</b>](#privacy-datacategory-enduser) <- [<b>privacy.dataCategory.endUser.support</b>](#privacy-datacategory-enduser-support) <- <b>privacy.dataCategory.endUser.support.interaction</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-dataidentifiablity"><b>privacy.dataIdentifiablity</b></a>


**Description**


The root trait for the set explaining how data value may identity an individual.


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- <b>privacy.dataIdentifiablity</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-dataidentifiablity-aggregated"><b>privacy.dataIdentifiablity.aggregated</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataIdentifiablity</b>](#privacy-dataidentifiablity) <- <b>privacy.dataIdentifiablity.aggregated</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-dataidentifiablity-anonymized"><b>privacy.dataIdentifiablity.anonymized</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataIdentifiablity</b>](#privacy-dataidentifiablity) <- <b>privacy.dataIdentifiablity.anonymized</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-dataidentifiablity-identified"><b>privacy.dataIdentifiablity.identified</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataIdentifiablity</b>](#privacy-dataidentifiablity) <- <b>privacy.dataIdentifiablity.identified</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-dataidentifiablity-pseudonimized"><b>privacy.dataIdentifiablity.pseudonimized</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataIdentifiablity</b>](#privacy-dataidentifiablity) <- <b>privacy.dataIdentifiablity.pseudonimized</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-dataidentifiablity-pseudonimizednotlinked"><b>privacy.dataIdentifiablity.pseudonimizedNotLinked</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataIdentifiablity</b>](#privacy-dataidentifiablity) <- <b>privacy.dataIdentifiablity.pseudonimizedNotLinked</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datasubjectaction"><b>privacy.dataSubjectAction</b></a>


**Description**


The set of actions a data subject must be able to take on a set of data.


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- <b>privacy.dataSubjectAction</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datasubjectaction-delete"><b>privacy.dataSubjectAction.delete</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataSubjectAction</b>](#privacy-datasubjectaction) <- <b>privacy.dataSubjectAction.delete</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datasubjectaction-edit"><b>privacy.dataSubjectAction.edit</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataSubjectAction</b>](#privacy-datasubjectaction) <- <b>privacy.dataSubjectAction.edit</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datasubjectaction-export"><b>privacy.dataSubjectAction.export</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataSubjectAction</b>](#privacy-datasubjectaction) <- <b>privacy.dataSubjectAction.export</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datasubjectaction-view"><b>privacy.dataSubjectAction.view</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataSubjectAction</b>](#privacy-datasubjectaction) <- <b>privacy.dataSubjectAction.view</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datausage"><b>privacy.dataUsage</b></a>


**Description**


The purpose for a sepcific usage of a set of data


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- <b>privacy.dataUsage</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datausage-advertising"><b>privacy.dataUsage.advertising</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataUsage</b>](#privacy-datausage) <- <b>privacy.dataUsage.advertising</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datausage-advertising-adplatform"><b>privacy.dataUsage.advertising.adPlatform</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataUsage</b>](#privacy-datausage) <- [<b>privacy.dataUsage.advertising</b>](#privacy-datausage-advertising) <- <b>privacy.dataUsage.advertising.adPlatform</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datausage-advertising-directmarketing"><b>privacy.dataUsage.advertising.directMarketing</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataUsage</b>](#privacy-datausage) <- [<b>privacy.dataUsage.advertising</b>](#privacy-datausage-advertising) <- <b>privacy.dataUsage.advertising.directMarketing</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datausage-improve"><b>privacy.dataUsage.improve</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataUsage</b>](#privacy-datausage) <- <b>privacy.dataUsage.improve</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datausage-personalize"><b>privacy.dataUsage.personalize</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataUsage</b>](#privacy-datausage) <- <b>privacy.dataUsage.personalize</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datausage-provide"><b>privacy.dataUsage.provide</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataUsage</b>](#privacy-datausage) <- <b>privacy.dataUsage.provide</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datausage-recommend"><b>privacy.dataUsage.recommend</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataUsage</b>](#privacy-datausage) <- <b>privacy.dataUsage.recommend</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datausage-research"><b>privacy.dataUsage.research</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataUsage</b>](#privacy-datausage) <- <b>privacy.dataUsage.research</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datausage-share"><b>privacy.dataUsage.share</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataUsage</b>](#privacy-datausage) <- <b>privacy.dataUsage.share</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datausage-share-controller"><b>privacy.dataUsage.share.controller</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataUsage</b>](#privacy-datausage) <- [<b>privacy.dataUsage.share</b>](#privacy-datausage-share) <- <b>privacy.dataUsage.share.controller</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-datausage-share-processor"><b>privacy.dataUsage.share.processor</b></a>


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.dataUsage</b>](#privacy-datausage) <- [<b>privacy.dataUsage.share</b>](#privacy-datausage-share) <- <b>privacy.dataUsage.share.processor</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-expresses"><b>privacy.expresses</b></a>


**Description**


The root meta trait that indicates how to interpret a group of co-ascribed privacy traits.


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- <b>privacy.expresses</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-expresses-data"><b>privacy.expresses.data</b></a>


**Description**


The assumed default behavior, if privacy.expresses.metaData is not set, then this trait is implicit. When a group of traits are ascribed to an entity or attribute, The other privacy traits describe the aspects of data values held by the entity or attribute.


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.expresses</b>](#privacy-expresses) <- <b>privacy.expresses.data</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-expresses-metadata"><b>privacy.expresses.metaData</b></a>


**Description**


When this trait and a group of other privacy traits are ascribed to an entity or attribute, The other privacy traits describe the aspects of the metatdata for the data values held by the entity or attribute. That is, the entity itself may contain privacy or policy descriptions, rules, settings.


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.expresses</b>](#privacy-expresses) <- <b>privacy.expresses.metaData</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-expresses-useallowed"><b>privacy.expresses.useAllowed</b></a>


**Description**


Use is allowed for the condition using the combined meanings of all other privacy traits in a set.


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.expresses</b>](#privacy-expresses) <- <b>privacy.expresses.useAllowed</b>|


**Properties**

None


**Parameters**

None


## <a id="privacy-expresses-userestricted"><b>privacy.expresses.useRestricted</b></a>


**Description**


Use is dis-allowed for the condition formed using the combined meanings of all other privacy traits in a set.


| Inheritance |
|--|
|[<b>privacy</b>](#privacy) <- [<b>privacy.expresses</b>](#privacy-expresses) <- <b>privacy.expresses.useRestricted</b>|


**Properties**

None


**Parameters**

None


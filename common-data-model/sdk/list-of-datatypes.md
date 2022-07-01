---
title: A list of Common Data Model datatypes | Microsoft Docs
description: A list of Common Data Model datatypes.
author: msftman

ms.reviewer: v-iap
ms.topic: article
ms.date: 05/06/2021
ms.author: matgos
---

# List of CDM data types

This page lists the data types which are available in Common Data Model.

## <a id="addressline"><b>addressLine</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>addressLine</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.location.address</b>|

## <a id="age"><b>age</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>integer</b>](#integer) <- <b>age</b>|

| Traits |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.signed</b>|
|<b>is.dataFormat.numeric</b>|
|<b>means.demographic.age</b>|
|<b>means.measurement.age</b>|

## <a id="ampere"><b>ampere</b></a>

**Description**

Unit of measure for electric current in amperes

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>ampere</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.electricCurrent</b>|
|<b>means.measurement.units.si.ampere</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|

## <a id="any"><b>any</b></a>

**Description**

The root dataType

**Inheritance**

None

**Traits**

None

## <a id="attribute"><b>attribute</b></a>

**Description**

Types for trait parameters that take objects as values

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>object</b>](#object) <- [<b>cdmObject</b>](#cdmobject) <- <b>attribute</b>|

**Traits**

None

## <a id="attributegroup"><b>attributeGroup</b></a>

**Description**

Types for trait parameters that take objects as values

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>object</b>](#object) <- [<b>cdmObject</b>](#cdmobject) <- <b>attributeGroup</b>|

**Traits**

None

## <a id="attributename"><b>attributeName</b></a>

**Description**

Type for trait parameters that take attribute names as values

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>attributeName</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.attributeName</b>|

## <a id="basecurrency"><b>baseCurrency</b></a>

**Description**

Value is expressed in the base currency units for the system

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>decimal</b>](#decimal) <- [<b>currency</b>](#currency) <- <b>baseCurrency</b>|

| Traits |
|--|
|<b>is.dataFormat.numeric.shaped</b>|
|<b>means.measurement.currency</b>|
|<b>means.measurement.currency</b>|

## <a id="biginteger"><b>bigInteger</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>integer</b>](#integer) <- <b>bigInteger</b>|

| Traits |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.signed</b>|
|<b>is.dataFormat.numeric</b>|
|<b>is.dataFormat.big</b>|

## <a id="binary"><b>binary</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>byte</b>](#byte) <- <b>binary</b>|

| Traits |
|--|
|<b>is.dataFormat.byte</b>|
|<b>is.dataFormat.array</b>|

## <a id="birthdate"><b>birthDate</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>date</b>](#date) <- [<b>dateTime</b>](#datetime) <- <b>birthDate</b>|

| Traits |
|--|
|<b>is.dataFormat.date</b>|
|<b>means.measurement.date</b>|
|<b>is.dataFormat.time</b>|
|<b>means.measurement.time</b>|
|<b>means.demographic.birthDate</b>|

## <a id="boolean"><b>boolean</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- <b>boolean</b>|

| Traits |
|--|
|<b>is.dataFormat.boolean</b>|

## <a id="byte"><b>byte</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- <b>byte</b>|

| Traits |
|--|
|<b>is.dataFormat.byte</b>|

## <a id="candela"><b>candela</b></a>

**Description**

Unit of measure for luminous intensity in candelas

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>candela</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.luminousIntensity</b>|
|<b>means.measurement.units.si.candela</b>|
|<b>has.measurement.fundamentalComponent.candela</b>|

## <a id="cdmobject"><b>cdmObject</b></a>

**Description**

Types for trait parameters that take CDM objects as values

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>object</b>](#object) <- <b>cdmObject</b>|

**Traits**

None

## <a id="celsius"><b>celsius</b></a>

**Description**

Unit of measure for temperature in degrees celsius

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>celsius</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.temperature</b>|
|<b>means.measurement.units.si.celsius</b>|
|<b>has.measurement.fundamentalComponent.kelvin</b>|

## <a id="centimeter"><b>centimeter</b></a>

**Description**

Unit of measure for length in 10E-2 meters

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>meter</b>](#meter) <- <b>centimeter</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.length</b>|
|<b>means.measurement.units.si.meter</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>means.measurement.prefix.centi</b>|

## <a id="char"><b>char</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- <b>char</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|

## <a id="city"><b>city</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>city</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.location.city</b>|

## <a id="colorname"><b>colorName</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>colorName</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.measurement.color</b>|

## <a id="companyname"><b>companyName</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>companyName</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.company.name</b>|


## <a id="coulomb"><b>coulomb</b></a>

**Description**

Unit of measure for electric charge or amount of electricity in coulombs

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>coulomb</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.electricCharge</b>|
|<b>means.measurement.units.si.coulomb</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|

## <a id="country"><b>country</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>country</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.location.country</b>|

## <a id="county"><b>county</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>county</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.location.county</b>|

## <a id="culturetag"><b>cultureTag</b></a>

**Description**

A BCP 47 language tag

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- [<b>languageTag</b>](#languagetag) <- <b>cultureTag</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.reference.language.tag</b>|
|<b>means.reference.culture.tag</b>|

## <a id="currency"><b>currency</b></a>

**Description**

An amount of currency, money in units specified elsewhere.

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>decimal</b>](#decimal) <- <b>currency</b>|

| Traits |
|--|
|<b>is.dataFormat.numeric.shaped</b>|
|<b>means.measurement.currency</b>|

## <a id="currencycode"><b>currencyCode</b></a>

**Description**

Value is a ISO 4217 currency code

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>currencyCode</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.measurement.currencyCode</b>|

## <a id="datatype"><b>dataType</b></a>

**Description**

Types for trait parameters that take objects as values

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>object</b>](#object) <- [<b>cdmObject</b>](#cdmobject) <- <b>dataType</b>|

**Traits**

None

## <a id="date"><b>date</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- <b>date</b>|

| Traits |
|--|
|<b>is.dataFormat.date</b>|
|<b>means.measurement.date</b>|

## <a id="datetime"><b>dateTime</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>date</b>](#date) <- <b>dateTime</b>|

| Traits |
|--|
|<b>is.dataFormat.date</b>|
|<b>means.measurement.date</b>|
|<b>is.dataFormat.time</b>|
|<b>means.measurement.time</b>|

## <a id="datetimeoffset"><b>dateTimeOffset</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>date</b>](#date) <- [<b>dateTime</b>](#datetime) <- <b>dateTimeOffset</b>|

| Traits |
|--|
|<b>is.dataFormat.date</b>|
|<b>means.measurement.date</b>|
|<b>is.dataFormat.time</b>|
|<b>means.measurement.time</b>|
|<b>is.dataFormat.timeOffset</b>|

## <a id="day"><b>day</b></a>

**Description**

[deprecated] This dataType is being deprecated, and will be removed in a future version of CDM. Please use the relevant traits directly.

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>integer</b>](#integer) <- [<b>integerCalendarPart</b>](#integercalendarpart) <- <b>day</b>|

| Traits |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.signed</b>|
|<b>is.dataFormat.numeric</b>|
|<b>means.calendar</b>|
|<b>means.calendar.day</b>|

### <a id="day"><b>day</b></a>


## <a id="day"><b>day</b></a>


**Description**


Unit of measure for time in 'one earth rotation' interval


**Inheritance**

| |
|--|
|[<b>any</b>](#any) <- [<b>integer</b>](#integer) <- <b>day</b>|

| Traits |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.signed</b>|
|<b>is.dataFormat.numeric</b>|
|<b>means.measurement.dimension.time</b>|
|<b>means.measurement.duration.days</b>|
|<b>has.measurement.fundamentalComponent.second</b>|

## <a id="decimal"><b>decimal</b></a>

**Description**

A precise fractional number with a specific precision and scale

| Inheritance |
|--|
|[<b>any</b>](#any) <- <b>decimal</b>|

| Traits |
|--|
|<b>is.dataFormat.numeric.shaped</b>|

## <a id="degree"><b>degree</b></a>

**Description**

Unit of measure for angles in degrees, 1/360 rotation

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>degree</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.angle</b>|
|<b>means.measurement.units.degree</b>|
|<b>has.measurement.fundamentalComponent</b>|

## <a id="displayorder"><b>displayOrder</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>integer</b>](#integer) <- <b>displayOrder</b>|

| Traits |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.signed</b>|
|<b>is.dataFormat.numeric</b>|
|<b>means.formatting.order</b>|

## <a id="double"><b>double</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- <b>double</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|

## <a id="email"><b>email</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>email</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.service.email</b>|

## <a id="entity"><b>entity</b></a>

**Description**

Types for trait parameters that take objects as values

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>object</b>](#object) <- [<b>cdmObject</b>](#cdmobject) <- <b>entity</b>|

| Traits |
|--|
|<b>means.entityName.specific</b>|

## <a id="entityid"><b>entityId</b></a>

**Description**

A unique identifier for entity instances

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- [<b>guid</b>](#guid) <- <b>entityId</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>is.dataFormat.guid</b>|
|<b>means.identity.entityId</b>|

## <a id="entityname"><b>entityName</b></a>

**Description**

Type for trait parameters that take entity names as values

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>entityName</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.entityName</b>|
|<b>means.entityName</b>|

## <a id="ethnicity"><b>ethnicity</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>ethnicity</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.demographic.ethnicity</b>|

## <a id="farad"><b>farad</b></a>

**Description**

Unit of measure for electric capacitance in farads

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>farad</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.capacitance</b>|
|<b>means.measurement.units.si.farad</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|

## <a id="fileid"><b>fileId</b></a>

**Description**

A unique identifier for file instances

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- [<b>guid</b>](#guid) <- [<b>entityId</b>](#entityid) <- <b>fileId</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>is.dataFormat.guid</b>|
|<b>means.identity.entityId</b>|

## <a id="filename"><b>fileName</b></a>

**Description**

A string value representing the name of a file.

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>fileName</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.fileName</b>|

## <a id="firstname"><b>firstName</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>firstName</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.person.firstName</b>|

## <a id="fixeddecimal"><b>fixedDecimal</b></a>

**Description**

The 64 bit fixed (4) scale numbers used by PBI

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>decimal</b>](#decimal) <- <b>fixedDecimal</b>|

| Traits |
|--|
|<b>is.dataFormat.numeric.shaped</b>|

## <a id="float"><b>float</b></a>

**Description**

Fractional numbers, assumed to correspond with a 32 bit float IEEE approximation.

| Inheritance |
|--|
|[<b>any</b>](#any) <- <b>float</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|

## <a id="fullname"><b>fullName</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>fullName</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.person.fullName</b>|

## <a id="gender"><b>gender</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>gender</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.demographic.gender</b>|

## <a id="gigahertz"><b>gigahertz</b></a>

**Description**

Unit of frequency equivalent to 10E9 hertz

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>hertz</b>](#hertz) <- <b>gigahertz</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.frequency</b>|
|<b>means.measurement.units.si.hertz</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.prefix.giga</b>|

## <a id="gigapascal"><b>gigapascal</b></a>

**Description**

Unit of stress, equivalent to 10E9 pascals

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>pascal</b>](#pascal) <- <b>gigapascal</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.pressure</b>|
|<b>means.measurement.units.si.pascal</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.prefix.giga</b>|

## <a id="governmentid"><b>governmentId</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>governmentId</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.governmentID</b>|

## <a id="gram"><b>gram</b></a>

**Description**

Unit of measure for mass in grams

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>gram</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.mass</b>|
|<b>means.measurement.units.si.gram</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|

## <a id="guid"><b>guid</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>guid</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>is.dataFormat.guid</b>|

## <a id="hertz"><b>hertz</b></a>

**Description**

Unit of measure for frequency in hertz

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>hertz</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.frequency</b>|
|<b>means.measurement.units.si.hertz</b>|
|<b>has.measurement.fundamentalComponent.second</b>|

## <a id="hour"><b>hour</b></a>

**Description**

Unit of measure for time in 3600 second interval

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>integer</b>](#integer) <- <b>hour</b>|

| Traits |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.signed</b>|
|<b>is.dataFormat.numeric</b>|
|<b>means.measurement.dimension.time</b>|
|<b>means.measurement.duration.hours</b>|
|<b>has.measurement.fundamentalComponent.second</b>|

## <a id="image"><b>image</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>byte</b>](#byte) <- [<b>binary</b>](#binary) <- <b>image</b>|

| Traits |
|--|
|<b>is.dataFormat.byte</b>|
|<b>is.dataFormat.array</b>|
|<b>means.content.binary.image</b>|

## <a id="inches"><b>inches</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>inches</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.distance.inches</b>|

## <a id="integer"><b>integer</b></a>

**Description**

Whole numbers, assumed to correspond with a 32 bit signed int

| Inheritance |
|--|
|[<b>any</b>](#any) <- <b>integer</b>|

| Traits |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.signed</b>|
|<b>is.dataFormat.numeric</b>|

## <a id="integercalendarpart"><b>integerCalendarPart</b></a>


**Description**


[deprecated] This dataType is being deprecated, and will be removed in a future version of CDM. Please use the relevant traits directly.


**Inheritance**

| |
|--|
|[<b>any</b>](#any) <- [<b>integer</b>](#integer) <- <b>integerCalendarPart</b>|

| Traits |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.signed</b>|
|<b>is.dataFormat.numeric</b>|
|<b>means.calendar</b>|

## <a id="ip4address"><b>IP4Address</b></a>

**Description**

Internet Protocol V4 Address of the form DDD.DDD.DDD.DDD

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>IP4Address</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.IP4Address</b>|

## <a id="ip6address"><b>IP6Address</b></a>

**Description**

Internet Protocol V6 Address of the form  XXXX:XXXX:XXXX:XXXX:XXXX:XXXX:XXXX:XXXX

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>IP6Address</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.IP6Address</b>|

## <a id="joule"><b>joule</b></a>

**Description**

Unit of measure for energy, work or heat in joules

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>joule</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.energy</b>|
|<b>means.measurement.units.si.joule</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|

## <a id="jsinteger"><b>JSInteger</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>decimal</b>](#decimal) <- <b>JSInteger</b>|

| Traits |
|--|
|<b>is.dataFormat.numeric.shaped</b>|
|<b>is.dataFormat.JSInteger</b>|

## <a id="json"><b>json</b></a>

**Description**

A JSON fragment contained within one string value

| Inheritance|
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>json</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.content.text.JSON</b>|

## <a id="kelvin"><b>kelvin</b></a>

**Description**

Unit of measure for thermodynamic temperature in degrees kelvin

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>kelvin</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.temperature</b>|
|<b>means.measurement.units.si.kelvin</b>|
|<b>has.measurement.fundamentalComponent.kelvin</b>|

## <a id="kilogram"><b>kilogram</b></a>

**Description**

Unit of measure for mass in kilogram

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>kilogram</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.mass</b>|
|<b>means.measurement.units.si.kilogram</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|

## <a id="kilohertz"><b>kilohertz</b></a>

**Description**

Unit of frequency equivalent to 10E3 hertz

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>hertz</b>](#hertz) <- <b>kilohertz</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.frequency</b>|
|<b>means.measurement.units.si.hertz</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.prefix.kilo</b>|

## <a id="kilometer"><b>kilometer</b></a>

**Description**

Unit of measure for length in 10E3 meters

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>meter</b>](#meter) <- <b>kilometer</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.length</b>|
|<b>means.measurement.units.si.meter</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>means.measurement.prefix.kilo</b>|

## <a id="kiloohm"><b>kiloOhm</b></a>

**Description**

Unit of power, equivalent to 10E3 ohms

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>ohm</b>](#ohm) <- <b>kiloOhm</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.resistance</b>|
|<b>means.measurement.units.si.ohm</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|
|<b>means.measurement.prefix.kilo</b>|

## <a id="kilopascal"><b>kilopascal</b></a>

**Description**

Unit of stress, equivalent to 10E3 pascals

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>pascal</b>](#pascal) <- <b>kilopascal</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.pressure</b>|
|<b>means.measurement.units.si.pascal</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.prefix.kilo</b>|

## <a id="kilovolt"><b>kilovolt</b></a>

**Description**

Unit of power, equivalent to 10E3 volts

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>volt</b>](#volt) <- <b>kilovolt</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.electromotiveForce</b>|
|<b>means.measurement.units.si.volt</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|
|<b>means.measurement.prefix.kilo</b>|

## <a id="kilowatt"><b>kilowatt</b></a>

**Description**

Unit of power, equivalent to 10E3 watts

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>watt</b>](#watt) <- <b>kilowatt</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.power</b>|
|<b>means.measurement.units.si.watt</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.prefix.kilo</b>|

## <a id="language"><b>language</b></a>

**Description**

A language identifier

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>language</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.reference.language</b>|

## <a id="languagetag"><b>languageTag</b></a>

**Description**

A BCP 47 language tag

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>languageTag</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.reference.language.tag</b>|

## <a id="lastname"><b>lastName</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>lastName</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.person.lastName</b>|

## <a id="latitude"><b>latitude</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>latitude</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.location.latitude</b>|

## <a id="list"><b>list</b></a>

**Description**

A CSV contained within one string value

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>list</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.content.text.CSV</b>|

## <a id="listlookup"><b>listLookup</b></a>

**Description**

One integer value from a defined list of possibilities

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>integer</b>](#integer) <- <b>listLookup</b>|

| Traits |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.signed</b>|
|<b>is.dataFormat.numeric</b>|
|<b>does.haveDefault</b>|
|<b>is.constrainedList</b>|

## <a id="listlookupcorrelated"><b>listLookupCorrelated</b></a>

**Description**

One integer value from a defined list of possibilities where the list represents correlated status

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>integer</b>](#integer) <- <b>listLookupCorrelated</b>|

| Traits |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.signed</b>|
|<b>is.dataFormat.numeric</b>|
|<b>is.constrainedList.correlated</b>|

## <a id="listlookupmultiple"><b>listLookupMultiple</b></a>

**Description**

A set of one or more values from a defined list of possibilities

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>listLookupMultiple</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>does.haveDefault</b>|
|<b>means.content.text.CSV</b>|
|<b>is.constrainedList</b>|

## <a id="listlookupstring"><b>listLookupString</b></a>

**Description**

One string value from a defined list of possibilities

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>listLookupString</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>is.constrainedList.string</b>|

## <a id="listlookupwellknown"><b>listLookupWellKnown</b></a>

**Description**

One string value from a defined list of possibilities which are defined in an identified public location.

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>listLookupWellKnown</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>is.constrainedList.wellKnown</b>|

## <a id="localizeddisplaytext"><b>localizedDisplayText</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>localizedDisplayText</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.reference.displayText</b>|

## <a id="localizeddisplaytextmultiple"><b>localizedDisplayTextMultiple</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- [<b>localizedDisplayText</b>](#localizeddisplaytext) <- <b>localizedDisplayTextMultiple</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.reference.displayText</b>|
|<b>means.content.text.CSV</b>|

## <a id="longitude"><b>longitude</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>longitude</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.location.longitude</b>|

## <a id="maritalstatus"><b>maritalStatus</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>maritalStatus</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.demographic.maritalStatus</b>|

## <a id="megahertz"><b>megahertz</b></a>

**Description**

Unit of frequency equivalent to 10E6 hertz

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>hertz</b>](#hertz) <- <b>megahertz</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.frequency</b>|
|<b>means.measurement.units.si.hertz</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.prefix.mega</b>|

## <a id="megaohm"><b>megaOhm</b></a>

**Description**

Unit of power, equivalent to 10E6 Ohms

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>ohm</b>](#ohm) <- <b>megaOhm</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.resistance</b>|
|<b>means.measurement.units.si.ohm</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|
|<b>means.measurement.prefix.mega</b>|

## <a id="megapascal"><b>megapascal</b></a>

**Description**

Unit of stress, equivalent to 10E6 pascals

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>pascal</b>](#pascal) <- <b>megapascal</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.pressure</b>|
|<b>means.measurement.units.si.pascal</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.prefix.mega</b>|

## <a id="megavolt"><b>megavolt</b></a>

**Description**

Unit of power, equivalent to 10E6 volts

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>volt</b>](#volt) <- <b>megavolt</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.electromotiveForce</b>|
|<b>means.measurement.units.si.volt</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|
|<b>means.measurement.prefix.mega</b>|

## <a id="megawatt"><b>megawatt</b></a>

**Description**

Unit of power, equivalent to 10E6 watts

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>watt</b>](#watt) <- <b>megawatt</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.power</b>|
|<b>means.measurement.units.si.watt</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.prefix.mega</b>|

## <a id="meter"><b>meter</b></a>

**Description**

Unit of measure for length in meters

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>meter</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.length</b>|
|<b>means.measurement.units.si.meter</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|

## <a id="microampere"><b>microampere</b></a>

**Description**

Unit of capacitance, equivalent to 10E-6 amperes

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>ampere</b>](#ampere) <- <b>microampere</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.electricCurrent</b>|
|<b>means.measurement.units.si.ampere</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|
|<b>means.measurement.prefix.micro</b>|

## <a id="microfarad"><b>microfarad</b></a>

**Description**

Unit of capacitance, equivalent to 10E-6 farads

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>farad</b>](#farad) <- <b>microfarad</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.capacitance</b>|
|<b>means.measurement.units.si.farad</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|
|<b>means.measurement.prefix.micro</b>|

## <a id="microsecond"><b>microSecond</b></a>

**Description**

Unit of measure for time in 10E-6 seconds

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>second</b>](#second) <- <b>microSecond</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.time</b>|
|<b>means.measurement.units.si.second</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.duration.seconds</b>|
|<b>means.measurement.prefix.micro</b>|

## <a id="middlename"><b>middleName</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>middleName</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.person.middleName</b>|

## <a id="milliampere"><b>milliampere</b></a>

**Description**

Unit of capacitance, equivalent to 10E-3 amperes

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>ampere</b>](#ampere) <- <b>milliampere</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.electricCurrent</b>|
|<b>means.measurement.units.si.ampere</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|
|<b>means.measurement.prefix.milli</b>|

## <a id="milligram"><b>milligram</b></a>

**Description**

Unit of measure for mass in milligrams

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>gram</b>](#gram) <- <b>milligram</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.mass</b>|
|<b>means.measurement.units.si.gram</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>means.measurement.prefix.milli</b>|

## <a id="millimeter"><b>millimeter</b></a>

**Description**

Unit of measure for length in 10E-3 meters

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>meter</b>](#meter) <- <b>millimeter</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.length</b>|
|<b>means.measurement.units.si.meter</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>means.measurement.prefix.milli</b>|

## <a id="millisecond"><b>milliSecond</b></a>

**Description**

Unit of measure for time in 10E-3 seconds

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>second</b>](#second) <- <b>milliSecond</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.time</b>|
|<b>means.measurement.units.si.second</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.duration.seconds</b>|
|<b>means.measurement.prefix.milli</b>|

## <a id="millivolt"><b>millivolt</b></a>

**Description**

Unit of power, equivalent to 10E-3 volts

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>volt</b>](#volt) <- <b>millivolt</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.electromotiveForce</b>|
|<b>means.measurement.units.si.volt</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|
|<b>means.measurement.prefix.milli</b>|

## <a id="milliwatt"><b>milliwatt</b></a>

**Description**

Unit of power, equivalent to 10E-3 watts

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>watt</b>](#watt) <- <b>milliwatt</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.power</b>|
|<b>means.measurement.units.si.watt</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.prefix.milli</b>|

## <a id="minute"><b>minute</b></a>

**Description**

Unit of measure for time in 60 second interval

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>integer</b>](#integer) <- <b>minute</b>|

| Traits |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.signed</b>|
|<b>is.dataFormat.numeric</b>|
|<b>means.measurement.dimension.time</b>|
|<b>means.measurement.duration.minutes</b>|
|<b>has.measurement.fundamentalComponent.second</b>|

## <a id="minutes"><b>minutes</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>integer</b>](#integer) <- [<b>minute</b>](#minute) <- <b>minutes</b>|

| Traits |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.signed</b>|
|<b>is.dataFormat.numeric</b>|
|<b>means.measurement.dimension.time</b>|
|<b>means.measurement.duration.minutes</b>|
|<b>has.measurement.fundamentalComponent.second</b>|

## <a id="mole"><b>mole</b></a>

**Description**

Unit of measure for amount in moles

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>mole</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.amount</b>|
|<b>means.measurement.units.si.mole</b>|
|<b>has.measurement.fundamentalComponent.mole</b>|

## <a id="month"><b>month</b></a>


**Description**


[deprecated] This dataType is being deprecated, and will be removed in a future version of CDM. Please use the relevant traits directly.


**Inheritance**

| |
|--|
|[<b>any</b>](#any) <- [<b>integer</b>](#integer) <- [<b>integerCalendarPart</b>](#integercalendarpart) <- <b>month</b>|

| Traits |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.signed</b>|
|<b>is.dataFormat.numeric</b>|
|<b>means.calendar</b>|
|<b>means.calendar.month</b>|

## <a id="name"><b>name</b></a>

|  Inheritance|
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>name</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.name</b>|

## <a id="nanofarad"><b>nanofarad</b></a>

**Description**

Unit of capacitance, equivalent to 10E-9 farads

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>farad</b>](#farad) <- <b>nanofarad</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.capacitance</b>|
|<b>means.measurement.units.si.farad</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|
|<b>means.measurement.prefix.nano</b>|

## <a id="newton"><b>newton</b></a>

**Description**

Unit of measure for force or weight in newtons

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>newton</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.force</b>|
|<b>means.measurement.units.si.newton</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|

## <a id="object"><b>object</b></a>

**Description**

Types for trait parameters that take objects as values

| Inheritance |
|--|
|[<b>any</b>](#any) <- <b>object</b>|

**Traits**
None

## <a id="ohm"><b>ohm</b></a>

**Description**

Unit of measure for electrical resistance, impedance, reactance in ohms

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>ohm</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.resistance</b>|
|<b>means.measurement.units.si.ohm</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|

## <a id="pascal"><b>pascal</b></a>

**Description**

Unit of measure for pressure or stress in pascals

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>pascal</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.pressure</b>|
|<b>means.measurement.units.si.pascal</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|

## <a id="phone"><b>phone</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>phone</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.service.phone</b>|

## <a id="phonecell"><b>phoneCell</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>phoneCell</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.service.phone.cell</b>|

## <a id="phonefax"><b>phoneFax</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>phoneFax</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.service.phone.fax</b>|

## <a id="picofarad"><b>picofarad</b></a>

**Description**

Unit of capacitance, equivalent to 10E-12 farads

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- [<b>farad</b>](#farad) <- <b>picofarad</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.capacitance</b>|
|<b>means.measurement.units.si.farad</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|
|<b>means.measurement.prefix.pico</b>|

## <a id="postalcode"><b>postalCode</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>postalCode</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.location.postalCode</b>|

## <a id="purpose"><b>purpose</b></a>

**Description**

Types for trait parameters that take objects as values

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>object</b>](#object) <- [<b>cdmObject</b>](#cdmobject) <- <b>purpose</b>|

**Traits**

None

## <a id="quarter"><b>quarter</b></a>


**Description**


[deprecated] This dataType is being deprecated, and will be removed in a future version of CDM. Please use the relevant traits directly.


**Inheritance**

| |
|--|
|[<b>any</b>](#any) <- [<b>integer</b>](#integer) <- [<b>integerCalendarPart</b>](#integercalendarpart) <- <b>quarter</b>|

| Traits |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.signed</b>|
|<b>is.dataFormat.numeric</b>|
|<b>means.calendar</b>|
|<b>means.calendar.quarter</b>|

## <a id="radian"><b>radian</b></a>

**Description**

Unit of measure for angle in radians

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>radian</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.angle</b>|
|<b>means.measurement.units.si.radian</b>|
|<b>has.measurement.fundamentalComponent</b>|

## <a id="schar"><b>sChar</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- <b>sChar</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|

## <a id="second"><b>second</b></a>

**Description**

Unit of measure for time in seconds

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>second</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.time</b>|
|<b>means.measurement.units.si.second</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.duration.seconds</b>|

## <a id="smallinteger"><b>smallInteger</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>integer</b>](#integer) <- <b>smallInteger</b>|

| Traits |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.signed</b>|
|<b>is.dataFormat.numeric</b>|
|<b>is.dataFormat.small</b>|

## <a id="stateorprovince"><b>stateOrProvince</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>stateOrProvince</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.location.stateOrProvince</b>|

## <a id="string"><b>string</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- <b>string</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|

## <a id="stringformat"><b>stringFormat</b></a>

**Description**

A string representing the format used to encode data in another string

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>stringFormat</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.formatting.stringFormat</b>|

## <a id="tenday"><b>tenday</b></a>


**Description**


[deprecated] This dataType is being deprecated, and will be removed in a future version of CDM. Please use the relevant traits directly.


**Inheritance**

| |
|--|
|[<b>any</b>](#any) <- [<b>integer</b>](#integer) <- [<b>integerCalendarPart</b>](#integercalendarpart) <- <b>tenday</b>|

| Traits |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.signed</b>|
|<b>is.dataFormat.numeric</b>|
|<b>means.calendar</b>|
|<b>means.calendar.tenday</b>|

## <a id="tickersymbol"><b>tickerSymbol</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>tickerSymbol</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.tickerSymbol</b>|

## <a id="time"><b>time</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- <b>time</b>|

| Traits |
|--|
|<b>is.dataFormat.time</b>|
|<b>means.measurement.time</b>|

## <a id="timezone"><b>timezone</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>timezone</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.location.timezone</b>|

## <a id="trait"><b>trait</b></a>

**Description**

Types for trait parameters that take objects as values

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>object</b>](#object) <- [<b>cdmObject</b>](#cdmobject) <- <b>trait</b>|

**Traits**
None

## <a id="trimester"><b>trimester</b></a>


**Description**


[deprecated] This dataType is being deprecated, and will be removed in a future version of CDM. Please use the relevant traits directly.


**Inheritance**

| |
|--|
|[<b>any</b>](#any) <- [<b>integer</b>](#integer) <- [<b>integerCalendarPart</b>](#integercalendarpart) <- <b>trimester</b>|

| Traits |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.signed</b>|
|<b>is.dataFormat.numeric</b>|
|<b>means.calendar</b>|
|<b>means.calendar.trimester</b>|



## <a id="unsignedinteger"><b>unsignedInteger</b></a>


**Description**


Assumed to correspond with a 32 bit unsigned int


**Inheritance**

| |
|--|
|[<b>any</b>](#any) <- <b>unsignedInteger</b>|


**Traits**

| |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.unsigned</b>|
|<b>is.dataFormat.numeric</b>|



## <a id="uri"><b>uri</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>uri</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.reference.URI</b>|

## <a id="url"><b>url</b></a>

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>url</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.reference.URL</b>|

## <a id="userid"><b>userId</b></a>

**Description**

The identifier of a system user

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- [<b>guid</b>](#guid) <- [<b>entityId</b>](#entityid) <- <b>userId</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>is.dataFormat.guid</b>|
|<b>means.identity.entityId</b>|
|<b>means.userId</b>|

## <a id="variabledecimal"><b>variableDecimal</b></a>

**Description**

15-digit precision numbers with no fixed scale

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>decimal</b>](#decimal) <- <b>variableDecimal</b>|

| Traits |
|--|
|<b>is.dataFormat.numeric.shaped</b>|

## <a id="volt"><b>volt</b></a>

**Description**

Unit of measure for voltage, EMF, electrical potantial difference in volts

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>volt</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.electromotiveForce</b>|
|<b>means.measurement.units.si.volt</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|

## <a id="watt"><b>watt</b></a>

**Description**

Unit of measure for power or radiant flux in watts

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>float</b>](#float) <- [<b>double</b>](#double) <- <b>watt</b>|

| Traits |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.power</b>|
|<b>means.measurement.units.si.watt</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|

## <a id="week"><b>week</b></a>


**Description**


[deprecated] This dataType is being deprecated, and will be removed in a future version of CDM. Please use the relevant traits directly.


**Inheritance**

| |
|--|
|[<b>any</b>](#any) <- [<b>integer</b>](#integer) <- [<b>integerCalendarPart</b>](#integercalendarpart) <- <b>week</b>|

| Traits |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.signed</b>|
|<b>is.dataFormat.numeric</b>|
|<b>means.calendar</b>|
|<b>means.calendar.week</b>|

## <a id="xml"><b>xml</b></a>

**Description**

An XML fragment contained within one string value

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>char</b>](#char) <- [<b>string</b>](#string) <- <b>xml</b>|

| Traits |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.content.text.XML</b>|

## <a id="year"><b>year</b></a>

**Description**

Unit of measure for time in 'one solar orbit' interval

| Inheritance |
|--|
|[<b>any</b>](#any) <- [<b>integer</b>](#integer) <- <b>year</b>|

| Traits |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.signed</b>|
|<b>is.dataFormat.numeric</b>|
|<b>means.measurement.dimension.time</b>|
|<b>means.measurement.duration.years</b>|
|<b>has.measurement.fundamentalComponent.second</b>|

### <a id="year"><b>year</b></a>


## <a id="year"><b>year</b></a>


**Description**


[deprecated] This dataType is being deprecated, and will be removed in a future version of CDM. Please use the relevant traits directly.


**Inheritance**

| |
|--|
|[<b>any</b>](#any) <- [<b>integer</b>](#integer) <- [<b>integerCalendarPart</b>](#integercalendarpart) <- <b>year</b>|

| Traits |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.signed</b>|
|<b>is.dataFormat.numeric</b>|
|<b>means.calendar</b>|
|<b>means.calendar.year</b>|

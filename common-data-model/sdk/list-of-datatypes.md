---
title: List of Common Data Model datatypes | Microsoft Docs
description: Lists the datatypes that are available in Common Data Model and describes the inheritance and traits of the datatypes.
author: matgos
ms.service: common-data-model
ms.reviewer: v-iap
ms.topic: article
ms.date: 12/14/2020
ms.author: matgos
---

# List of Common Data Model datatypes
This page lists the datatypes that are available in Common Data Model.

## <b>any</b>
**Description**

The root dataType

### Inheritance
None

### Traits
None

## <b>integer</b>
**Description**

Whole numbers, assumed to correspond with a 32 bit signed int

### Inheritance
| |
|--|
|any -> integer|

### Traits
| |
|--|
|<b>is.dataFormat.integer</b>|

## <b>listLookup</b>
**Description**

One integer value from a defined list of possibilities

### Inheritance
| |
|--|
|any -> integer -> listLookup|

### Traits
| |
|--|
|<b>is.dataFormat.integer</b>|
|<b>does.haveDefault</b>|
|<b>is.constrainedList</b>|

## <b>listLookupCorrelated</b>
**Description**

One integer value from a defined list of possibilities where the list represents correlated status

### Inheritance
| |
|--|
|any -> integer -> listLookupCorrelated|

### Traits
| |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.constrainedList.correlated</b>|

## <b>smallInteger</b>
### Inheritance
| |
|--|
|any -> integer -> smallInteger|

### Traits
| |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.small</b>|

## <b>bigInteger</b>
### Inheritance
| |
|--|
|any -> integer -> bigInteger|

### Traits
| |
|--|
|<b>is.dataFormat.integer</b>|
|<b>is.dataFormat.big</b>|

## <b>integerCalendarPart</b>
### Inheritance
| |
|--|
|any -> integer -> integerCalendarPart|

### Traits
| |
|--|
|<b>is.dataFormat.integer</b>|
|<b>means.calendar</b>|

## <b>day</b>
### Inheritance
| |
|--|
|any -> integer -> integerCalendarPart -> day|

### Traits
| |
|--|
|<b>is.dataFormat.integer</b>|
|<b>means.calendar</b>|
|<b>means.calendar.day</b>|

## <b>week</b>
### Inheritance
| |
|--|
|any -> integer -> integerCalendarPart -> week|

### Traits
| |
|--|
|<b>is.dataFormat.integer</b>|
|<b>means.calendar</b>|
|<b>means.calendar.week</b>|

## <b>tenday</b>
### Inheritance
| |
|--|
|any -> integer -> integerCalendarPart -> tenday|

### Traits
| |
|--|
|<b>is.dataFormat.integer</b>|
|<b>means.calendar</b>|
|<b>means.calendar.tenday</b>|

## <b>month</b>
### Inheritance
| |
|--|
|any -> integer -> integerCalendarPart -> month|

### Traits
| |
|--|
|<b>is.dataFormat.integer</b>|
|<b>means.calendar</b>|
|<b>means.calendar.month</b>|

## <b>quarter</b>
### Inheritance
| |
|--|
|any -> integer -> integerCalendarPart -> quarter|

### Traits
| |
|--|
|<b>is.dataFormat.integer</b>|
|<b>means.calendar</b>|
|<b>means.calendar.quarter</b>|

## <b>trimester</b>
### Inheritance
| |
|--|
|any -> integer -> integerCalendarPart -> trimester|

### Traits
| |
|--|
|<b>is.dataFormat.integer</b>|
|<b>means.calendar</b>|
|<b>means.calendar.trimester</b>|

## <b>year</b>
### Inheritance
| |
|--|
|any -> integer -> integerCalendarPart -> year|

### Traits
| |
|--|
|<b>is.dataFormat.integer</b>|
|<b>means.calendar</b>|
|<b>means.calendar.year</b>|

## <b>minute</b>
**Description**

Unit of measure for time in 60 second interval

### Inheritance
| |
|--|
|any -> integer -> minute|

### Traits
| |
|--|
|<b>is.dataFormat.integer</b>|
|<b>means.measurement.dimension.time</b>|
|<b>means.measurement.duration.minutes</b>|
|<b>has.measurement.fundamentalComponent.second</b>|

## <b>minutes</b>
### Inheritance
| |
|--|
|any -> integer -> minute -> minutes|

### Traits
| |
|--|
|<b>is.dataFormat.integer</b>|
|<b>means.measurement.dimension.time</b>|
|<b>means.measurement.duration.minutes</b>|
|<b>has.measurement.fundamentalComponent.second</b>|

## <b>hour</b>
**Description**

Unit of measure for time in 3600 second interval

### Inheritance
| |
|--|
|any -> integer -> hour|

### Traits
| |
|--|
|<b>is.dataFormat.integer</b>|
|<b>means.measurement.dimension.time</b>|
|<b>means.measurement.duration.hours</b>|
|<b>has.measurement.fundamentalComponent.second</b>|

## <b>day</b>
**Description**

Unit of measure for time in 'one earth rotation' interval

### Inheritance
| |
|--|
|any -> integer -> day|

### Traits
| |
|--|
|<b>is.dataFormat.integer</b>|
|<b>means.measurement.dimension.time</b>|
|<b>means.measurement.duration.days</b>|
|<b>has.measurement.fundamentalComponent.second</b>|

## <b>year</b>
**Description**

Unit of measure for time in 'one solar orbit' interval

### Inheritance
| |
|--|
|any -> integer -> year|

### Traits
| |
|--|
|<b>is.dataFormat.integer</b>|
|<b>means.measurement.dimension.time</b>|
|<b>means.measurement.duration.years</b>|
|<b>has.measurement.fundamentalComponent.second</b>|

## <b>displayOrder</b>
### Inheritance
| |
|--|
|any -> integer -> displayOrder|

### Traits
| |
|--|
|<b>is.dataFormat.integer</b>|
|<b>means.formatting.order</b>|

## <b>age</b>
### Inheritance
| |
|--|
|any -> integer -> age|

### Traits
| |
|--|
|<b>is.dataFormat.integer</b>|
|<b>means.demographic.age</b>|
|<b>means.measurement.age</b>|

## <b>float</b>
**Description**

Fractional numbers, assumed to correspond with a 32 bit float IEEE approximation.

### Inheritance
| |
|--|
|any -> float|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|

## <b>double</b>
### Inheritance
| |
|--|
|any -> float -> double|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|

## <b>second</b>
**Description**

Unit of measure for time in seconds

### Inheritance
| |
|--|
|any -> float -> double -> second|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.time</b>|
|<b>means.measurement.units.si.second</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.duration.seconds</b>|

## <b>microSecond</b>
**Description**

Unit of measure for time in 10E-6 seconds

### Inheritance
| |
|--|
|any -> float -> double -> second -> microSecond|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.time</b>|
|<b>means.measurement.units.si.second</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.duration.seconds</b>|
|<b>means.measurement.prefix.micro</b>|

## <b>milliSecond</b>
**Description**

Unit of measure for time in 10E-3 seconds

### Inheritance
| |
|--|
|any -> float -> double -> second -> milliSecond|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.time</b>|
|<b>means.measurement.units.si.second</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.duration.seconds</b>|
|<b>means.measurement.prefix.milli</b>|

## <b>meter</b>
**Description**

Unit of measure for length in meters

### Inheritance
| |
|--|
|any -> float -> double -> meter|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.length</b>|
|<b>means.measurement.units.si.meter</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|

## <b>millimeter</b>
**Description**

Unit of measure for length in 10E-3 meters

### Inheritance
| |
|--|
|any -> float -> double -> meter -> millimeter|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.length</b>|
|<b>means.measurement.units.si.meter</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>means.measurement.prefix.milli</b>|

## <b>centimeter</b>
**Description**

Unit of measure for length in 10E-2 meters

### Inheritance
| |
|--|
|any -> float -> double -> meter -> centimeter|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.length</b>|
|<b>means.measurement.units.si.meter</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>means.measurement.prefix.centi</b>|

## <b>kilometer</b>
**Description**

Unit of measure for length in 10E3 meters

### Inheritance
| |
|--|
|any -> float -> double -> meter -> kilometer|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.length</b>|
|<b>means.measurement.units.si.meter</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>means.measurement.prefix.kilo</b>|

## <b>kilogram</b>
**Description**

Unit of measure for mass in kilogram

### Inheritance
| |
|--|
|any -> float -> double -> kilogram|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.mass</b>|
|<b>means.measurement.units.si.kilogram</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|

## <b>ampere</b>
**Description**

Unit of measure for electric current in amperes

### Inheritance
| |
|--|
|any -> float -> double -> ampere|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.electricCurrent</b>|
|<b>means.measurement.units.si.ampere</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|

## <b>microampere</b>
**Description**

Unit of capacitance, equivalent to 10E-6 amperes

### Inheritance
| |
|--|
|any -> float -> double -> ampere -> microampere|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.electricCurrent</b>|
|<b>means.measurement.units.si.ampere</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|
|<b>means.measurement.prefix.micro</b>|

## <b>milliampere</b>
**Description**

Unit of capacitance, equivalent to 10E-3 amperes

### Inheritance
| |
|--|
|any -> float -> double -> ampere -> milliampere|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.electricCurrent</b>|
|<b>means.measurement.units.si.ampere</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|
|<b>means.measurement.prefix.milli</b>|

## <b>kelvin</b>
**Description**

Unit of measure for thermodynamic temperature in degrees kelvin

### Inheritance
| |
|--|
|any -> float -> double -> kelvin|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.temperature</b>|
|<b>means.measurement.units.si.kelvin</b>|
|<b>has.measurement.fundamentalComponent.kelvin</b>|

## <b>mole</b>
**Description**

Unit of measure for amount in moles

### Inheritance
| |
|--|
|any -> float -> double -> mole|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.amount</b>|
|<b>means.measurement.units.si.mole</b>|
|<b>has.measurement.fundamentalComponent.mole</b>|

## <b>candela</b>
**Description**

Unit of measure for luminous intensity in candelas

### Inheritance
| |
|--|
|any -> float -> double -> candela|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.luminousIntensity</b>|
|<b>means.measurement.units.si.candela</b>|
|<b>has.measurement.fundamentalComponent.candela</b>|

## <b>hertz</b>
**Description**

Unit of measure for frequency in hertz

### Inheritance
| |
|--|
|any -> float -> double -> hertz|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.frequency</b>|
|<b>means.measurement.units.si.hertz</b>|
|<b>has.measurement.fundamentalComponent.second</b>|

## <b>kilohertz</b>
**Description**

Unit of frequency equivalent to 10E3 hertz

### Inheritance
| |
|--|
|any -> float -> double -> hertz -> kilohertz|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.frequency</b>|
|<b>means.measurement.units.si.hertz</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.prefix.kilo</b>|

## <b>megahertz</b>
**Description**

Unit of frequency equivalent to 10E6 hertz

### Inheritance
| |
|--|
|any -> float -> double -> hertz -> megahertz|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.frequency</b>|
|<b>means.measurement.units.si.hertz</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.prefix.mega</b>|

## <b>gigahertz</b>
**Description**

Unit of frequency equivalent to 10E9 hertz

### Inheritance
| |
|--|
|any -> float -> double -> hertz -> gigahertz|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.frequency</b>|
|<b>means.measurement.units.si.hertz</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.prefix.giga</b>|

## <b>radian</b>
**Description**

Unit of measure for angle in radians

### Inheritance
| |
|--|
|any -> float -> double -> radian|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.angle</b>|
|<b>means.measurement.units.si.radian</b>|
|<b>has.measurement.fundamentalComponent</b>|

## <b>newton</b>
**Description**

Unit of measure for force or weight in newtons

### Inheritance
| |
|--|
|any -> float -> double -> newton|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.force</b>|
|<b>means.measurement.units.si.newton</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|

## <b>pascal</b>
**Description**

Unit of measure for pressure or stress in pascals

### Inheritance
| |
|--|
|any -> float -> double -> pascal|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.pressure</b>|
|<b>means.measurement.units.si.pascal</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|

## <b>kilopascal</b>
**Description**

Unit of stress, equivalent to 10E3 pascals

### Inheritance
| |
|--|
|any -> float -> double -> pascal -> kilopascal|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.pressure</b>|
|<b>means.measurement.units.si.pascal</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.prefix.kilo</b>|

## <b>megapascal</b>
**Description**

Unit of stress, equivalent to 10E6 pascals

### Inheritance
| |
|--|
|any -> float -> double -> pascal -> megapascal|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.pressure</b>|
|<b>means.measurement.units.si.pascal</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.prefix.mega</b>|

## <b>gigapascal</b>
**Description**

Unit of stress, equivalent to 10E9 pascals

### Inheritance
| |
|--|
|any -> float -> double -> pascal -> gigapascal|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.pressure</b>|
|<b>means.measurement.units.si.pascal</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.prefix.giga</b>|

## <b>joule</b>
**Description**

Unit of measure for energy, work or heat in joules

### Inheritance
| |
|--|
|any -> float -> double -> joule|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.energy</b>|
|<b>means.measurement.units.si.joule</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|

## <b>watt</b>
**Description**

Unit of measure for power or radiant flux in watts

### Inheritance
| |
|--|
|any -> float -> double -> watt|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.power</b>|
|<b>means.measurement.units.si.watt</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|

## <b>milliwatt</b>
**Description**

Unit of power, equivalent to 10E-3 watts

### Inheritance
| |
|--|
|any -> float -> double -> watt -> milliwatt|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.power</b>|
|<b>means.measurement.units.si.watt</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.prefix.milli</b>|

## <b>kilowatt</b>
**Description**

Unit of power, equivalent to 10E3 watts

### Inheritance
| |
|--|
|any -> float -> double -> watt -> kilowatt|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.power</b>|
|<b>means.measurement.units.si.watt</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.prefix.kilo</b>|

## <b>megawatt</b>
**Description**

Unit of power, equivalent to 10E6 watts

### Inheritance
| |
|--|
|any -> float -> double -> watt -> megawatt|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.power</b>|
|<b>means.measurement.units.si.watt</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>means.measurement.prefix.mega</b>|

## <b>coulomb</b>
**Description**

Unit of measure for electric charge or amount of electricity in coulombs

### Inheritance
| |
|--|
|any -> float -> double -> coulomb|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.electricCharge</b>|
|<b>means.measurement.units.si.coulomb</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|

## <b>volt</b>
**Description**

Unit of measure for voltage, EMF, electrical potantial difference in volts

### Inheritance
| |
|--|
|any -> float -> double -> volt|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.electromotiveForce</b>|
|<b>means.measurement.units.si.volt</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|

## <b>millivolt</b>
**Description**

Unit of power, equivalent to 10E-3 volts

### Inheritance
| |
|--|
|any -> float -> double -> volt -> millivolt|

### Traits
| |
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

## <b>kilovolt</b>
**Description**

Unit of power, equivalent to 10E3 volts

### Inheritance
| |
|--|
|any -> float -> double -> volt -> kilovolt|

### Traits
| |
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

## <b>megavolt</b>
**Description**

Unit of power, equivalent to 10E6 volts

### Inheritance
| |
|--|
|any -> float -> double -> volt -> megavolt|

### Traits
| |
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

## <b>farad</b>
**Description**

Unit of measure for electric capacitance in farads

### Inheritance
| |
|--|
|any -> float -> double -> farad|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.capacitance</b>|
|<b>means.measurement.units.si.farad</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|

## <b>microfarad</b>
**Description**

Unit of capacitance, equivalent to 10E-6 farads

### Inheritance
| |
|--|
|any -> float -> double -> farad -> microfarad|

### Traits
| |
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

## <b>nanofarad</b>
**Description**

Unit of capacitance, equivalent to 10E-9 farads

### Inheritance
| |
|--|
|any -> float -> double -> farad -> nanofarad|

### Traits
| |
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

## <b>picofarad</b>
**Description**

Unit of capacitance, equivalent to 10E-12 farads

### Inheritance
| |
|--|
|any -> float -> double -> farad -> picofarad|

### Traits
| |
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

## <b>ohm</b>
**Description**

Unit of measure for electrical resistance, impedance, reactance in ohms

### Inheritance
| |
|--|
|any -> float -> double -> ohm|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.resistance</b>|
|<b>means.measurement.units.si.ohm</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>has.measurement.fundamentalComponent.meter</b>|
|<b>has.measurement.fundamentalComponent.second</b>|
|<b>has.measurement.fundamentalComponent.ampere</b>|

## <b>kiloOhm</b>
**Description**

Unit of power, equivalent to 10E3 ohms

### Inheritance
| |
|--|
|any -> float -> double -> ohm -> kiloOhm|

### Traits
| |
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

## <b>megaOhm</b>
**Description**

Unit of power, equivalent to 10E6 Ohms

### Inheritance
| |
|--|
|any -> float -> double -> ohm -> megaOhm|

### Traits
| |
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

## <b>gram</b>
**Description**

Unit of measure for mass in grams

### Inheritance
| |
|--|
|any -> float -> double -> gram|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.mass</b>|
|<b>means.measurement.units.si.gram</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|

## <b>milligram</b>
**Description**

Unit of measure for mass in milligrams

### Inheritance
| |
|--|
|any -> float -> double -> gram -> milligram|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.mass</b>|
|<b>means.measurement.units.si.gram</b>|
|<b>has.measurement.fundamentalComponent.kilogram</b>|
|<b>means.measurement.prefix.milli</b>|

## <b>celsius</b>
**Description**

Unit of measure for temperature in degrees celsius

### Inheritance
| |
|--|
|any -> float -> double -> celsius|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.temperature</b>|
|<b>means.measurement.units.si.celsius</b>|
|<b>has.measurement.fundamentalComponent.kelvin</b>|

## <b>degree</b>
**Description**

Unit of measure for angles in degrees, 1/360 rotation

### Inheritance
| |
|--|
|any -> float -> double -> degree|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.dimension.angle</b>|
|<b>means.measurement.units.degree</b>|
|<b>has.measurement.fundamentalComponent</b>|

## <b>inches</b>
### Inheritance
| |
|--|
|any -> float -> double -> inches|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.measurement.distance.inches</b>|

## <b>latitude</b>
### Inheritance
| |
|--|
|any -> float -> double -> latitude|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.location.latitude</b>|

## <b>longitude</b>
### Inheritance
| |
|--|
|any -> float -> double -> longitude|

### Traits
| |
|--|
|<b>is.dataFormat.floatingPoint</b>|
|<b>is.dataFormat.big</b>|
|<b>means.location.longitude</b>|

## <b>decimal</b>
**Description**

A precice fractional number with a specific precision and scale

### Inheritance
| |
|--|
|any -> decimal|

### Traits
| |
|--|
|<b>is.dataFormat.numeric.shaped</b>|

## <b>fixedDecimal</b>
**Description**

The 64 bit fixed (4) scale numbers used by PBI

### Inheritance
| |
|--|
|any -> decimal -> fixedDecimal|

### Traits
| |
|--|
|<b>is.dataFormat.numeric.shaped</b>|

## <b>variableDecimal</b>
**Description**

15 digit precision numbers with no fixed scale

### Inheritance
| |
|--|
|any -> decimal -> variableDecimal|

### Traits
| |
|--|
|<b>is.dataFormat.numeric.shaped</b>|

## <b>JSInteger</b>
### Inheritance
| |
|--|
|any -> decimal -> JSInteger|

### Traits
| |
|--|
|<b>is.dataFormat.numeric.shaped</b>|
|<b>is.dataFormat.JSInteger</b>|

## <b>currency</b>
**Description**

An amount of currency, money in units specified elsewhere.

### Inheritance
| |
|--|
|any -> decimal -> currency|

### Traits
| |
|--|
|<b>is.dataFormat.numeric.shaped</b>|
|<b>means.measurement.currency</b>|

## <b>baseCurrency</b>
**Description**

Value is expressed in the base currency units for the system

### Inheritance
| |
|--|
|any -> decimal -> currency -> baseCurrency|

### Traits
| |
|--|
|<b>is.dataFormat.numeric.shaped</b>|
|<b>means.measurement.currency</b>|
|<b>means.measurement.currency</b>|

## <b>boolean</b>
### Inheritance
| |
|--|
|any -> boolean|

### Traits
| |
|--|
|<b>is.dataFormat.boolean</b>|

## <b>char</b>
### Inheritance
| |
|--|
|any -> char|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|

## <b>string</b>
### Inheritance
| |
|--|
|any -> char -> string|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|

## <b>listLookupMultiple</b>
**Description**

A set of one or more values from a defined list of possibilities

### Inheritance
| |
|--|
|any -> char -> string -> listLookupMultiple|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>does.haveDefault</b>|
|<b>means.content.text.CSV</b>|
|<b>is.constrainedList</b>|

## <b>listLookupString</b>
**Description**

One string value from a defined list of possibilities

### Inheritance
| |
|--|
|any -> char -> string -> listLookupString|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>is.constrainedList.string</b>|

## <b>listLookupWellKnown</b>
**Description**

One string value from a defined list of possibilities which are defined in an identified public location.

### Inheritance
| |
|--|
|any -> char -> string -> listLookupWellKnown|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>is.constrainedList.wellKnown</b>|

## <b>guid</b>
### Inheritance
| |
|--|
|any -> char -> string -> guid|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>is.dataFormat.guid</b>|

## <b>entityId</b>
**Description**

A unique identifier for entity instances

### Inheritance
| |
|--|
|any -> char -> string -> guid -> entityId|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>is.dataFormat.guid</b>|
|<b>means.identity.entityId</b>|

## <b>userId</b>
**Description**

The identifier of a system user

### Inheritance
| |
|--|
|any -> char -> string -> guid -> entityId -> userId|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>is.dataFormat.guid</b>|
|<b>means.identity.entityId</b>|
|<b>means.userId</b>|

## <b>fileId</b>
**Description**

A unique identifier for file instances

### Inheritance
| |
|--|
|any -> char -> string -> guid -> entityId -> fileId|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>is.dataFormat.guid</b>|
|<b>means.identity.entityId</b>|

## <b>fileName</b>
**Description**

A string value representing the name of a file.

### Inheritance
| |
|--|
|any -> char -> string -> fileName|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.fileName</b>|

## <b>entityName</b>
**Description**

Type for trait parameters that take entity names as values

### Inheritance
| |
|--|
|any -> char -> string -> entityName|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.entityName</b>|
|<b>means.entityName</b>|

## <b>attributeName</b>
**Description**

Type for trait parameters that take attribute names as values

### Inheritance
| |
|--|
|any -> char -> string -> attributeName|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.attributeName</b>|

## <b>list</b>
**Description**

A CSV contained within one string value

### Inheritance
| |
|--|
|any -> char -> string -> list|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.content.text.CSV</b>|

## <b>language</b>
**Description**

A language identifier

### Inheritance
| |
|--|
|any -> char -> string -> language|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.reference.language</b>|

## <b>languageTag</b>
**Description**

A BCP 47 language tag

### Inheritance
| |
|--|
|any -> char -> string -> languageTag|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.reference.language.tag</b>|

## <b>cultureTag</b>
**Description**

A BCP 47 language tag

### Inheritance
| |
|--|
|any -> char -> string -> languageTag -> cultureTag|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.reference.language.tag</b>|
|<b>means.reference.culture.tag</b>|

## <b>localizedDisplayText</b>
### Inheritance
| |
|--|
|any -> char -> string -> localizedDisplayText|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.reference.displayText</b>|

## <b>localizedDisplayTextMultiple</b>
### Inheritance
| |
|--|
|any -> char -> string -> localizedDisplayText -> localizedDisplayTextMultiple|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.reference.displayText</b>|
|<b>means.content.text.CSV</b>|

## <b>url</b>
### Inheritance
| |
|--|
|any -> char -> string -> url|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.reference.URL</b>|

## <b>uri</b>
### Inheritance
| |
|--|
|any -> char -> string -> uri|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.reference.URI</b>|

## <b>governmentId</b>
### Inheritance
| |
|--|
|any -> char -> string -> governmentId|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.governmentID</b>|

## <b>name</b>
### Inheritance
| |
|--|
|any -> char -> string -> name|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.name</b>|

## <b>companyName</b>
### Inheritance
| |
|--|
|any -> char -> string -> companyName|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.company.name</b>|

## <b>firstName</b>
### Inheritance
| |
|--|
|any -> char -> string -> firstName|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.person.firstName</b>|

## <b>fullName</b>
### Inheritance
| |
|--|
|any -> char -> string -> fullName|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.person.fullName</b>|

## <b>lastName</b>
### Inheritance
| |
|--|
|any -> char -> string -> lastName|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.person.lastName</b>|

## <b>middleName</b>
### Inheritance
| |
|--|
|any -> char -> string -> middleName|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.person.middleName</b>|

## <b>email</b>
### Inheritance
| |
|--|
|any -> char -> string -> email|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.service.email</b>|

## <b>phone</b>
### Inheritance
| |
|--|
|any -> char -> string -> phone|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.service.phone</b>|

## <b>phoneCell</b>
### Inheritance
| |
|--|
|any -> char -> string -> phoneCell|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.service.phone.cell</b>|

## <b>phoneFax</b>
### Inheritance
| |
|--|
|any -> char -> string -> phoneFax|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.service.phone.fax</b>|

## <b>tickerSymbol</b>
### Inheritance
| |
|--|
|any -> char -> string -> tickerSymbol|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.tickerSymbol</b>|

## <b>IP4Address</b>
**Description**

Internet Protocol V4 Address of the form DDD.DDD.DDD.DDD

### Inheritance
| |
|--|
|any -> char -> string -> IP4Address|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.IP4Address</b>|

## <b>IP6Address</b>
**Description**

Internet Protocol V6 Address of the form  XXXX:XXXX:XXXX:XXXX:XXXX:XXXX:XXXX:XXXX

### Inheritance
| |
|--|
|any -> char -> string -> IP6Address|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.identity.IP6Address</b>|

## <b>currencyCode</b>
**Description**

Value is a ISO 4217 currency code

### Inheritance
| |
|--|
|any -> char -> string -> currencyCode|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.measurement.currencyCode</b>|

## <b>colorName</b>
### Inheritance
| |
|--|
|any -> char -> string -> colorName|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.measurement.color</b>|

## <b>stringFormat</b>
**Description**

A string representing the format used to encode data in another string

### Inheritance
| |
|--|
|any -> char -> string -> stringFormat|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.formatting.stringFormat</b>|

## <b>json</b>
**Description**

A JSON fragment contained within one string value

### Inheritance
| |
|--|
|any -> char -> string -> json|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.content.text.JSON</b>|

## <b>xml</b>
**Description**

An XML fragment contained within one string value

### Inheritance
| |
|--|
|any -> char -> string -> xml|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.content.text.XML</b>|

## <b>gender</b>
### Inheritance
| |
|--|
|any -> char -> string -> gender|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.demographic.gender</b>|

## <b>ethnicity</b>
### Inheritance
| |
|--|
|any -> char -> string -> ethnicity|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.demographic.ethnicity</b>|

## <b>maritalStatus</b>
### Inheritance
| |
|--|
|any -> char -> string -> maritalStatus|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.demographic.maritalStatus</b>|

## <b>addressLine</b>
### Inheritance
| |
|--|
|any -> char -> string -> addressLine|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.location.address</b>|

## <b>city</b>
### Inheritance
| |
|--|
|any -> char -> string -> city|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.location.city</b>|

## <b>country</b>
### Inheritance
| |
|--|
|any -> char -> string -> country|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.location.country</b>|

## <b>county</b>
### Inheritance
| |
|--|
|any -> char -> string -> county|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.location.county</b>|

## <b>postalCode</b>
### Inheritance
| |
|--|
|any -> char -> string -> postalCode|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.location.postalCode</b>|

## <b>stateOrProvince</b>
### Inheritance
| |
|--|
|any -> char -> string -> stateOrProvince|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.location.stateOrProvince</b>|

## <b>timezone</b>
### Inheritance
| |
|--|
|any -> char -> string -> timezone|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|
|<b>is.dataFormat.big</b>|
|<b>is.dataFormat.array</b>|
|<b>means.location.timezone</b>|

## <b>sChar</b>
### Inheritance
| |
|--|
|any -> sChar|

### Traits
| |
|--|
|<b>is.dataFormat.character</b>|

## <b>byte</b>
### Inheritance
| |
|--|
|any -> byte|

### Traits
| |
|--|
|<b>is.dataFormat.byte</b>|

## <b>binary</b>
### Inheritance
| |
|--|
|any -> byte -> binary|

### Traits
| |
|--|
|<b>is.dataFormat.byte</b>|
|<b>is.dataFormat.array</b>|

## <b>image</b>
### Inheritance
| |
|--|
|any -> byte -> binary -> image|

### Traits
| |
|--|
|<b>is.dataFormat.byte</b>|
|<b>is.dataFormat.array</b>|
|<b>means.content.binary.image</b>|

## <b>object</b>
**Description**

Types for trait parameters that take objects as values

### Inheritance
| |
|--|
|any -> object|

### Traits
None

## <b>cdmObject</b>
**Description**

Types for trait parameters that take CDM objects as values

### Inheritance
| |
|--|
|any -> object -> cdmObject|

### Traits
None

## <b>trait</b>
**Description**

Types for trait parameters that take objects as values

### Inheritance
| |
|--|
|any -> object -> cdmObject -> trait|

### Traits
None

## <b>dataType</b>
**Description**

Types for trait parameters that take objects as values

### Inheritance
| |
|--|
|any -> object -> cdmObject -> dataType|

### Traits
None

## <b>purpose</b>
**Description**

Types for trait parameters that take objects as values

### Inheritance
| |
|--|
|any -> object -> cdmObject -> purpose|

### Traits
None

## <b>entity</b>
**Description**

Types for trait parameters that take objects as values

### Inheritance
| |
|--|
|any -> object -> cdmObject -> entity|

### Traits
| |
|--|
|<b>means.entityName.specific</b>|

## <b>attribute</b>
**Description**

Types for trait parameters that take objects as values

### Inheritance
| |
|--|
|any -> object -> cdmObject -> attribute|

### Traits
None

## <b>attributeGroup</b>
**Description**

Types for trait parameters that take objects as values

### Inheritance
| |
|--|
|any -> object -> cdmObject -> attributeGroup|

### Traits
None

## <b>date</b>
### Inheritance
| |
|--|
|any -> date|

### Traits
| |
|--|
|<b>is.dataFormat.date</b>|
|<b>means.measurement.date</b>|

## <b>dateTime</b>
### Inheritance
| |
|--|
|any -> date -> dateTime|

### Traits
| |
|--|
|<b>is.dataFormat.date</b>|
|<b>means.measurement.date</b>|
|<b>is.dataFormat.time</b>|
|<b>means.measurement.time</b>|

## <b>dateTimeOffset</b>
### Inheritance
| |
|--|
|any -> date -> dateTime -> dateTimeOffset|

### Traits
| |
|--|
|<b>is.dataFormat.date</b>|
|<b>means.measurement.date</b>|
|<b>is.dataFormat.time</b>|
|<b>means.measurement.time</b>|
|<b>is.dataFormat.timeOffset</b>|

## <b>birthDate</b>
### Inheritance
| |
|--|
|any -> date -> dateTime -> birthDate|

### Traits
| |
|--|
|<b>is.dataFormat.date</b>|
|<b>means.measurement.date</b>|
|<b>is.dataFormat.time</b>|
|<b>means.measurement.time</b>|
|<b>means.demographic.birthDate</b>|

## <b>time</b>
### Inheritance
| |
|--|
|any -> time|

### Traits
| |
|--|
|<b>is.dataFormat.time</b>|
|<b>means.measurement.time</b>|


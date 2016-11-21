# complex-processes
An ontology and associated examples for describing processes for ISO/OGC Obersvation &amp; Measurements and Sampling
## Contents
- [Classes](#classes)
    - [ComplexProcess](#complexprocess)
    - [Instrument](#instrument)
    - [Quality](#quality)
    - [Algorithm](#algorithm)
    - [ManufacturersCalibration](#manufacturerscalibration)
    - [InSituCorrection](#insitucorrection)
- [Properties](#properties)
    - [partialMeasure](#partialmeasure)
    - [usedInstrument](#usedInstrument)
- [Namespaces Used](#namespaces-used)

## Classes
### ComplexProcess
The ComplexProcess class

**In domain of** [usedInstrument](#usedinstrument)

### Instrument
The Instrument class describes characteristics of the sensor used to generate an Observation

**In domain of** 

**In range of** [usedInstrument](#usedinstrument)

### Quality
The Quality class retains information about the Process such as Limits of Detection; Uncertainity; Accuracy and Precision
### Algorithm
The Algorithm class is used to describe data processing equations and calculations.
### ManufacturersCalibration
The ManufacturersCalibration class describes instrument calibrations undertaken by their manufacturer.
### InSituCorrection
The InSituCorrection class describes offsets applied to sensor measurements determined after comparison with discrete measurements made on Sampling Specimens.
## Properties
### partialMeasure

**Domain** sam:Measure

**Range** [PartialMeasure](#partialmeasure)

### usedInstrument
Assigns an instrument to an Observation Process

**Domain** [ComplexProcess](#complexprocess)

**Range** [Instrument](#instrument)

**Sub-property of** prov:wasAssociatedWith

## Namespaces Used
prov: http://www.w3.org/ns/prov#

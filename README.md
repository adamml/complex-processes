# complex-processes
An ontology and associated examples for describing processes for ISO/OGC Obersvation &amp; Measurements and Sampling
## Contents
- [Classes](#classes)
    - [Algorithm](#algorithm)
    - [ComplexProcess](#complexprocess)
    - [InSituCorrection](#insitucorrection)
    - [Instrument](#instrument)
    - [ManufacturersCalibration](#manufacturerscalibration)
    - [PartialMeasure](#partialmeasure)
    - [Quality](#quality)
- [Properties](#properties)
    - [partialMeasure](#partialmeasure)
    - [usedInstrument](#usedInstrument)
- [Namespaces Used](#namespaces-used)

## Classes
### Algorithm
The Algorithm class is used to describe data processing equations and calculations.
### ComplexProcess
The ComplexProcess class

**In domain of** [usedInstrument](#usedinstrument)

### InSituCorrection
The InSituCorrection class describes offsets applied to sensor measurements determined after comparison with discrete measurements made on Sampling Specimens.
### Instrument
The Instrument class describes characteristics of the sensor used to generate an Observation

**In domain of** 

**In range of** [usedInstrument](#usedinstrument)

### ManufacturersCalibration
The ManufacturersCalibration class describes instrument calibrations undertaken by their manufacturer.
### PartialMeasure
The PartialMeasure class is for use where a sam:Specimen samples more than one matrix (such as air and water in pCO2 measurements.
### Quality
The Quality class retains information about the Process such as Limits of Detection; Uncertainity; Accuracy and Precision
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

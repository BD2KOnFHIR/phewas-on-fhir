PheWAS on FHIR
==============

FHIR based framework for Phenome Wide Association Studies

## Logical Model

![alt tag](https://github.com/BD2KOnFHIR/phewas-on-fhir/blob/master/docs/PheWasModel_small.png)

## Details

FHIR Extensions and Profiles created to implement the model.

* [source](source)
  * [PheWAS Diagnosis](source/PheWASDiagnosis.StructureDefinition.xml) - Diagnosis extension to FHIR [Condition](https://www.hl7.org/fhir/condition.html) Resource.
  * [PheWAS LabTest](source/PheWASLabTest-profile.xml) - LabTest profile to FHIR [Observation](https://www.hl7.org/fhir/observation.html) Resource.
  * [PheWAS Genetic Report](source/PheWASGeneticReport-profile.xml) - Genetic Report derived profile to FHIR [Observation-genetics](https://www.hl7.org/fhir/observation-genetics.html) Profile.
  * [PheWAS Report](source/PheWASReport.StructureDefinition.xml) - PheWAS Report Logical model composed of [Diagnosis](source/PheWASDiagnosis.StructureDefinition.xml), [LabTest](source/PheWASLabTest-profile.xml) and [Genetic Report](source/PheWASGeneticReport-profile.xml).
* [model](model)
  * [UML Model](model) - UML Model created using MagicDraw
 

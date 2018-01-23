# Surveillance Mechanisms
## Description:

In Mexico there are different surveillance mechanisms that testify the transparency and legality through all the contracting process.

## Proposal:

Add a new array field

### Codelist:

  - Social witness
  - Citizen comptroller
  - Internal control unit
  - External auditor

### Schema:

  - Contract {object}
    - surveillanceMechanisms [array]

## Defining texts:


**Code** | **Title** | **Description**
--|--|--
surveillanceMechanisms | Surveillance mechanisms | The surveillance mechanisms used in this contracting process. The mechanisms should be taken from the surveillanceMechanisms codelist (url).
socialWitness | Social witness | Specialized citizens who participate in the surveillance of this contracting process.
citizenComptroller | Citizen comptroller | Surveillance mechanism by beneficiaries to verify the works progress and the correct expending of public resources.
internalControlUnit | Internal control unit | Body in charge of preventing, detecting, sanctioning and eradicating corrupt practices that may arise in this contracting process.
externalAuditor | External auditor | Institution outside the public administration that performs an audit of this contracting process.

## Issues 

Report issues for this extension in the [standard repository](https://github.com/open-contracting/standard/issues/652) of the Open Contracting Partnership.

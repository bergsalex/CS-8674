# Berger CS 8674, Spring 2023
This document outlines the deliverables for Alexander Berger's CS 8674 masters project. The project is to create
a framework for enabling a progressive refactoring of the [Geneweaver](geneweaver.org) project that accounts for the
three main project stakeholders: scientific curators, genomic researchers, and educators and students.

The project will focus on three classes of deliverables: (1) a process for technical documentation of the Geneweaver
project, (2) development of automated testing and validation tools for contributions to the Geneweaver project, and
(3) a framework for enabling a progressive refactoring of Analysis tools.

## Process for Technical Documentation
One common request from stakeholders was a more comprehensive approach to technical documentation for the Geneweaver
project. There is currently documentation for the project that is aimed at scientific curators and genomic researchers.
This documentation is of limited value to both software contributors and educators and students.

### Deliverables
- A process for technical documentation of the Geneweaver project
- A technical documentation template for the Geneweaver project

#### Deliverable Technical Documentation
- Contribution guidelines for the Geneweaver project (provided in the new technical documentation)
- Documentation on External Data Sources
- At least one example of the following types of technical documentation:
    - A High Level, Non-expert Centric Product Overview
    - A Use-case for Non-multidisciplinary Uses
    - A Use-case for Multidisciplinary Uses
    - An Example Exercise
    - A Component Use-cases
- Comprehensive of each of the following deliverable sections in this document. 

## Automated Testing and Validation Tools
Another common overlap between stakeholder requests, is the need for more comprehensive automated testing and validation
tools for contributions to the Geneweaver project. This is a common request from both software contributors and 
educators and students.

### Deliverables
- A process for automated testing and validation of contributions to the Geneweaver project
  - This process should include a set of guidelines for the types of automated tests and validation tools that should
    be included in contributions to the Geneweaver project
- A set of high level automated tests and validation tools for contributions to the Geneweaver project
  - This should include high level architectural tests,
  - Functional tests of high level interfaces,
  - Validation of contribution guidelines (e.g. code syntax, documentation of code, etc.)

## Progressive Refactoring of Analysis Tools
The final common request from stakeholders is the need for a framework for enabling a progressive refactoring of Analysis
tools, such that tools can be used and improved incrementally, apart from the development of the larger Geneweaver.org
website. 

### Deliverables
- A software architecture to allow for Geneweaver to use module based analysis tools
- A software architecture to allow for the creation of module based analysis tools

## Stretch Goals
The following are stretch goals for the project. These are not required for the project to be considered a success, but
would be nice to have, and can be worked on if time permits.

- A data model design to allow for versioning of external sources data
- A bug reporting process for the Geneweaver project
- Improvements to the external sources data collection process

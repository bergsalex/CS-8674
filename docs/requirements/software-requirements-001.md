# Geneweaver 3 - Software Requirements 001

## 1. Introduction

### Purpose
This project intends to redesign the Geneweaver system while taking full account of the three independent project 
stakeholders: Educators and Students, Scientific Curators, and Genomics/Bioinformatics Researchers.

### Intended Audiences
This document is intended for all contributors to the Geneweaver project. This includes clients and stakeholders, 
developers, testers, and technical writers, past, present and future. This document outlines the scope of the current 
work on the project required to fully implement the Geneweaver 3 system for all identified stakeholders and priorities.

### External Documents
- [Clients and Stakeholders](./clients-and-stakeholders-001.md)
- [Operating Environment](./operating-environment-001.md)
- [Conventions](./conventions-001.md)

## 2. Overall Goals

### 2.1 Enable Genomics Researchers

### 2.2 Enable Scientific Curators

### 2.3 Enable Computer Science Educators and Students

## 3. Background and Context
### Background
Geneweaver is a website based "system for the integration and analysis of heterogeneous functional genomics data." The 
system has three core user groups: genomics researchers, expert literature curators, and computer science educators and 
students. The system allows users to upload sets of genes, search for curated sets of genes, and then use a suite of 
analysis tools to compare, combine, and investigate those sets of genes.

### Product Description

### Product Features

## 4. Assumptions

## 5. User Stories

### 5.1 Contribution Guidelines and Requirements
In order for the code base to be used and expanded upon by future developers, the code must be well documented and the
standards for contributing to the code base must be clearly defined. 

#### 5.1a Contribution Guidelines as Automated Tests
The contribution guidelines should be defined as automated tests. This will ensure that the contribution guidelines are
clearly defined and that they are enforced by the automated testing framework. This will make it easier for contributors
and collaborators to engage with the project by ensuring that they are able to easily understand the contribution
guidelines and that they are able to easily follow them.

### 5.2 Educational Use-case Documentation
The Geneweaver system is intended to be used by educators and students in a variety of courses. The system must be
designed to be easily understood by non-experts and to be easily used in a variety of courses.

#### 5.2a High Level, Non-expert Centric Product Overview
The Geneweaver system needs to have a product description that is accessible to non-experts. This description should
include a high level overview of the system, a description of the system's intended use, and a description of the 
system's features. It should also include an overview of the biology and genomics concepts that underpin the design of
the system.

#### 5.2b Use-cases for Non-multidisciplinary Courses
Documentation is needed on how Geneweaver can be utilized by courses which require no prior knowledge of genomics or
bioinformatics. This should include documentation on example use-cases that do not require an extensive background in
genomics or bioinformatics.

#### 5.2c Example Exercises and Component Use-cases
It would be useful to have a set of example exercises that can be used by educators to demonstrate the use of the
Geneweaver system in their courses. There should be a variety of exercises that can be used in a variety of courses,
including Genomics, Bioinformatics, Computer Science, and Data Science.

#### 5.2d Use-cases for Multidisciplinary Courses
Documentation is needed on how Geneweaver can be utilized by courses which require prior knowledge of genomics or
bioinformatics. The current documentation is aimed specifically at expert curators and post-graduate researchers. It
would be useful to have documentation that is aimed at educators and students who have some prior knowledge of
genomics and bioinformatics.

### 5.3 Set-up and Installation Documentation
The current documentation for setting up and installing the Geneweaver system is not sufficient. The documentation
should be improved to include a step-by-step guide for setting up and installing the system. The documentation should
also include a guide for setting up and installing the system on a local machine for development and educational
purposes.

### 5.4 Set-up Processes Improvement
The current set-up processes for installing the Geneweaver system are too complicated and do not work on all
operating systems. The set-up processes should be improved to be more user-friendly and to work reasonably well on all 
operating systems. This will require de-coupling major components of the system and making them more modular, as the
highly coupled nature of the current system makes it difficult/impossible to install dependencies on some operating
systems (see User Story 5.9).

### 5.5 System Architecture and Design Documentation
Documentation of the systems overall architecture and design is needed to allow new contributors and educational 
collaborators to understand the system and to allow them to contribute to the system. This documentation should
include a high level overview of the system's architecture and design, a description of the system's components, and
a description of the system's data model.

### 5.6 External Data Sources Documentation
Documentation of the external data sources used by the Geneweaver system is needed to allow new contributors and
educational collaborators to understand the source of the data used by the system. This documentation should include
a description of the data sources, a description of the data model used by the data sources, and a description of the
data model used by the Geneweaver system.

### 5.7 External Data Sources Collection, Process Improvement
The current process for collecting data from external data sources is too complicated, is not automated, and is 
maintained by a single person. The process should be improved to be more automated and to be more easily maintained
by multiple people.

### 5.8 Allow Versioning of External Data Sources Model
The current system does not allow for the versioning of the external data sources model. This makes it difficult to
reproduce results and to maintain the system. The system should be modified to allow for the versioning of the external
data sources model. This will require modifying the data-model of the external data sources and the data-model of the
Geneweaver system to allow for the versioning of the external data sources model.

### 5.9 Decoupling and Modularization of Analysis Tools
The current system is highly coupled and difficult to maintain. The source code for all analysis tools are contained in
a single repository, and the tools must be installed into the main Geneweaver system in order to be used. This makes
it difficult to install the system on some operating systems and makes it difficult to maintain the system. The system
should be decoupled and modularized to make it easier to maintain.

#### 5.9a Decoupling and Modularization of Analysis Tools - Tool Interface
An interface for analysis tools should be created to allow analysis tools to be used by the Geneweaver system without
having to be installed into the Geneweaver system. This interface should define how data is passed to and from the
analysis tools and how the analysis tools are invoked.

#### 5.9b Decoupling and Modularization of Analysis Tools - Tool Plugin Architecture
A plugin architecture should be created to allow analysis tools to be used by the Geneweaver system without having to
be installed directly into the Geneweaver system. This plugin architecture should define how analysis tools are loaded 
and invoked by the Geneweaver system.

### 5.10 Package Based Architecture
In order to facilitate broader contributions to the Geneweaver system, the system should be re-architected to be more
modular and to use a package based architecture. This will allow the system to be more easily maintained and will 
allow the system to be more easily extended by third parties. This will also allow geneweaver components to be used 
independently of the Geneweaver system as a whole, making it easier to use Geneweaver in educational and data-science
contexts.

### 5.11 Data-upload, Process Improvements
The current process for data-uploading uses a proprietary data format and is not automated. It should be improved to
use a more standardized data formats, which will improve efficiency and will make it easier for users to upload data
to the system. The process should also be improved to be more automated, which will improve efficiency and will make
it easier for users to upload data to the system.

### 5.12 Data-download, Process Improvements
The available data-download formats should be evaluated, and non-proprietary formats should be added. This will make
it easier for users to download data from the system and to use the data in other contexts, increasing the potential
for collaboration and for the use of the system in educational contexts.

### 5.13 Bug-reporting and Issue Tracking
The current system does not have a functional bug-reporting or issue tracking system. A bug-reporting and issue tracking
system should be created to allow users to report bugs and issues with the system and to allow developers to track and
resolve bugs and issues. This system should be integrated with the Geneweaver system and should be accessible to all
users. The system should be designed to support the broad contribution goals of the system, allowing for the reporting
of bugs and issues by non-technical users, and allowing for the resolution of bugs and issues by a variety of 
contributors.

## 6. User Interface and Design

## 7. Questions

## 8. Not Doing



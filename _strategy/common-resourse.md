---
title: Managing data as a common resource
status: draft
permalink: /strategy/data-is-a-common-resource
layout: strategy-chapter
order: 30
toc: true
---

## Foundational data

Foundational data is the fundamental data within the municipal data ecosystem, the basic business data that is essential for the municipality’s central functions. The data processed as foundational data should be of sufficient quality that it should provide a common understanding of what the data is about, what it contains and where it can be found. Ideally the municipality's departments should be able to access foundational data directly from the source, and so not need to make a copy of the data. However, within the municipality's environment multiple systems and transforming IT environments often mean that this is not the case. Without common foundational data, it is difficult, or impossible, to combine information resources reliably and efficiently, which means that the ability of the data strategy to have impact will be limited. The first step therefore is to identify the key foundational data categories required for data driven decision making and implement fixes and improvements to make sure this data is usable across the organisation. Challenges that might currently exist, and need to be addressed, are as follows (not exhaustive):

* Foundational data is missing
* Foundational data is distributed across multiple different systems
* Copies of foundational data are being used instead of the foundational data itself
* Foundational data is being manually maintained
* Identifiers, metadata is missing or not accessible 

This strategy recommends one of the functions of the Data Group is to carry out this foundational data analysis and, through the data council, make improvements in order to build the target state for each of the data, ensuring quality and usage of the municipality's foundational data.

## Data should be findable, accessible, interoperable and reusable

The main objectives of data governance are to ensure data quality, data security and privacy, and data accessibility, remembering that data is only an asset to an organisation if it is used. Data management needs to be organised across the organisation to ensure adherence to data governance standards. However, in the municipality currently, there are hundreds of different systems and technologies being used across siloed departments and agencies, which means different ways of storing, updating and using data. Both systems and people process data differently leading to significant data quality challenges. This further becomes problematic when this data needs to be combined for reporting, analysis and models, if it even is able to be combined. Therefore investment in data governance, especially data quality and interoperability, will lead to a greatly improved secondary use of data, in order to promote data-driven decision making. This will also help with the ability to audit what data is being used where, for what purpose, and so ensure data is being kept secure, and where necessary, private.

Generally accepted data usage principles for an organisation is the [FAIR](https://www.go-fair.org/fair-principles/) model - which requires that data is findable, accessible, interoperable, and reusable, in order to maximise the use of data, and the investment in data, within the organisation.

**Findable:** The first step in (re)using data sets is to find them. Metadata and data should be easy to find for both humans and computers. Machine-readable metadata are essential for automatic discovery of datasets and services. In order to support this, a municipality-wide data catalogue that contains information about data, i.e. the metadata, needs to be established. The metadata includes information relevant to the findability and utilisation of the associated data, such as where the data can be found, a persistent data identifier, information about the content of the data and any restrictions on the utilisation of the data.

**Accessible:** Once the user finds the required data, she/he/they need to know how they can be accessed, possibly including authentication and authorisation. This means that the municipality needs to establish within data management data classification that can guide any user, internal or external, on how to access the data.

**Interoperable:** The data usually needs to be integrated with other data. In addition, the data needs to interoperate with applications or workflows for analysis, storage, and processing. This means there need to be commonly agreed upon identifiers, concepts, and ontologies for all data within the municipality.

**Reusable:** The ultimate goal of FAIR is to optimise the reuse of data. To achieve this, metadata and data should be well-described so that they can be replicated and/or combined in different settings. In all data activities, the municipality should invest in the reusability of data. This means building the capabilities within the organisation to be able to ensure that data that is accessed or created within the organisation has the legal and technical parameters to facilitate its reuse.

### Data Quality

There are many models for data quality, but typically six factors determine the the quality of data (from DMBOK:

- Timeliness - is the data available in the timeframe it is needed for use?
- Completeness - is all the data required for use available?
- Uniqueness - can this data be mistaken for other entries?
- Consistency - is the data the same within and between datasets?
- Validity - is the data within the defined requirements such as format, type and range?
- Accuracy - to what extent does the data represent reality?

The municipality needs to develop common data quality metrics based on the above to enable continual data quality improvement as the municipality utilises and grows its data capabilities. These data quality standards and metrics will empower data custodians and owners to monitor current usage and improve data quality over time. This will also mean that inadequate data is not used in data analysis, resulting in less-accurate outcomes.

## Data Classification

In order to facilitate the use of data within the organisation, data classification provides the ability to identify datasets subject to common rules and operating methods. This results in better data processing, data security and data management. It also facilitates risk assessment and better communication around data utilisation and sharing. Data is typically classified by content type, by usage, and by processing rules.

Content-based classification can refer to the nature of the data, and includes the following:

- Identifier - whether the data is about a person, an organisation, an area, etc
- Characteristics - items such as the data source, collection time and location, and other information related to the data
- Data Processing Level - raw data, aggregated data linked to an identifier, data not linked to an identifier
- Data Processing Rules - whether the data is restricted, confidential, internal-only or public/open
- Data categories - for example master data, transactional data, reference data, structured or unstructured, etc

Usage-based classification refers to the intended use of data, and includes the following:

- Processing and storage - where the data is sourced from and where the data is stored
- Lifecycle of the data - the period the data is kept for, which can range from immediate deletion to permanent storage
- Use case - the purposes for which data is collected and used
- Legal framework - whatever obligations and restrictions are imposed on the data by all relevant legislation
- Users and user rights - who has access to different types of data

The municipality data group must undertake to classify data according to defined data classification standards when creating the data catalogue and data hub. Especially important will be to classify the data by its processing rules, thereby unlocking its usability throughout the organisation.

## Data ownership

In order to implement the data strategy both direct and transversal resources are required. These includes:


- **Data Stewards**: subject experts with a thorough understanding of a particular data set. The Data Steward of a data resource is responsible for ensuring the classification, protection, use, and quality of that data, in line with the Data Governance standards set by the Data Owner. Data stewards may exist in departments and agencies or operate more centrally, and are fundamentally responsible for the use of data within an organisation. Data stewards typically support data owners.
- **Data Custodians**: A Data Custodian is responsible for implementing and maintaining security controls for a given data set in order to meet the requirements specified by the Data Owner. This is typically an IT role.
- **Data Owners**: the person accountable for the classification, protection, use, and quality of one or more data sets within an organisation. This responsibility involves activities including, but not limited to, ensuring that:
    - The organisation’s Data Catalogue is comprehensive and agreed upon by all stakeholders
    - A system is in place for auditing and reporting data quality
    - An escalation matrix is in place for data quality issues
    - Actions are taken to resolve data quality issues within a defined timeframe

## Data Architecture

<img src="/assets/strategy/stack.svg" alt="A stack diagram showing foundational data at the bottom, common data infrastructure in the middle, and supporting multiple outcomes at the top" width="400"/>

As shown in the figure above, in order to implement data-driven mechanisms in the municipality, the municipality has to attain a modern technology architecture capable of organising, and surfacing, data in a way that maximises its useability and shareability. This is a challenge for the municipality given the number of systems that currently exist in its technology stack. It is also possible that some municipality data is stored in systems controlled by third parties. The core principle of the target data architecture, as in line with the FAIR model, is to make sure all municipality data is accessible via a similar mechanism. To this end, common APIs and API policies should be created and implemented. A municipality-wide data system (a data hub) should be created to interact with the systems inside municipality departments and agencies, that can act as an example as APIs within municipal departments and agencies come online. 

The data group needs to work with IMU in creating an understanding of the “as-is” data architecture of the municipality, and designing a target architecture, ideally distributed / semi-distributed, that results in the success of the data strategy. This roadmap should be able to be implemented iteratively to ensure that the data strategy can begin to be implemented from day one, and through this, architecture begins to evolve to meet the needs of the strategy implementation.


## Actions

* Design and test a single process adopting open standards for data and identifiers
* Conduct assessment of the municipality's current data infrastructure (using the Wardley mapping technique)
* Publish a foundational data catalogue and an API catalogue (based on the findings of the assessment)
* Define the responsibilities of a data custodian to support transversal outcomes
* Design and test a single process for departments to request access to data from other departments
* Publish API guidance in the data manual
* Adopt the one-only principle for data
---
layout: project
name: eosclife
title: EOSC-Life
path: eosclife
collection: projects
description: The EOSC-Life project develops an open collaborative space for digital biology in Europe
logo: eosc-life20k.png
website: https://elixir-europe.org/news/eosc-life-start
start_date: 2019-03-01
duration: 48 months
project_reference: https://cordis.europa.eu/project/rcn/219199/factsheet/en
---

EOSC-Life brings together the 13  Biological and Medical ESFRI research infrastructures (BMS RIs) to create an open collaborative space for digital biology.  It is our joint response to the challenge of analysing and reusing the prodigious amounts of data produced by life-science. Managing and integrating this data is beyond the capabilities of most individual end-users and institutes. By publishing data and tools in a Europe-wide cloud EOSC-Life aims to bring the capabilities of big science projects to the wider research community.  Federated user access (AAI) will allow transnational resource access and authorisation. EOSC-Life establishes a novel access model for the BMS RI: through EOSC scientists would gain direct access to FAIR data and tools in a cloud environment available throughout the European Research Area. 

EOSC-Life will make BMS RIs data resources FAIR and publish  them in the EOSC following guidelines and standards (e.g. EDMI). Overall this will drive the evolution of the RI repository infrastructure for EOSC and integration of the BMS RI repositories. EOSC-Life will implement workflows that cross disciplines and RI boundaries and address the needs of interdisciplinary science. Through open hackathons and bring-your-own-data events we will co-create  EOSC-Life  with our user communities , providing a blueprint for how the EOSC supports wide-spread and excellent data-driven life science research. EOSC-Life will address the data policies needed for human research data under GDPR. Interoperable provenance information describe history of sample and data to ensure reproducibility and adherence to regulatory requirements.

The goal of the EOSC-Life project is to make sure that life-scientists can find, access and integrate life-science data for analysis and reuse in academic and industrial research. EOSC-Life will transform European life-science by providing an open, continent-scale, collaborative and interdisciplinary environment for data science.

## eScienceLab contribution

The eScience Lab is contributing in eScienceLab as part of ELIXIR-UK.

* WP1: Publishing FAIR RI data resources in EOSC
* WP2: _Tools Collaboratory_: Deployment of life-science data integration and analysis workflows in EOSC 
  * Implementation of a mechanism for publishing and sharing workflows across instances of the environment
* WP3: Demonstrators and Open Calls for User Projects

We will address cross-RI interoperability in the EOSC by fostering implementation of tools and workflows in
an integrated EOSC environment. To this end, this task will leverage pre-existing work on standardization and,
where possible, try to synergize with relevant efforts such as GA4GH Cloud Work Stream. 

The proposed integrated environment is to build on a limited number of components in the following areas:
* _software_ and _tools packaging_ will leverage existing efforts around package managers for software (e.g. [BioConda](https://bioconda.github.io/)) and containerization technology (e.g. [Docker](https://www.docker.com/), [Singularity](https://www.sylabs.io/singularity/)) with reference to standards from the [Open Containers Initiative](https://www.opencontainers.org/).
* _workflow composition_ and execution will rely on widely adopted standards for workflow specification (e.g. [Common Workflow Language](/activities/cwl/)) to ensure interoperability and re-usability across research infrastructure.
* an environment with a _graphical user interface_ (e.g. based on [Galaxy](http://galaxyproject.org/)) to support end-users with little or no experience in the design, customization and implementation of software pipelines.

![EOSC-Life architecture](/images/eosclife-architecture.png)

Tools and workflows must be findable and accessible. They should also be citable, have managed metadata profiles and openly available for review and analytics. The proposed registry solution will be built in the following components:

* A **Workflow Registry** based on a prior open source platform (e.g. myExperiment) that is workflow system agnostic, supports a repository of workflows in native and standardised form (e.g. CWL) and the virtual aggregation of established tool, workflow and registries to support discovery over a fragmented ecosystem.  The federated registry would support a common API to simplify access for tool developers.
* Standardised _workflow identifiers_ and _metadata descriptions_ (e.g. CWL) needed for workflow discovery, reuse, preservation, interoperability and monitoring and metadata harvesting using standard protocols.  Workflows are usually multi-component (requiring links to test data, example runs, explanatory documentation, etc) and used in collections for scientific use cases. We plan to use the Research Object specification for packaging workflows, which has already been combined with CWL and is part of the [BioComputeObject](http://biocomputeobject.org/) specification.
* Workflow snapshot preservation, publishing, citation and monitoring, credit claiming and workflows part of the scholarly communication landscape partnering with platforms like DataCite and EOSC’s OpenAIRE and their Research Community Dashboards linking publications with workflows, associated datasets, software, etc.

The workflow registry is planned to be based on the [SEEK platform](/products/seek/) using [Common Workflow Language](/activities/cwl/) and [Research Objects](/products/researchobject/) to glue in federated workflow and tool descriptions across the research infrastructures.

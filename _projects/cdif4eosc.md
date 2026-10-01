---
layout: project
name: cdif4eosc
title: "CDIF4EOSC"
path: cdif4eosc.html
collection: projects
description: Developing and implementing the Cross-Domain Interoperability Framework for EOSC
logo: cdif4eosc.png
website: https://www.cdif4eosc.eu/
start_date: 2026-06
duration: 36 months
project_reference: https://doi.org/10.3030/101292473
tags:
  - FAIR data
  - EOSC
  - interoperability
  - CDIF
  - RO-Crate
  - FAIR Digital Objects
  - data quality
---


**CDIF4EOSC** is a Horizon Europe project developing and implementing the **Cross-Domain Interoperability Framework (CDIF)** for the European Open Science Cloud (EOSC). 
The project is funded by call [HORIZON-INFRA-2025-01-EOSC-02](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/opportunities/topic-details/HORIZON-INFRA-2025-01-EOSC-02) and coordinated by [CODATA](https://codata.org/).

## Project summary

Research addressing complex scientific and societal questions increasingly needs to combine data across disciplines, infrastructures and sectors. Although the FAIR principles provide a valuable high-level direction, they do not prescribe the detailed standards, metadata, semantics and implementation practices needed to make heterogeneous data practically interoperable and reusable.

CDIF4EOSC will turn CDIF into a comprehensive and actionable **CDIF4EOSC Playbook** for FAIR integration in EOSC and beyond. The Playbook will combine recommendations, implementation profiles, worked examples, sample code, tools and services. It will support a FAIR-by-design approach in which research outputs are created as machine-actionable FAIR Digital Objects with sufficient information for discovery, assessment, processing, combination and reuse.

The project advances FAIR integration in three connected ways:

1. **Beyond the original FAIR principles:** incorporating data quality, sensitive-data management, trust, provenance and data governance.
2. **At metadata and data level:** showing how data and other research outputs can be made FAIR-by-design and integrated for concrete research purposes.
3. **At infrastructure level:** integrating FAIR-enabling practices, tools and services with the EOSC Federation, EOSC Nodes and Common European Data Spaces.

The Playbook will be developed iteratively with three cross-domain use cases:

- ocean sciences;
- social sciences and environmental data; and
- safe-and-sustainable-by-design materials.

These use cases will identify requirements, test the recommendations and supporting services, and demonstrate their benefits in operational data pipelines. The project will also develop reusable AI-assisted FAIRification tools for metadata extraction and enhancement, semantic mapping, data-quality description, variable description, access and usage information, and packaging of FAIR Digital Objects.

## What is CDIF?

The [**Cross-Domain Interoperability Framework (CDIF)**](https://codata.org/initiatives/making-data-work/cdif/) is an international, discipline-neutral and extensible framework for implementing FAIR and enabling interoperability. It was initially developed by the WorldFAIR project.

CDIF does not propose a single universal metadata format. Instead, it provides profiles that address particular functional requirements and explain how established, domain-neutral standards can work together. Existing CDIF profiles cover discovery, access, integration, controlled vocabularies and common concepts such as location, time and units of measurement.

CDIF4EOSC will expand these profiles to cover areas including:

- machine-actionable navigation;
- AI-ready data descriptions;
- FAIR software and interoperable repositories;
- machine-actionable access and usage conditions;
- complex scientific variables and their semantics;
- semantic mappings and descriptions of semantic artefacts;
- provenance, context and data quality;
- legal and organisational interoperability; and
- packaging of FAIR Digital Objects.

The resulting Playbook is intended to provide the practical implementation detail that sits between high-level FAIR and EOSC interoperability principles and the standards, metadata, services and examples needed by implementers. CDIF4EOSC places particular emphasis on scientific variables, associated concepts, data structure, provenance and quality, treating these as essential information for meaningful reuse rather than optional domain-specific additions.

## The role of RO-Crate

[**RO-Crate**](/products/researchobject/) is the principal approach used by CDIF4EOSC for packaging FAIR Digital Objects. It provides a community-driven way to package research outputs, such as data, software, workflows, publications and images, together with structured metadata describing their identities, relationships, provenance and context.

Within CDIF4EOSC, RO-Crate has a **structural glue** role. It is not expected to replace the specialist standards used by the other CDIF profiles. Instead, an RO-Crate can bring together a research object and the different descriptions needed for FAIR integration. For example, it can identify:

- the data, software and other constituent research outputs;
- relationships among those outputs;
- provenance and lineage information;
- the CDIF profiles and vocabulary versions being followed;
- machine-actionable rights or usage statements;
- variable and structural descriptions; and
- data-quality assessments and how they were produced.

This means that specialist descriptions can remain expressed using the most appropriate standards while RO-Crate records how they belong together as one machine-actionable research object.

The eScience Lab leads the work on the CDIF4EOSC profile for **packaging FAIR Digital Objects**. Manchester also contributes RO-Crate expertise to the iterative development of the Playbook and to the technical tools and services. These services include packaging integrated research artefacts and metadata as RO-Crate for use in FAIRification pipelines and subsequent publication to repositories and infrastructures.

RO-Crate will also be tested in the project's use cases alongside other CDIF technologies. This will help demonstrate how research outputs can move through domain-specific pipelines while retaining sufficiently rich and connected metadata for cross-domain discovery, assessment and reuse.


## eScience Lab involvement

* WP1: CDIF4EOSC Playbook (lead: CODATA)
  - Task T1.1: Develop the roadmap for the CDIF4EOSC Playbook (lead: CODATA)
  - Task T1.2: Develop the new profiles for the CDIF4EOSC Playbook, iteration cycles 1 (lead: CODATA)
    - **UNIMAN leads the profile for packaging FAIR Digital Objects using RO-Crate**
  - Task T1.3: Further develop the CDIF4EOSC Playbook, iteration cycles 2 (lead: CODATA)
  - Task T1.4: Finalise and launch the CDIF4EOSC Playbook v1.0 (lead: CODATA)
  - Task T1.5: Sustainability planning for the CDIF4EOSC Playbook (lead: CODATA)
  - Deliverable D1.1: CDIF4EOSC Playbook Roadmap (lead: CODATA)
  - Milestone MS1: Development and evaluation workshop 1 (lead: CODATA)
  - Milestone MS2: Development and evaluation workshop 2 (lead: CODATA)
  - Deliverable D1.2: CDIF4EOSC Playbook v1.0 (lead: CODATA)
    - Includes the FAIR Digital Object packaging profile developed by UNIMAN using RO-Crate
  - Milestone MS3: CDIF4EOSC Playbook v1.1 (lead: CODATA)
  - Deliverable D1.3: CDIF4EOSC Sustainability Plan (lead: CODATA)
* WP2: Data Quality Protocols and Infrastructure (lead: 7P9-DE)
  - Task T2.1: Stocktaking and roadmapping (lead: 7P9-DE)
  - **Task T2.2: Generalised Data Quality Framework for CDIF4EOSC (lead: UNIMAN)**
  - Task T2.3: Evaluation of use-case-specific test implementations of the Data Quality Framework (lead: 7P9-SI)
  - **Milestone MS4: First version of data quality assurance and documentation specification for development in the CDIF4EOSC Playbook (lead: UNIMAN)**
  - **Deliverable D2.2: Data Quality in CDIF4EOSC (lead: UNIMAN)**
* WP3: CDIF4EOSC Tools and Services Development (lead: UESSEX)
  - Task T3.1: Technical Design Specification (lead: UESSEX)
  - Task T3.2: Initial prototyping of Tools and Services (lead: UESSEX)
    - Includes the DataProductPackager for packaging integrated research artefacts and metadata as RO-Crate
  - Task T3.3: Tools and Services Iterative Development and alignment with Use Cases, EOSC Nodes and Data Spaces (lead: UESSEX)
    - Includes further development and production-level implementation of the RO-Crate DataProductPackager
  - Deliverable D3.1: CDIF4EOSC Technical Design Specification Version 1.0 (lead: UESSEX)
  - Deliverable D3.2: Publication of CDIF4EOSC Tools and Services at TRL5/6 on to Public Repository (lead: UESSEX)
    - Includes the initial RO-Crate packaging implementation developed through T3.2
  - Deliverable D3.3: Publication of CDIF4EOSC Tools and Services at TRL8+ on to Public Repository (lead: UESSEX)
    - Includes the production-level RO-Crate packaging implementation developed through T3.3
  - Deliverable D3.4: CDIF4EOSC Technical Design Specification Version 2.0 (lead: UESSEX)
* WP8: Project Coordination (lead: CODATA)
  - Task T8.2: Quality assurance, risk, IPR and ethics management (lead: CODATA)
  - Task T8.3: Project management, reporting and financial/legal issues (lead: CODATA)
  - Task T8.4: Policy Briefs (lead: CODATA)

## References

- [CDIF Handbook](https://cross-domain-interoperability-framework.github.io/cdifbook/)

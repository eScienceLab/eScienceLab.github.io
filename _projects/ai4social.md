---
layout: project
name: ai4social
title: "AI4Social+"
path: ai4social.html
collection: projects
description: AI Readiness for Social Impact
logo: ai4social.png
website: https://eosc.eu/horizon-europe-projects/ai4socialplus
start_date: 2026-10
duration: 36 months
project_reference: https://doi.org/10.3030/101292886
---
*Preparing research data, models, workflows and infrastructure for trustworthy and reproducible AI-assisted science*

[AI4Social+](https://eosc.eu/horizon-europe-projects/ai4socialplus) is a Horizon Europe project funded under [HORIZON-INFRA-2025-01-EOSC-03](https://cordis.europa.eu/project/id/101292886/de), grant 101292886, and coordinated by [Barcelona Supercomputing Centre](https://www.bsc.es/) (BSC).

AI4Social+ will advance AI readiness and machine actionability within the [European Open Science Cloud](https://eosc.eu/) (EOSC). It will make it easier for researchers to assess, prepare and reuse data, models and computational workflows for AI-assisted research while following Open Science and trustworthy-AI practices.

Starting with the social sciences and humanities, the project combines five connected areas:

* the **AI Readiness Common Hub (ARCH) Framework and Toolkit**;
* AI-assisted tools for machine-actionable data repositories;
* a portable infrastructure platform combining data management, workflows, cloud and high-performance computing;
* five research use cases spanning social, humanities, climate and health research; and
* a sustainable AI4Social+ Competence Centre providing guidance, training and community support.

The ARCH Framework will define AI readiness across the research lifecycle, including data preparation and quality, metadata, provenance, access conditions, portability, reproducibility and responsible AI practice. The accompanying ARCH Toolkit will provide assessment methods, profiles, guidance, validation tools and reference implementations.

The infrastructure platform will integrate https://galaxyproject.org/, COMPSs and Onedata. This will support AI model training, fine-tuning and inference across cloud and HPC resources while retaining information about the data, software and workflows used to produce research results.

## Research use cases

AI4Social+ will validate its framework, tools and infrastructure through five use cases:

1. portable life-course foundation models for cross-national employment trajectories;
2. AI-assisted transcription and analysis of handwritten historical collections;
3. AI tools for climate and health policy;
4. AI-assisted social simulation for actionable hypothesis generation; and
5. analysis of citation and semantic relationships to support interdisciplinary discovery.

The use cases will provide requirements and testing for the project's technical work while producing reusable AI models, datasets and computational workflows.

## RO-Crate and AI readiness

[RO-Crate](/product/researchobject/) has a central role in AI4Social+. It provides the main transport and metadata mechanism for connecting AI-ready datasets, models and computational workflows as FAIR Digital Objects.

The ARCH metadata framework will build on RO-Crate alongside standards and approaches including Croissant, FAIR4ML, DOME, CDIF, DDI-CDI, DCAT and DPV/ODRL. 

These descriptions will support provenance, portability and validation. They will also allow tools to determine whether research objects comply with the ARCH Framework and contain the information needed for reuse on another platform.

The project will develop RO-Crate FAIR Digital Object profiles for AI readiness and extend existing profiles where necessary to describe portable AI models, data and workflows. Workflow outputs will be packaged as enhanced RO-Crates, with workflows published through [WorkflowHub](https://workflowhub.eu/) and related research objects deposited in suitable repositories.

The project will also use the RO-Crate support in Dataverse to connect published AI models with their datasets, provenance and originating computational workflows.

## eScience Lab involvement

The eScience Lab leads substantial parts of the ARCH Framework and Toolkit work. We contribute expertise in RO-Crate, [WorkflowHub](https://workflowhub.eu/), FAIR Digital Objects, computational workflows, provenance and research object exchange.

We lead the internal validation work package and is responsible for developing the ARCH assessment methodology, metadata framework and portability tests. This work will use RO-Crate profiles to connect AI-ready data, models and workflows and to test whether these research objects can be interpreted and reused across tools and infrastructure platforms.

### eScience Lab contributions

* WP1: Project Management and Coordination: Initiation and Running (lead: BSC)
  - Task T1.1: Scientific and Technical coordination (lead: BSC)
  - Task T1.3: Administrative and financial management (lead: BSC)

* WP2: Project Management and Coordination: Reviewing and Concluding (lead: BSC)
  - Task T2.1: Scientific and Technical coordination: Review and Concluding (lead: BSC)
  - Task T2.3: Administrative and financial management (lead: BSC)

* WP4: AI Readiness Framework Co-Design and Definition (lead: KCL)
  - Task T4.1: Review the AI-readiness landscape of frameworks, metadata standards and ethics considerations (lead: CODATA)
  - Task T4.2: AI Readiness Requirements Co-creation workshop (lead: KCL)
  - Task T4.3: AI Readiness Assessment Methodology, first version of toolkit and feedback loop (lead: UNIMAN)
  - Deliverable D4.3: ARCH toolkit review (lead: UNIMAN)

* **WP5: AI Readiness Framework Internal Validation (lead: UNIMAN)**
  - Task T5.1: Use case-based assessment of ARCH (lead: KCL)
  - **Task T5.2: ARCH Standard validation and portability tests (lead: UNIMAN)**
  - Milestone MS6: First Validation Workshop completed (lead: UNIMAN)
  - Milestone MS7: First draft of metadata blueprint (lead: UNIMAN)

* WP6: AI Readiness Framework Community Adoption (lead: KCL)
  - Task T6.1: ARCH Toolkit as an EOSC product (lead: KCL)
  - Task T6.2: ARCH implementation, external adoption and sustainability (lead: CODATA)
  - **Deliverable D6.1: Release of the ARCH Toolkit (lead: UNIMAN)**

* WP9: Infrastructure Platform Design and Proof of Concept (lead: AGH)
  - Task T9.1: Co-design of the technical architecture of the platform (lead: BSC)
  - Task T9.2: Co-design of the AI-related logic and processes (lead: UFR)

* WP10: Infrastructure Platform Implementation and Handoff (lead: UFR)
  - Task T10.4: Final implementation of distributed workflow execution services and tools catering for use cases (lead: UFR)

* WP14: Competence Centre Mapping and Architecture Conceptualization (lead: CESSDA)
  - Task T14.2: Community building on AI readiness in SSH (lead: CESSDA)

* WP15: Competence Centre Implementation and Capture Innovation (lead: CESSDA)
  - Task T15.1: Implementing the concept and architecture of the SSH AI Competence Centre (lead: CESSDA)
  - Task T15.2: Community engagement and training co-design (lead: CODATA)


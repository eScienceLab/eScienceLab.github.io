---
layout: project
name: eurosciencegateway
title: EuroScienceGateway
path: eurosciencegateway.html
collection: projects
description: Improving computational workflows in Galaxy by maturing Pulsar Network and publishing computational workflows as FAIR Digital Objects.
logo: eurosciencegateway.svg
website: http://eurosciencegateway.eu/
start_date: 2022-09-01
duration: 36 months
project_reference: https://doi.org/10.3030/101057388 https://gtr.ukri.org/projects?ref=10038963
---

## Motivation

In the past decade, many scientific domains have been transformed into data-driven disciplines relying on the exchange and integration of internationally distributed data. Exploiting this data is still a laborious and largely manual task, prone to losses and errors, and increasingly specialised beyond most users technical capabilities. [FAIR practices](https://doi.org/10.1038/sdata.2016.18) are encouraged but their adoption curve is steep. The needs for compute and data resources, tools, and application platforms are often domain-specific. 

Many scientists struggle to navigate this intricate ecosystem. Generally, researchers do not possess the computing skills to effectively use the HPC or Cloud platforms they need. Thus, new approaches are needed to enable all researchers, with widely ranging digital skills, to efficiently use the diverse computational infrastructures available across Europe, for asynchronous and for interactive applications.

## EuroScienceGateway

**EuroScienceGateway** will leverage a distributed computing network across 13 European countries, accessible via 6 national, user-friendly web portals, facilitating access to compute and storage infrastructures across Europe as well as to data, tools, workflows and services that can be customized to suit researchers' needs. 

EuroScienceGateway will deliver a robust, scalable, seamlessly integrated open infrastructure for data-driven research, contributing an innovative and customizable service for EOSC that enables operational open and FAIR data and data processing, empowering European researchers to embrace the new digital age of science.

### EOSC integration

At the heart of the proposal workflows will integrate with the [EOSC-Core](https://eoscfuture.eu/wp-content/uploads/2022/04/EOSC-Core.pdf). Adoption, development and implementation of technologies to interoperate across services, will allow researchers to produce high-quality FAIR data, available to all in EOSC. Communities across disciplines -- Life Sciences, Climate and Biodiversity, Astrophysics, Materials science - will demonstrate the bridge from EOSC's technical services to scientific analysis.

Funded by Horizon Europe call [HORIZON-INFRA-2021-EOSC-01-04](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/opportunities/topic-details/horizon-infra-2021-eosc-01-04) (_Enabling an operational, open and FAIR EOSC ecosystem_), EuroScienceGateway will work closely with [EOSC](https://www.eosc.eu/), EOSC projects including [EOSC-Life](../eosclife/), as well as established e-Infrastructures and life science communities like [ELIXIR](../elixir/).

### Galaxy and Pulsar Network

EuroScienceGateway will leverage the [Galaxy platform](https://galaxyproject.eu/) (an open, web-based platform for data-intensive research), the [Pulsar
Network](https://pulsar-network.readthedocs.io) (a wide job execution system distributed to scale computing power over heterogeneous resources) and
FAIR workflow services pioneered in the [EOSC-Life](https://www.eosc-life.eu/) cluster ([WorkflowHub](https://workflowhub.eu/), [Workflow RO-Crate](https://w3id.org/workflowhub/workflow-ro-crate/) and metadata standards like [schema.org](https://schema.org/)). 

EuroScienceGateway will lift Pulsar from TRL-7 to TRL-9 by expanding the APIs, hardening deployments and adding support for different usage patterns, e.g. data localisation during job scheduling. 

[National Galaxy instances](https://galaxyproject.org/use/) across Europe and other workflow management systems will be enabled to submit jobs to this distributed compute network. Pulsar will become a production-ready interface for European computing resources, including [EGI](https://www.egi.eu/) and [EuroHPC](https://eurohpc-ju.europa.eu/) as Pulsar providers.

### WP2: Stimulate FAIR and reusable research

* WP2 introduction slides: <https://doi.org/10.5281/zenodo.7152762>

The eScience Lab at The University of Manchester is leading the work package WP2 _Stimulate FAIR and reusable research_, contributing with our expertise on [FAIR Computational Workflows](https://workflows.community/groups/fair/)).

This work package adds sufficient measures to EuroScienceGateway to support FAIR practices for and by workflows. 

[FAIR Digital Objects](https://fairdo.org/) (FDOs), for exchanging, publishing, archiving and citing workflows and their companion data, provenance logs and associated resources, will be realized as [RO-Crate](/products/researchobject/#research-object-crate-ro-crate)s. 
 
The FDOs will be published through EOSC and in EOSC catalogues (e.g. [OpenAIRE](https://www.openaire.eu/)) and further communicated through outreach plans to increase uptake of the EuroScienceGateway in affiliated and newly targeted computational researcher communities. 

[WorkflowHub](../workflowhub/), a FAIR registry for workflows that is RO-Crate compliant, will be lifted to TRL-9 status (from TRL-7) and made the registry of choice for all workflow system types and for all disciplines in EOSC. 

By collaborating with the project CSA INFRA-01-EOSC-01-05 (_Enabling discovery and interoperability of federated research objects across scientific communities_), both the WorkflowHub and Workflow Digital Objects will be further aligned with the PID and metadata schema frameworks.


#### WP2 Objectives

* O2.1 Bringing FAIR workflows into EOSC through the EuroScienceGateway
* O2.2 Support reusable and reproducible workflows
* O2.3 Establish FAIR Digital Objects as citable exchange format for workflows for all EOSC services
* O2.4 Establish FAIR Workflow Digital Objects as publishable scholarly objects

## eScienceLab contributions

UK partners in Horizon Europe projects are funded through [Innovate UK](https://www.ukri.org/councils/innovate-uk/) (#10038963) from the [UKRI Horizon Europe guarantee](https://www.ukri.org/apply-for-funding/apply-for-horizon-europe-guarantee-funding/).

* WP2: Stimulate FAIR and reusable research (lead: UNIMAN)
  - Task T2.1: Integration of EuroScienceGateway in EOSC (lead: UNIMAN)
  - Task T2.2: Reproducible and reusable FAIR Digital Objects  (lead: UNIMAN)
  - Task T2.3: Using and enriching workflow FDOs (lead: UNIMAN)
  - Task T2.4: FAIR workflows as scholarly objects in scientific publishing (lead: EPFL)
  - Deliverable D2.1 Reproducible FAIR Digital Objects for workflows (lead: UNIMAN)
  - Deliverable D2.2 Publishing workflow enriched FDOs to EOSC (lead: UNIMAN)
* WP3: Pulsar Network: Distributed heterogeneous compute (lead: CNR)
  - Task T3.4 Add TES support to WfExS (Workflow Execution Service) (lead: BSC)-

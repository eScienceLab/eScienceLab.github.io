---
layout: project
name: everse
title: "EVERSE"
path: everse.html
collection: projects
description: European Virtual Institute for Research Software Excellence
#logo: everse.svg
#website: http://NOTeverse.eu/
start_date: Late 2023
duration: 36 months
#project_reference: https://doi.org/10.3030/101129744
---

The EVERSE project aims to create a framework for research software and code excellence, collaboratively designed and championed by the research communities, in pursuit of building a **European network of Research Software Quality** and setting the foundations of a future **Virtual Institute for Research Software Excellence**. 

<!-- copied from proposal, rewrite: -->

This project, funded by Horizon Europe call [HORIZON-INFRA-2023-EOSC-01-02](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/opportunities/topic-details/horizon-infra-2023-eosc-01-02) ([#101057344](https://doi.org/10.3030/101057344)) has the objectives:
1.  Build a collaborative, community-led structure for evaluating, verifying, and improving the quality of research software and code, by actively involving researchers, software developers, and other stakeholders in the research community.
2.  Leverage existing tools and resources to support the evaluation, verification and improvement of research software and code quality, based on existing practices and standards across research communities represented by the five EOSC Science Clusters.
3.  Establish a sustainable and collaborative ecosystem of stakeholders across the research communities associated with the five EOSC Science Clusters to ensure research software and code quality assurance and support the advancement of reliable and reproducible research.
4.  Provide a framework that will ensure appropriate recognition, reward, and career development for researchers and RSEs who implement research software and code quality assurance practices and policies.


The framework for research software excellence will incorporate aspects involving community curation, quality assessment, and best practices for research software. This collective knowledge will be captured in the **Research Software Quality toolkit** (RSQkit), a knowledge base to gather and curate expertise that will contribute to high-quality software and code across different disciplines.

By embedding the RSQkit and services into the EOSC Science Clusters, EVERSE will demonstrate improvements in the quality of research software and maximise its reuse, leading to standardised software development practices and sustainable research software. Furthermore, we will drive recognition of software and support career progress for developers, from researchers who code to RSEs, raising their capacity to guarantee software quality.

EVERSE ultimate ambition is to contribute towards a cultural change where research software is recognized as a first-class citizen of the scientific process and the people that contribute to it are credited for their efforts.

EVERSE is coordinated by the [Centre for Research and Technology hellas (CERTH)](https://www.certh.gr). The University of Manchester is participating in EVERSE with both the eScience Lab as well as Manchester Particle Physics Group, where Caterina Doglioni will co-lead WP4 for interfacing the [EOSC science clusters](https://eosc-portal.eu/esfri-thematic-cluster-projects) and their emerging use cases:

- [ENVRI-FAIR](https://envri.eu/home-envri-fair/): Essential Climate Variables
- [EOSC-Life](https://www.eosc-life.eu/): The Workflow Execution Service backend with RO-Crate
- [ESCAPE](https://projectescape.eu/): Particle physics and astrophysics in the Dark Matter Science Project
- [PaNOSC](https://www.panosc.eu/): Photon and neutron science through LEAPS/LENS
- [SSHOC](https://sshopencloud.eu/): UDPipe language processing suite


### eScienceLab involvement

Building on our engagement in [EOSC-Life](../eosc-life/), [Software Sustainability Institute](../ssi/), [ELIXIR](../elixir/) and [FAIR-IMPACT](../fair-impact/), the eScience Lab will focus on gathering best practice for research software quality and software development practices (WP2). This will be documented in a knowledge base Research Software Quality toolkit (RSQkit), building on our [RDMkit](/products/rdmkit) work.

In addition, as part of making a _common metadata framework for software quality_ (WP3), we will provide support for [RO-Crate](/products/researchobject) in the Workflow Execution Service ([WfExS](https://github.com/inab/WfExS-backend)) (WP4), continuing work started in [EOSC-Life](../eosc-life/), [BY-COVID](../by-covid/) and [TRE-FX](../tre-fx/). This aims to incorporate the [Five Safes RO-Crate](https://w3id.org/5s-crate/) into WfExS for secured and federated workflow orchestration, and to use community-led standards for research software packaged using container technologies.


UNIMAN contributions (including eScience Lab and Manchester Particle Physics Group):

* WP2: Community-led best practices for developing high-quality research software (leads: BSC, NLeSC)
  - Task T2.1: Landscape analysis of high-quality research software development best practices (leads: BSC, FAU)
  - Task T2.2: Curation and harmonisation of best practices for developing high-quality research software (leads: UPM, **UNIMAN**)
  - Milestone MS2.5: Final release of the RSQkit containing curated best practices and associated indicators (lead: UNIMAN)
* WP3: Tools and services for software quality and FAIRness (leads: CNRS-LAPP, UEDIN)
  - Task T3.2:  Consolidation of tools and services to ease their implementation and use in research communities (leads: BSC, FAU)
  - Task T3.3: To provide the means to measure globally the software quality in the Science Clusters (leads: NLeSC, UPM)
* WP4: EOSC Science Cluster Pilots and Driver Projects (leads: HZDR, UNIMAN)
  - Task T4.2: Integration and showcase of good practices through the community driven pilots (lead: UNIMAN, HZDR)
    * Subtask T4.2.1: Integration of Science Cluster ENVRI through ENVRI-HUB (lead: UvA)
    * Subtask T4.2.2: Integration of Science Cluster EOSC-Life through ELIXIR (lead: BSC)
    * Subtask T4.2.3: Integration of Science Cluster ESCAPE through the Dark Matter Test Science Project (lead: UNIMAN)
    * Subtask T4.2.4: Integration of Science Cluster PaNOSC through LEAPS/LENS (lead: HZDR)
    * Subtask T4.2.5: Integration of Science Cluster SSHOC (Lead: CU)
  * MS4.1: Initial list of community established metrics/good practices (..) (lead: UNIMAN)
  * MS4.4: Science clusters integrated into RSQkit (lead: UNIMAN)
* WP5: Capacity Building and Recognition
  - Task T5.3: Establish a long-term training activity, supported by the respective community services and platforms (leads: UniSalento, CERTH)


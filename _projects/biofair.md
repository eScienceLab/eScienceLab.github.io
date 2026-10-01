---
layout: project
name: biofair
title: BioFAIR
path: biofair.html
collection: projects
description: Supporting the UK’s life science community with world class digital infrastructure for data driven bioscience. BioFAIR Methods Commons aims to establish a world-leading, standards-based national infrastructure for FAIR computational workflows in the UK life sciences.
logo: biofair.png
website: https://biofair.uk/
start_date: 2024-04-01
duration: 5 years
project_reference:
  - https://www.ukri.org/news/ukri-invests-72-million-upgrading-uk-research-infrastructure/
  - https://biofair.uk/updates/2026/biofair-announces-4-million-investment-to-create-a-methods-commons-led-by-the-university-of-manchester/
---

**[BioFAIR](https://biofair.uk/) is a £34 million UK digital research infrastructure for the life sciences. It is a joint project of the Biotechnology and Biological Sciences Research Council (BBSRC) and the Medical Research Council (MRC), funded through the UKRI Infrastructure Fund and the UKRI Digital Research Infrastructure Programme.**

BioFAIR's aim is a step change in project Research Data Management (RDM) by developing and operating a national BioCommons digital infrastructure. It will maximise the Findability, Accessibility, Interoperability and Reusability (FAIR) and Reproducibility of UKRI-supported life science data and methods.

BioFAIR supports the production, sharing, integration and archiving of high quality, accessible data for digitally-driven life sciences. It does this by enabling end-to-end RDM and analytics, and by driving the culture change that this requires.

The UK hosts many well-supported, active public data archives and specialised environments, such as [EMBL-EBI](https://www.ebi.ac.uk/) and the [HDR UK](https://www.hdruk.ac.uk/) [Gateway](https://healthdatagateway.org/), which offer support and RDM for researchers using those environments. BioFAIR complements and enhances these national and international life science data infrastructures. Examples are submitting high-quality UK-generated data automatically to EMBL-EBI public archives, and providing a national platform for project-specific "bring your own data" (BYOD) analysis workflows using EMBL-EBI and UK data and tools.

## A federated BioCommons

BioFAIR is organised as a federated **hub-and-spokes** infrastructure. The **BioFAIR Hub** at the [Earlham Institute](https://www.earlham.ac.uk/) provides central coordination and shared foundational services, such as federated identity, cybersecurity, governance and procurement. It also connects the network through the BioFAIR Fellowships and Pathfinder Projects. The spokes are:

- **Methods Commons**: discovery, execution, sharing and reuse of computational workflows, tools and notebooks (see [below](#biofair-methods-commons))
- **Data Commons**: sharing of data, metadata and standards
- **People Commons**: the growing community of FAIR practice that will drive adoption
- **Knowledge Hub**: a central training capability
- **BioFAIR Portal**: access to expertise, tools and services

![BioFAIR overview: Data Stewardship, Training, user support, communities of practice. Uses Web Portal and API, covered by Tools, workflow catalogue. Calls BioFAIR hybrid e-infrastructure, multi-tiered storage and HPC/cloud to support the Data and Methods Commons. This access public deposition databases and public curated data resources in ELIXIR and beyond.  The e-infrastructure works with the BioFAIR Data Lake, that store project "core" data rather than raw data objects, in a DataHub Catalogue, Store & Broker. Calls then Generalist repositories, Institutional repositories and Lab file stores.  Through FAIR Data preparation & submission these can be lifted into the Public deposition databases.](/images/posts_images/biofair-overview.png "BioFAIR overview")
_Original concept of BioFAIR, adapted from ELIXIR All Hands 2023 poster <https://doi.org/10.7490/f1000research.1119446.1>_

The **Data Commons** will assemble, host and operate a coherent set of registries, repositories, data management and analysis services, giving UK users a seamless, end-to-end research environment. It will allow data to be used beyond the data creator’s original purpose, and uses community standards to ensure the research integrity and quality of data collection and analysis. It will bridge life scientists' cycle of *collection → analysis → sharing* across local, national and global data infrastructures, simplifying and streamlining their use.

BioFAIR was conceived by [ELIXIR-UK](https://elixiruknode.org/), which also produced the [BioFAIR Feasibility Study](https://doi.org/10.5281/zenodo.7924339).

## BioFAIR Methods Commons

In July 2026 BioFAIR [appointed a consortium]({% post_url 2026-07-02-biofair-method-commons %}) led by the **University of Manchester**, with the **Earlham Institute** and **Seqera**, to establish the [Methods Commons](https://elixiruknode.org/project/biofair-methods-commons/). It is the first spoke of BioFAIR. BioFAIR is investing up to **£4 million over an initial two-year period** (July 2026 to July 2028), and expects to extend the partnership through to June 2029 and beyond.

The Methods Commons aims to establish a world-leading, standards-based national infrastructure for FAIR computational workflows in the UK life sciences. It brings together the teams behind [Galaxy](https://galaxyproject.org/), [Nextflow](https://www.nextflow.io/) and the [WorkflowHub](/products/workflowhub/) registry, drawing on more than 20 years of running Europe's shared workflow services. Together they will join up the UK's currently siloed workflow provision into one environment. It will serve everyone from no-code biologists to expert developers, making it easy to find high-quality workflows, run them at scale and share them with full provenance.

The Methods Commons is built around five strategic pillars:

1. **Technical infrastructure**: scalable, cloud-based execution with a national Galaxy instance, an enterprise-grade Seqera/Nextflow platform, and JupyterLab with containerised environments (e.g. Snakemake, R) on AWS. It will have hybrid bridges to National Compute Resources.
2. **Workflow discovery**: [WorkflowHub](https://workflowhub.eu/) as the single access point for finding, sharing and reusing workflows in any language. It will host a curated **BioFAIR Workflow Collection** of endorsed, canonical workflows.
3. **Secure collaboration**: a **Shared Project Space** for private, access-controlled management of research data and results. It uses [Workflow Run RO-Crate](https://www.researchobject.org/workflow-run-crate/) provenance and foreshadows the BioFAIR Data Commons.
4. **Community mobilisation**: a tiered **Concierge Service** and a **Workflow Observatory** for expert support, onboarding and quality vetting of workflows, plus contributions to BioFAIR's Knowledge Hub and People Commons.
5. **Operational excellence**: governance, onboarding playbooks and standardised APIs (RO-Crate, [GA4GH](https://www.ga4gh.org/)) that embed FAIR practice across the workflow lifecycle, with pathways for onboarding further workflow systems and agentic AI.

Delivery follows an agile, two-phase Minimum Viable Product (MVP) approach. It is co-designed with nine [Exemplar Use Cases](https://stuzart.github.io/biofair-methods-commons/use-cases), from bioimaging and single-cell genomics to fungal genomics and environmental metagenomics, together with BioFAIR Fellows and the first cohort of BioFAIR Pathfinder Projects. More details are on the [Methods Commons website](https://stuzart.github.io/biofair-methods-commons/).

## eScience Lab involvement

Carole Goble is joint Head of Node of [ELIXIR-UK](https://elixiruknode.org/) and has been active in shaping BioFAIR since its conception. She is **Project Lead** of the BioFAIR Methods Commons. The University of Manchester team leads the WorkflowHub, RO-Crate, Shared Project Space and Workflow Observatory work. Team members include Stuart Owen, Shoaib Sufi, Munazah Andrabi and Stian Soiland-Reyes.

BioFAIR takes advantage of many of the [eScience Lab products](/products/):

- [WorkflowHub](/products/workflowhub/) is the registry and **Commons Hub** of the **BioFAIR Methods Commons**. It hosts the BioFAIR Workflow Collection and integrates with Galaxy and Nextflow execution, and with the [IWC](https://iwc.galaxyproject.org/) and [nf-core](https://nf-co.re/) community collections. The Workflow Observatory adds quality assurance through WorkflowHub's integration with [LifeMonitor](https://lifemonitor.eu/) testing and the [ELIXIR FAIR Checker](https://fair-checker.france-bioinformatique.fr/). This builds on [EOSC-Life](/projects/eosclife/)'s [Workflow Collaboratory](https://doi.org/10.5281/zenodo.4605654) and on Galaxy and Pulsar work in [EuroScienceGateway](/projects/eurosciencegateway/).
- [RO-Crate](/products/researchobject) and **Workflow Run RO-Crate** provide provenance for workflow runs from Galaxy and Nextflow, and the packaging behind the **Shared Project Space**. RO-Crate also supports **data collection** in the BioFAIR Data Commons, including a National Data Lake.
- [FAIRDOM-SEEK](/products/seek), the platform WorkflowHub is built on, provides cataloguing in the **Shared Project Space**. It is also part of the **BioFAIR DataHub**, an ISA-based metadata catalogue in the BioFAIR Data Commons.
- [RDMKit](/products/rdmkit/) is part of the _Data Stewardship toolkit_ in the **BioFAIR Data Commons**.
- [TeSS](/products/tess/) and [RSQkit](/products/rsqkit/) contribute training materials and guidance to BioFAIR's **Knowledge Hub** and **People Commons**.

BioFAIR is a UK-wide collaboration that goes well beyond the highlights above. See the [BioFAIR website](https://biofair.uk/) for more details.

## References

Carole Goble, Stuart Owen, Shoaib Sufi, Irene Papatheodorou, Nicola Soranzo, Evan Floden, Geraldine Van der Auwera (2026):  
**Methods Commons MVP: Shared home for reproducible, reusable bioscience computational methods**.  
_[BioFAIR Annual Showcase 2026](https://biofair.uk/biofair-annual-showcase-2026/)_, Cambridge, UK, 2026-05-14/--15.

Nicola Soranzo, Robert Andrews, Tim Beck, Alexia Cardona, Emily Delva, Catherine Knox, Gos Micklem, Christine Orengo, Krzysztof Poterlowicz, Susanna-Assunta Sansone, Neil Hall, Carole Goble, ELIXIR-UK (2023):  
[**BioFAIR: a new BioCommons infrastructure for the UK life science**](https://doi.org/10.7490/f1000research.1119446.1).  
_ELIXIR All Hands 2023_, Dublin, Ireland, 2023-06-05/--09.  
_F1000Research_ **12**(ELIXIR):596 (poster)  
<https://doi.org/10.7490/f1000research.1119446.1>

Nicola Soranzo, Carole Goble (2023):  
[**BioFAIR: a new BioCommons infrastructure for UK life science**](https://doi.org/10.5281/zenodo.7708304).  
_UKRI DRI Community Congress 2023_  
<https://doi.org/10.5281/zenodo.7708304>

Technopolis Group, Nicola Soranzo, Catherine Knox, Hannah Norman, Robert Andrews, Tim Beck, Gos Micklem, Christine Orengo, Susanna Assunta Sansone, Neil Hall, Carole Goble (2021):  
[**BioFAIR Final Report**](https://doi.org/10.5281/zenodo.7924339). BioFAIR Feasibility Study.  
_Zenodo_  
<https://doi.org/10.5281/zenodo.7924339>

---
layout: project
name: eurosciencegateway
title: EuroScienceGateway
path: eurosciencegateway.html
collection: projects
description: Improving computational workflows in Galaxy by maturing Pulsar Network and publishing computational workflows as FAIR Digital Objects.
logo: eurosciencegateway.svg
website: https://eurosciencegateway.eu/
start_date: 2022-09-01
expired: true
duration: 36 months
project_reference:
  - https://doi.org/10.3030/101057388
  - https://gtr.ukri.org/projects?ref=10038963
---

## Motivation

In the past decade, many scientific domains have been transformed into data-driven disciplines relying on the exchange and integration of internationally distributed data. Exploiting this data is still a laborious and largely manual task, prone to losses and errors, and increasingly specialised beyond most users technical capabilities. [FAIR practices](https://doi.org/10.1038/sdata.2016.18) are encouraged but their adoption curve is steep. The needs for compute and data resources, tools, and application platforms are often domain-specific. 

Many scientists struggle to navigate this intricate ecosystem. Generally, researchers do not possess the computing skills to effectively use the HPC or Cloud platforms they need. Thus, new approaches are needed to enable all researchers, with widely ranging digital skills, to efficiently use the diverse computational infrastructures available across Europe, for asynchronous and for interactive applications.

## EuroScienceGateway

**EuroScienceGateway**  leveraged a distributed computing network across 13 European countries, accessible via 6 national, user-friendly web portals, facilitating access to compute and storage infrastructures across Europe as well as to data, tools, workflows and services that can be customized to suit researchers' needs. 

EuroScienceGateway delivered a robust, scalable, seamlessly integrated open infrastructure for data-driven research, contributing an innovative and customizable service for EOSC that enables operational open and FAIR data and data processing, empowering European researchers to embrace the new digital age of science.

### EOSC integration

Workflows were integrated with the evolving EOSC infrastructure with an aim for the EOSC Interoperability Framework. Adoption, development and implementation of technologies to interoperate across services, will allow researchers to produce high-quality FAIR data, available to all in EOSC. Communities across disciplines -- Life Sciences, Climate and Biodiversity, Astrophysics, Materials science -- demonstrated the bridge from EOSC's technical services to scientific analysis.

Funded by Horizon Europe call [HORIZON-INFRA-2021-EOSC-01-04](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/opportunities/topic-details/horizon-infra-2021-eosc-01-04) (_Enabling an operational, open and FAIR EOSC ecosystem_), EuroScienceGateway worked closely with [EOSC](https://www.eosc.eu/), EOSC projects including [EOSC-Life](../eosclife/), as well as established e-Infrastructures and life science communities like [ELIXIR](../elixir/).

### Galaxy and Pulsar Network

EuroScienceGateway leveraged the [Galaxy platform](https://galaxyproject.eu/) (an open, web-based platform for data-intensive research), the [Pulsar
Network](https://pulsar-network.readthedocs.io) (a wide job execution system distributed to scale computing power over heterogeneous resources) and
FAIR workflow services pioneered in the [EOSC-Life](https://www.eosc-life.eu/) cluster ([WorkflowHub](https://workflowhub.eu/), [Workflow RO-Crate](https://w3id.org/workflowhub/workflow-ro-crate/) and metadata standards like [schema.org](https://schema.org/)). 

EuroScienceGateway lifted Pulsar from TRL-7 to TRL-9 by expanding the APIs, hardening deployments and adding support for different usage patterns, e.g. data localisation during job scheduling. 

[National Galaxy instances](https://galaxyproject.org/use/) across Europe and other workflow management systems were connected to submit jobs to this distributed compute network. Pulsar aimed to become a production-ready interface for European computing resources, including [EGI](https://www.egi.eu/) and [EuroHPC](https://eurohpc-ju.europa.eu/) as Pulsar providers.

### WP2: Stimulate FAIR and reusable research

* WP2 introduction slides: <https://doi.org/10.5281/zenodo.7152762>

The eScience Lab at The University of Manchester was leading the work package WP2 _Stimulate FAIR and reusable research_, contributing with our expertise on [FAIR Computational Workflows](https://workflows.community/groups/fair/).

This work package added sufficient measures to EuroScienceGateway to support FAIR practices for and by workflows. 

[FAIR Digital Objects](https://fairdo.org/) (FDOs), for exchanging, publishing, archiving and citing workflows and their companion data, provenance logs and associated resources, were realized as [RO-Crate](/products/researchobject/#research-object-crate-ro-crate)s using a [FAIR Signposting](https://signposting.org/fair/) approach.
 
The FDOs were published through Datacite to EOSC catalogues e.g. [OpenAIRE](https://www.openaire.eu/) and further communicated through outreach plans to increase uptake of the EuroScienceGateway in affiliated and newly targeted computational researcher communities. 

[WorkflowHub](../workflowhub/), a FAIR registry for workflows that is RO-Crate compliant, was lifted to TRL-9 status (from TRL-7) and made the registry of choice for all workflow system types and for all disciplines in EOSC. 

By collaborating with the project CSA INFRA-01-EOSC-01-05 (_Enabling discovery and interoperability of federated research objects across scientific communities_), both the WorkflowHub and Workflow Digital Objects will be further aligned with the PID and metadata schema frameworks.


#### WP2 Objectives

* O2.1 Bringing FAIR workflows into EOSC through the EuroScienceGateway
* O2.2 Support reusable and reproducible workflows
* O2.3 Establish FAIR Digital Objects as citable exchange format for workflows for all EOSC services
* O2.4 Establish FAIR Workflow Digital Objects as publishable scholarly objects

## eScienceLab contributions

UK partners in Horizon Europe projects were funded through [Innovate UK](https://www.ukri.org/councils/innovate-uk/) (#10038963) from the [UKRI Horizon Europe guarantee](https://www.ukri.org/apply-for-funding/apply-for-horizon-europe-guarantee-funding/).

* WP2: Stimulate FAIR and reusable research (lead: UNIMAN)
  - Task T2.1: Integration of EuroScienceGateway in EOSC (lead: UNIMAN)
  - Task T2.2: Reproducible and reusable FAIR Digital Objects  (lead: UNIMAN)
  - Task T2.3: Using and enriching workflow FDOs (lead: UNIMAN)
  - Task T2.4: FAIR workflows as scholarly objects in scientific publishing (lead: EPFL)
  - Deliverable D2.1 Reproducible FAIR Digital Objects for workflows (lead: UNIMAN)
  - Deliverable D2.2 Publishing workflow enriched FDOs to EOSC (lead: UNIMAN)
* WP3: Pulsar Network: Distributed heterogeneous compute (lead: CNR)
  - Task T3.4 Add TES support to WfExS (Workflow Execution Service) (lead: BSC)-


## Relevant Deliverables


Anika Erxleben, Sebastian Schaaf, Flora D'Anna, Björn Grüning, Frederik Coppens, Eva Alloza, José María2 Fernández González, Nick Juty (ed.) (2023):  
EuroScienceGateway D2.1 [**EuroScienceGateway Data Management Plan**](https://doi.org/10.5281/zenodo.10054551) (DMP; D1.1).  v2.0  
_Zenodo_  
<https://doi.org/10.5281/zenodo.10054551>

Stian Soiland-Reyes, Eli Chadwick, Finn Bacall, José M Fernández, Björn Grüning, Hakan Bayındır (2024):  
[EuroScienceGateway D2.1: **Reproducible FAIR Digital Objects for Workflows Creators**](https://doi.org/10.5281/zenodo.13225792).  
_Zenodo_  
<https://doi.org/10.5281/zenodo.13225792>

Stian Soiland-Reyes, Björn Grüning,  Paul De Geest (2025):  
[EuroScienceGateway MS3: **Initial EuroScienceGateway workflows registered**](https://doi.org/10.5281/zenodo.10728922).  
_Zenodo_  
<https://doi.org/10.5281/zenodo.10728922>

Stian Soiland-Reyes, Eli Chadwick, Armin Dadras, Björn Grüning, Catalin Condurache, Sebastian Luna-Valero, Volodymy Savchenko (2025):  
[EuroScienceGateway D2.2: **Publishing workflow enriched FDOs to EOSC**](https://doi.org/10.5281/zenodo.15094824).  
_Zenodo_  
<https://doi.org/10.5281/zenodo.15094824>


Eli Chadwick, Oliver Woolland, Volodymyr Savchenko, Finn Bacall, Alexander Hambley, José María Fernández, Armin Dadras, Stian Soiland-Reyes (2025):  
[EuroScienceGateway MS6: **Integrated EuroScienceGateway knowledge graph**](https://doi.org/10.5281/zenodo.16992674).  
_Zenodo_  
<https://doi.org/10.5281/zenodo.16992674>


## Relevant Publications


Eli Chadwick, Oliver Woolland, Alexander Hambley, Volodymyr Savchenko, and Stian Soiland-Reyes (2025):  
[**Workflowhub Knowledge Graph**](https://doi.org/10.5281/zenodo.16995374).   
_Zenodo_   
<https://doi.org/10.5281/zenodo.16995374>

Sean R. Wilkinson, Johan Gustafsson, Finn Bacall, Khalid Belhajjame, Salvador Capella, Jose Maria Fernandez Gonzalez, Jacob Fosso Tande, Luiz Gadelha, Daniel Garijo, Patricia Grubel, Bjorn Grüning, Farah Zaib Khan, Sehrish Kanwal, Simone Leo, Stuart Owen, Luca Pireddu, Line Pouchard, Laura Rodríguez-Navas, Beatriz Serrano-Solano, Stian Soiland-Reyes, Baiba Vilne, Alan Williams, Merridee Ann Wouters, Frederik Coppens, Carole Goble (2025):  
[**An Ecosystem of Services for FAIR Computational Workflows**](https://doi.org/10.48550/arXiv.2505.15988).  
Book chapter, draft  
_arXiv_ 2505.15988 [cs.DC]  
<https://doi.org/10.48550/arXiv.2505.15988>

Frédéric Suter, Tainã Coleman, İlkay Altintaş, Rosa M. Badia, Bartosz Balis, Kyle Chard, Iacopo Colonnelli, Ewa Deelman, Paolo Di Tommaso, Thomas Fahringer, Carole Goble, Shantenu Jha, Daniel S. Katz, Johannes Köster, Ulf Leser, Kshitij Mehta, Hilary Oliver, J.-Luc Peterson, Giovanni Pizzi, Loïc Pottier, Raül Sirvent, Eric Suchyta, Douglas Thain, Sean R. Wilkinson, Justin M. Wozniak, Rafael Ferreira da Silva (2025):  
[**A Terminology for Scientific Workflow Systems**](https://doi.org/10.1016/j.future.2025.107974).  
_Future Generation Computer Systems_ **174**:107974  
<https://doi.org/10.1016/j.future.2025.107974>

Ove Johan Ragnar Gustafsson, Sean R. Wilkinson, Finn Bacall, Stian Soiland-Reyes, Simone Leo, Luca Pireddu, Stuart Owen, Nick Juty, José Mª Fernández, Tom Brown, Hervé Ménager, Björn Grüning, Salvador Capella-Gutierrez, Frederik Coppens, Carole Goble (2025):  
[**WorkflowHub: a registry for computational workflows**](https://research.manchester.ac.uk/files/808300570/s41597-025-04786-3.pdf).  
_Scientific Data_ **12**:837  
<https://doi.org/10.1038/s41597-025-04786-3>

Stian Soiland-Reyes, Peter Sefton, Simone Leo, Leyla Jael Castro, Claus Weiland, Herbert Van de Sompel (2025):  
[**Practical webby FDOs with RO-Crate and FAIR Signposting**: Experiences and lessons learned](https://www.tib-op.org/ojs/index.php/ocp/article/view/1273/2568).  
_International FAIR Digital Objects Implementation Summit 2024_, Berlin, Germany, 2024-03-20/--21.  
_Open Conference Proceedings_ **5**  
<https://doi.org/10.52825/ocp.v5i.1273>


Sean Wilkinson, Meznah Aloqalaa, Khalid Belhajjame, Michael R. Crusoe, Bruno de Paula Kinoshita, Luiz Gadelha, Daniel Garijo, Ove Johan Ragnar Gustafsson, Nick Juty, Sehrish Kanwal, Farah Zaib Khan, Johannes Köster, Karsten Peters-von Gehlen, Line Pouchard, Randy K. Rannow, Stian Soiland-Reyes, Nicola Soranzo, Shoaib Sufi, Ziheng Sun, Baiba Vilne, Merridee A. Wouters, Denis Yuen, Carole Goble (2025):  
[**Applying the FAIR Principles to Computational Workflows**](https://doi.org/10.1038/s41597-025-04451-9).  
_Scientific Data_ **12**:328  
<https://doi.org/10.1038/s41597-025-04451-9>

Alexander Hambley, Eli Chadwick, Oliver Woolland, Stian Soiland-Reyes, Volodymyr Savchenko (2024):  
[**WorkflowHub Knowledge Graph**](https://doi.org/10.5281/zenodo.13362051).  (Dataset)  
_Zenodo_  
<https://doi.org/10.5281/zenodo.13362051>


Eli Chadwick, Stian Soiland-Reyes, José María Fernández, Björn Grüning, Carole Goble (2025):  
[**RO-Crate – Capturing FAIR research outputs throughout the ELIXIR landscape**](https://doi.org/10.7490/f1000research.1120199.1).  
ELIXIR All Hands Meeting ([AHM2025](https://elixir-europe.org/events/elixir-all-hands-2025)), Thessaloniki, Greece,  2025-06-02/--05.  
_F1000Research_ **14**(ELIXIR):543 (poster)  
<https://doi.org/10.7490/f1000research.1120199.1>


Paula Iborra, José M. Fernández, Laia Codó, Eugenio Gonzalo, Stian Soiland-Reyes, Alexander Hambley, Jonathan Couldridge, Carole Goble, Philip Quinlan, Salvador Capella-Gutierrez (2025):  
[**ENTRUSTing WfExS 1.0 with WES and TES**](https://doi.org/10.7490/f1000research.1120178.1).  
ELIXIR All Hands Meeting ([AHM2025](https://elixir-europe.org/events/elixir-all-hands-2025)), Thessaloniki, Greece,  2025-06-02/--05.  
_F1000Research_ **14**(ELIXIR):518 (poster)  
<https://doi.org/10.7490/f1000research.1120178.1>


Finn Bacall, Stian Soiland-Reyes, Carole Goble, Stuart Owen, Johan Gustafsson, Frederik Coppens (2024):  
[**WorkflowHub**](https://doi.org/10.7490/f1000research.1119852.1).  
ELIXIR All Hands Meeting ([AHM2024](https://elixir-europe.org/events/elixir-all-hands-2024)), Uppsala, Sweden, 2024-06-10/--12.    
_F1000Research_ **13**(ELIXIR):1027 (poster)  
<https://doi.org/10.7490/f1000research.1119852.1>

Eli Chadwick, Stian Soiland-Reyes (2024):  
[**RO-Crate: package your research outputs with their metadata**](https://research.manchester.ac.uk/en/publications/ro-crate-package-your-research-outputs-with-their-metadata).  
_Research Software Engineering Conference_ ([RSECon 2024](https://rsecon24.society-rse.org/)), Newcastle, UK, 2024-09-03/--05.  
<https://research.manchester.ac.uk/en/publications/ro-crate-package-your-research-outputs-with-their-metadata>


Carole Goble, Finn Bacall, Stian Soiland-Reyes, Stuart Owen, Ignacio Eguinoa, Bert Droesbeke, Hervé Ménager, Laura Rodriguez-Navas, José M. Fernández, Salvador Capella-Gutierrez, Michael R. Crusoe, Björn Grüning, Simone Leo, Luca Pireddu, Marco Enrico Piras, Johan Gustafsson, Phil Ewels, WorkflowHub Community, Frederik Coppens (2023):  
[**WorkflowHub – a FAIR registry for workflows**](https://doi.org/10.7490/f1000research.1119430.1).  
ELIXIR All Hands Meeting ([AHM2023](https://elixir-europe.org/events/elixir-all-hands-2023)), Dublin, Ireland, 2023-06-05/--08.  
<https://doi.org/10.7490/f1000research.1119430.1>


Simone Leo, Laura Rodríguez-Navas, José M. Fernández, Paul De Geest, Luca Pireddu, Michael R. Crusoe, Daniel Garijo, Iacopo Colonnelli, Raül Sirvent, Stian Soiland-Reyes (2023):  
[**Making workflow provenance FAIR across workflow systems with Workflow Run RO-Crate**](https://doi.org/10.5281/zenodo.8004793).  
_Elixir All Hands 2023_, 2023-06-06, Dublin, Ireland.  
_F1000Research_  **12**(ELIXIR):592 (poster)  
<https://doi.org/10.7490/f1000research.1119445.1>


Simone Leo, Michael R. Crusoe, Laura Rodríguez-Navas, Raül Sirvent, Alexander Kanitz, Paul De Geest, Rudolf Wittner, Luca Pireddu, Daniel Garijo, José M. Fernández, Iacopo Colonnelli, Matej Gallo, Tazro Ohta, Hirotaka Suetake, Salvador Capella-Gutierrez, Renske de Wit, Bruno de Paula Kinoshita, Stian Soiland-Reyes (2024):  
[**Recording provenance of workflow runs with RO-Crate**](https://doi.org/10.1371/journal.pone.0309210).  
_PLOS One_ **19**(9):e0309210  
<https://doi.org/10.1371/journal.pone.0309210>

Stian Soiland-Reyes, Carole Goble, Paul Groth (2024):  
[**Evaluating FAIR Digital Object and Linked Data as distributed object systems**](https://s11.no/2023/phd/evaluating-fdo/).  
_PeerJ Computer Science_  **10**:e1781  
<https://doi.org/10.7717/peerj-cs.1781>
[[RO-Crate](https://w3id.org/ro/doi/10.5281/zenodo.8075229)]

Stian Soiland-Reyes, Leyla Jael Castro, Rohitha Ravinder, Claus Weiland, Jonas Grieb, Alexander Rogers, Christophe Blanchi, Herbert Van de Sompel (2024):  
[BioHackEU23 report: **Enabling FAIR Digital Objects with RO-Crate, Signposting and Bioschemas**](https://s11.no/2024/enabling-fair-digital-objects/).  
*BioHackrXiv*  
<https://doi.org/10.37044/osf.io/gmk2h>

José M. Fernández, Paula Iborra, Sébastien Moretti, Arun Isaac, Paul De Geest, Stian Soiland-Reyes (2024):
[**BioHackEU23: FAIR Workflow Execution with WfExS and Workflow Run Crate**](https://doi.org/10.37044/osf.io/7f94w).  
_BioHackrXiv_
<https://doi.org/10.37044/osf.io/7f94w>

 
Ignacio Eguinoa, Marek Suchánek, Vojtěch Knaisl, Jan Slifka, Paul De Geest, David López, Bjorn Gruning, Simone Leo, Stian Soiland-Reyes (2023):  
[**BioHackEU22 Report: Enhancing Research Data Management in Galaxy and Data Stewardship Wizard by utilising RO-Crates**](https://s11.no/2023/phd/enhancing-rdm-galaxy-dsw/).  
_BioHackrXiv_  
<https://doi.org/10.37044/osf.io/24jst>
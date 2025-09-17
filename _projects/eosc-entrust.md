---
layout: project
name: eosc-entrust
title: "EOSC-ENTRUST"
path: eosc-entrust.html
collection: projects
description: A European Network of TRUSTed research environments
#logo: eosc-entrust.svg
website: http://eosc-entrust.eu/
start_date: 2024-03
duration: 36 months
project_reference: https://doi.org/10.3030/101131056
---

_Trusted environments for sensitive data management in EOSC_

<!-- copied from proposal, rewrite: -->

[EOSC-ENTRUST](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/how-to-participate/org-details/999999999/project/101131056/program/43108390/details) is an Horizon Europe project funded by [HORIZON-INFRA-2023-EOSC-01-06](https://ec.europa.eu/info/funding-tenders/opportunities/portal/screen/opportunities/topic-details/horizon-infra-2023-eosc-01-06) grant 101131056 (_Trusted environments for sensitive data management in EOSC_) and lead by [ELIXIR](https://elixir-europe.org/) Hub at [EMBL-EBI](https://www.ebi.ac.uk/).


The mission of EOSC-ENTRUST is to create a European network of trusted research environments for sensitive data and to drive European interoperability by joint development of a common blueprint for federated data access and analysis.

Countries and institutions have made significant investments in secure and trusted data environments to meet the need for research and policy-driven analysis of sensitive datasets such as people's health and socio-economic status, the habitats of vulnerable species and geo-spatial locations of protected sites. 
There are now a large number of such secure environments in operation -- linked to national centres, individual organisations or specific research communities. 
This fragmented landscape poses challenges for both users and providers: researchers are faced with a large number of different systems and access procedures; providers need to manage federated access across multiple, potentially incompatible, technology and governance frameworks.

EOSC-ENTRUST brings together providers of operational _Trusted Research Environments_ (TREs) from 15 European countries with a shared goal to implement, validate and promote their capabilities through a common European framework using shared standards and common legal, operational and technical language. 
This blueprint for interoperability is anchored in the [EOSC Interoperability Framework](https://doi.org/10.2777/620649) spanning the four dimensions of Legal, Organisational, Technical and Semantic interoperability. 

EOSC-ENTRUST has identified four driver projects covering Genomics, Clinical trials, Social science, and public-private partnerships to benchmark capabilities, inform blueprint design and demonstrate secure data analysis using federated workflows:

* [Genome Data Infrastructure](https://gdi.onemilliongenomes.eu/) (GDI) & [Federated EGA](https://web2.ega-archive.org/federated) (FEGA) -- Federated Human Genomics as a catalyst for European TRE provision
* [Consortium of European Social Science Data Archives](https://www.cessda.eu/) (CESSDA) & [The International Secure Data Facility Professionals Network](https://ukdataservice.ac.uk/about/research-and-development/international-secure-data-facility-professionals-network-isdfpn/) (ISDFPN) -- Common standards to enable trans-national sharing of administrative/register and social science
data
* [European Clinical Research Infrastructure Network](https://ecrin.org/) (ECRIN) & University of Oslo -- Enabling secure transnational re-use of clinical research data in a legally and ethically compliant
manner
* Public-Private interactions between TRE in health and environmental data

Targeted outreach activities will expand this open network with further providers and develop policy papers and guidelines for the full range of stakeholders to create a long-term operational TRE framework within the [European Open Science Cloud](https://eosc.eu/).


## Objectives

1. Create a European network of Trusted Research Environments, linked to EOSC and EuroHPC, to enable transnational collaborative research on sensitive or restricted data.

2. Trusted Research Environment providers implement, validate, and promote their capabilities through a European framework using common standards and shared legal, operational and technical language.

3. National funders and governments understand the network of TRE capabilities serving their needs, and how TREs support their national priorities and their contributions to selected transnational programmes.

4. The European Network of Trusted Research Environments (ENTRUST) is embedded in the European Open Science Cloud and the European Data Spaces and fosters an ecosystem of public, private and joint-venture providers of TRE services.


### eScienceLab involvement

For the eScience Lab this project builds on our earlier work on [TRE-FX](../tre-fx/) and will align with our work on HDR UK Federated Analytics. In EOSC-ENTRUST we will particularly working with contribute with our expertise on [RO-Crate](products/researchobject/) and the [Five Safes RO-Crate](https://w3id.org/5s-crate/) profile.

UNIMAN contributions :

* WP7A: RO-Crate and workflow processing - Establishing a common terminology and approach  (leads: BSC, UNOTT)
  - Task 7A.1: Use-cases for the deployment of Five Safes RO-Crate
  - Task 7A.2: Workflow engine processing a Five Safes RO-Crate
  - Deliverable D7A.1: Deployable Demonstrator of Digital Objects & Workflows Developments
* WP7B: RO-Crate and workflow processing - Deployment  (leads: BSC, UNOTT)
  - Task 7B.1: Verifiable Five Safes RO-Crate.
  - Task 7B.2: Handling data security and data curation with workflow orchestrator.
  - Deliverable 7B.1: Deployable Demonstrator of Digital Objects & Workflows Developments, Second Version
* WP7C: RO-Crate and workflow processing - Demonstrating Impact  (leads: BSC, UNOTT)
  - Task 7C.1: Wrapping federated analytics within a Five Safes RO-Create
  - Task 7C.2: Developing a technical blueprint for federated analytics implementation
  - Deliverable 7C.1: Deployable Demonstrator of Digital Objects & Workflows Developments, Final Version

## Relevant publications


Stian Soiland-Reyes, Stuart Wheater, Thomas Giles, Jonathan Couldridge, Phil Quinlan, Carole Goble (2025):  
[**Five Safes RO-Crate: FAIR Digital Objects for Trusted Research Environments**](https://doi.org/10.52825/ocp.v5i.1419).  
_International FAIR Digital Objects Implementation Summit 2024_, Berlin, Germany, 2024-03-20/--21.  
_Open Conference Proceedings_ **5**  
<https://doi.org/10.52825/ocp.v5i.1419>


Eugenio Gonzalo, Laia Codó, Jose María Fernandez, Stian Soiland-Reyes, Salvador Capella-Gutierrez, Emily Jefferson, Carole Goble, Tim Beck, Phil Quinlan, Tom Giles (2024):  
[**Five safes workflow RO-Crate and WfExS**. Closing the gap of federated analysis and Trusted Research Enviroments (TREs) in the health data context](https://doi.org/10.7490/f1000research.1119724.1).  
ELIXIR All Hands Meeting ([AHM2024](https://elixir-europe.org/events/elixir-all-hands-2024)), Uppsala, Sweden, 2024-06-10/--12.    
_F1000Research_ **13**(ELIXIR):550 (poster)  
<https://doi.org/10.7490/f1000research.1119724.1>

Paula Iborra, José M. Fernández, Laia Codó, Eugenio Gonzalo, Stian Soiland-Reyes, Alexander Hambley, Jonathan Couldridge, Carole Goble, Philip Quinlan, Salvador Capella-Gutierrez (2025):  
[**ENTRUSTing WfExS 1.0 with WES and TES**](https://doi.org/10.7490/f1000research.1120178.1).  
ELIXIR All Hands Meeting ([AHM2025](https://elixir-europe.org/events/elixir-all-hands-2025)), Thessaloniki, Greece,  2025-06-02/--05.  
_F1000Research_ **14**(ELIXIR):518 (poster)  
<https://doi.org/10.7490/f1000research.1120178.1>

Philip Quinlan, Laia Codó, Jonathan Couldridge,  Eugenio Gonzalo Jimenez, Stian Soiland-Reyes, José María Fernández González, Tim Beck (2024):  
[EOSC-ENTRUST D19.1 **Deployable Demonstrator of Digital Objects & Workflows Developments**](https://doi.org/10.5281/zenodo.14412863).  
_Zenodo_  
<https://doi.org/10.5281/zenodo.14412863>




---
layout: project
name: federated-analytics
title: HDR-UK Federated Analytics
path: federated-analytics.html
collection: projects
description: Federated analytics with FAIR health data in Trusted Research Environments
logo: federated-analytics.png
website: https://federated-analytics.ac.uk/
start_date: 2023-04-01
#expired: true
duration: 5 years
project_reference: https://gtr.ukri.org/projects?ref=HDR-CORE
---

HDR-UK Federated Analytics is a research collaboration within HDR UK's Infrastructure and Services programme, funded by the second [quinquennial review](https://www.hdruk.org/quinquennial-review/) period (HDR QQ2).

[Health Data Research UK](https://www.hdruk.ac.uk) (HDR UK) is a national institute dedicated to improving health outcomes and advancing medical research through the use of data. Established in 2018, HDR UK is a partnership between leading universities, research institutions, and the National Health Service (NHS) in the UK. The primary mission of HDR UK is to harness the power of health data to drive scientific discoveries, develop innovative treatments and interventions, and ultimately improve patient care. By integrating and analysing vast amounts of health data, including electronic health records, genomic data, and other relevant information, HDR UK aims to generate insights that can transform healthcare delivery, policy, and research.

The University of Manchester, the University of Nottingham, Swansea University and the University of Dundee have established a collaborative network to explore innovative ways to use health data for research and healthcare improvement. These initiatives involve developing new analytical techniques, data linkage methods, and tools for data sharing while ensuring patient privacy and data security. 


## eScience Lab involvement

Professor Carole Goble from The University of Manchester co-leads the HDR Federated Analytics Infrastructure Programme together with Phil Quinlan from University of Nottingham.

At The University of Manchester, we want to better understand the challenges of computational reproducibility and FAIR data sharing within HDR UK federated data infrastructures, especially focussing on technology potential, limitations, integrity measures and handling of sensitive data.

We are building on the outputs from the [TRE-FX](../tre-fx/) project including the [Five Safes RO-Crate](https://w3id.org/5s-crate/) profile. A [PhD studentship](/hdr/phd/2023/07/18/hdr-uk-phd-studentship/) was granted. 

We have developed the [RO-Crate Validation Service](https://github.com/eScienceLab/Cratey-Validator) which presents an API based on the [CRS4 RO-Crate validator](https://github.com/crs4/rocrate-validator/). This microservice can be used separately or in conjuction with the other [federated analytics services](https://docs.federated-analytics.ac.uk).

We're leading WP3 on FAIR and Transparency. 

Our key objective is to improve transparency around the technical engineering and governance of federated analytics to make it easier for developers from other disciplines to get involved. 
Integrating FAIR data capabilities into the technical framework and architecture supports the governance requirements of Trusted Research Environments (TREs). We propose to use Research Objects, packaged as RO-Crates, to organise and describe the inputs, methods and outputs of an analysis. By cataloguing this information, a TRE provider has a record of the data provenance, context and understanding of how to reproduce a particular analysis of a particular dataset.

- Objective 1: Observe, collect and review FAIR practices (data, tools, services, infrastructure) present in the key use cases within the Trusted Research Environment (TRE) ecosystem.
- Objective 2: Practical FAIR for work to be implemented or adopted
- Objective 3: Co-create RO-Crate profiles to facilitate interoperability: overarching RO-Crate profiles that accommodate community-specific solutions
- Objective 4: Document and Disseminate the Framework for FAIR and RO-Crate usage 


## References and related outputs

Kay Snowley, Lara Edwards, Ben Crosby, Helen Tatlow (2023):  
[**Integrating Our Community**. Year 1](https://www.hdruk.ac.uk/wp-content/uploads/2023/10/Integrating-Our-Community_v1-Oct-2023-compressed.pdf)  
_Health Data Research UK_ (report) 
<https://www.hdruk.ac.uk/wp-content/uploads/2023/10/Integrating-Our-Community_v1-Oct-2023-compressed.pdf>

Chris Orton, Lara Edwards, David Seymour, Monica Jones, Philip Quinlan, Simon Thompson, Carole Goble, Jennifer Quint, Aziz Sheikh (2024):  
[**Data as infrastructure**: Systematic data curation addressing fundamental data content differences across the UK](https://doi.org/10.23889/ijpds.v9i5.2683).  
_Conference Proceedings for International Population Data Linkage Conference 2024_, Chicago, USA, 2024-09-15/--18.  
_International Journal of Population Data Science_ **9**(5)  
<https://doi.org/10.23889/ijpds.v9i5.2683>

Stian Soiland-Reyes, Stuart Wheater, Thomas Giles, Jonathan Couldridge, Phil Quinlan, Carole Goble (2025):  
[**Five Safes RO-Crate**: FAIR Digital Objects for Trusted Research Environments](https://doi.org/10.52825/ocp.v5i.1419).  
_International FAIR Digital Objects Implementation Summit 2024_ ([FDO2024](https://fairdo.org/fdof-summit-2024/)), Berlin, Germany, 2024-03-20/--21.  
_Open Conference Proceedings_ **5**  
<https://doi.org/10.52825/ocp.v5i.1419>

Michelle Amugi, Rob Baxter, Christian Cole, Carole Goble, Emily Jefferson, Fergus McDonald, Andrew Morris, Philip Quinlan, David Seymour, Jim Smith, Balint Stewart, Simon G. Thompson (2025):  
[**A Federated Architecture for a National Data Library**](https://doi.org/10.5281/zenodo.14672004).  
_Wellcome Trust_ (report) / DARE UK  
<https://doi.org/10.5281/zenodo.14672004>

See the [documentation for federated analytics](https://docs.federated-analytics.ac.uk/) for further developer-centric information, and the [federated-research GitHub organisation](https://github.com/federated-research) for source code.


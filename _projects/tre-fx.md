---
layout: project
name: tre-fx
title: TRE-FX
path: tre-fx.html
redirect_from: /projects/tre-fx/
collection: projects
description: Delivering a federated network of TREs to enable safe analytics
logo: tre-fx-logo.svg
website: https://trefx.uk/
start_date: 2023-02-01
end_date: 2023-10-31
expired: true
duration: 9 months
project_reference: https://gtr.ukri.org/projects?ref=MC_PC_23007
---

[TRE-FX](https://trefx.uk/) was a project [funded](https://dareuk.org.uk/five-projects-funded-to-drive-more-coordinated-secure-use-of-sensitive-data-for-research-across-uk/) by UK Research and Innovation ([UKRI](https://www.ukri.org/)) as part of the [DARE UK](https://dareuk.org.uk/) _Data and Analytics Research Environments UK_ programme ([MC_PC_23007](https://gtr.ukri.org/projects?ref=MC_PC_23007)).

## Motivation

Trusted research environments (TREs) are secure digital locations in which data are placed for researchers to analyse. They host administrative data, hospital data or any other data that must be securely held and only accessible for approved projects by approved researchers.

However, it is hard for a researcher to perform analysis across multiple TREs – for example when data is to be analysed across geographical or governance boundaries, such as devolved healthcare data from across different nations of the UK. Yet this ability is urgently needed. Analysis across a federation of TREs would enable timely analysis of data scattered across the UK to answer urgent questions, as we needed in the COVID-19 pandemic.

The project built a demonstration of how we can use secure research objects to move between TREs while still supporting the Five Safes principles that govern and protect sensitive data – all overseen by public representatives. [Research Objects](activities/researchobject/) are a standardised way of describing and packaging the digital information needed (but not the data itself) to pose a research question and report the answer.


## Approach

[**TRE-FX**](https://trefx.uk/) assembled leading technology providers from
[ELIXIR-UK](https://elixiruknode.org/) and [HDR UK](https://www.hdruk.ac.uk/), 
with three TRE providers and two leading analysis platforms
to show through a real reference implementation how we can use secure Research
Objects to move between TREs while still supporting the [Five Safes principles](https://ukdataservice.ac.uk/help/secure-lab/what-is-the-five-safes-framework/) that govern and protect patient data; all overseen by patient representatives.

This is potentially a step change for how researchers can safely combine data from many sources, and for how data providers from any sector can safely implement this using technology and standards we already have today.

* Principal investigator: Professor Carole Goble, University of Manchester

* Project partners: University of Manchester, University of Nottingham, University of Dundee, University of Swansea, University of Birmingham, Health Data Research UK (HDR UK), University of Liverpool, Bitfount, Birmingham University Hospitals NHS Trust 

## eScience Lab involvement

eScience Lab led this project on behalf of [ELIXIR-UK](https://elixiruknode.org/), and mainly contributed to:

* WP1: PPIE  (lead: University of Nottingham / PIONEER)
  - Promote the inclusion of under-represented groups (as required)
  - Plan PPIE engagement events for external audiences 
  - Provide bespoke support to peoples (as required)
  - Promote public engagement work across TRE-FX
  - Host PPIE engagement events for external audiences 
  - Deliver a PPIE video discussing the implementation
* WP2: Transparency (lead: ELIXIR-UK)
  - Develop a Five Safes RO-Crate 
  - Plan workshop to explore Five Safes RO-Crate  requirements with all Stakeholders
  - Develop a whitepaper based on the Five Safes RO-Crate 
  - Review the current mechanisms of accessing the HDR Data Use Register 
  - Develop HDR data use register to accept Five Safes RO-Crates 
  - Deliver a workshop on RO-Crate profile requirements with external Stakeholders
  - Deliver the whitepaper based on the Five Safes RO-Crate 
  - Deliver HDR data use register for Five Safes RO-Crate API integration 
* WP3: Microservice Development (lead: University of Nottingham)
  - Development of Controlled layer APIs and microservices 
  - Development of TRE polling layer  APIs and microservices
  - Development of Submission layer APIs and microservices
  - Continued development and bug fixing
  - Deliver working version of polling and controlled layer APIs and microservices 
  - Deliver working version of submission layer APIs and microservices
* WP5: Federated Analytics Testing
  - Development and testing of federated analytic workflows 
  - Testing on queries on reference implementation across TREs
  - Basic user authentication and disclosure control testing
  - Publish DataSHIELD and Bitfount WfExS open-source workflow to workflowhub.eu
  - Federated analytic workflows validated on TREs


## Outputs


Thomas Giles, Stian Soiland-Reyes, Jonathan Couldridge, Stuart Wheater, Blaise Thomson, Jillian Beggs, Suzy Gallier, Sam Cox, Daniel Lea, Justin Biddle, Rima Doal, Naaman Tammuz, Becca Wilson, Christian Cole, Elizabeth Sapey, Simon Thompson, Professor Emily Jefferson, Phillip Quinlan, Carole Goble (2023):  
[**TRE-FX: Delivering a federated network of trusted research environments to enable safe data analytics**](https://doi.org/10.5281/zenodo.10055354).  
_Zenodo_ / DARE UK  
<https://doi.org/10.5281/zenodo.10055354>

Stian Soiland-Reyes, Stuart Wheater (2023):  
[**Five Safes RO-Crate profile**](https://w3id.org/5s-crate/0.4), version 0.4.  
_TRE-FX Candidate Recommendation_  
<https://w3id.org/5s-crate/0.4>

Carole Goble, Phil Quinlan, Tom Giles (2023):
[**TRE-FX: Core federation services for a federated network of TREs to enable Five Safes analytics**](https://doi.org/10.5281/zenodo.7708175)
_DARE-UK launch_, 2023-03-08.  
<https://doi.org/10.5281/zenodo.7708175>

Simone Leo, Laura Rodríguez-Navas, José M. Fernández, Paul De Geest, Luca Pireddu, Michael R. Crusoe, Daniel Garijo, Iacopo Colonnelli, Raül Sirvent, Stian Soiland-Reyes (2023):  
[**Making workflow provenance FAIR across workflow systems with Workflow Run RO-Crate**](https://doi.org/10.5281/zenodo.8004793).  
_Elixir All Hands 2023_, 2023-06-06, Dublin, Ireland.  
_F1000Research_  **12**(ELIXIR):592 (poster)  
<https://doi.org/10.7490/f1000research.1119445.1>

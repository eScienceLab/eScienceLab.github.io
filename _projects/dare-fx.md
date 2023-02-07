---
layout: project
name: dare-fx
title: DARE-FX
path: dare-fx.html
collection: projects
description: Delivering a federated network of TREs to enable safe analytics
logo: dare-fx.svg
website: https://darefx.uk/
start_date: 2023-02-01
duration: 9 months
project_reference: 
---

[DARE-FX](https://darefx.uk/) is a project funded by [UKRI](https://www.ukri.org/) Medical Research Council [MRC](https://www.ukri.org/councils/mrc/) and [DARE UK](https://dareuk.org.uk/) for the call [“Inform design of cross-council trusted research environments”](https://www.ukri.org/opportunity/inform-design-of-cross-council-trusted-research-environments/).

## Motivation

Trusted Research Environments (TREs) are secure locations in which data are placed
for researchers to analyse. They host administrative data, hospital data or any other
data that must be securely isolated and only accessible for approved queries by
approved researchers. 

However, _it is hard for a researcher to perform analysis across
multiple TREs_, for example when data is to be analysed across geographical or
governance boundaries, such as the devolved nature of healthcare in the United
Kingdom. _Yet this ability is urgently needed_. 

Analysis across a federation of TREs
would enable timely analysis of UK wide scattered data to answer urgent questions,
as we needed in the COVID-19 pandemic. The technologies and standards we need to be able to do this are available now. They
do not need to be invented. 

[**DARE-FX**](https://darefx.uk) is assembling leading technology providers from
[ELIXIR-UK](https://elixiruknode.org/) and [HDR-UK](https://www.hdruk.ac.uk/), 
with three TRE providers and two leading analysis platforms
to show through a real reference implementation how we can use secure Research
Objects to move between TREs while still supporting the [Five Safes principles](https://ukdataservice.ac.uk/help/secure-lab/what-is-the-five-safes-framework/) that
govern and protect patient data; all overseen by patient representatives.

The impact will be a step change for how researchers can safely combine data from
many sources, and for how data providers from any sector can safely implement this
using technology and standards we already have today.

## eScience Lab involvement

eScience Lab is leading this project on behalf of [ELIXIR-UK](https://elixiruknode.org/), and is mainly contributing to:

* WP1: PPIE  (lead: University of Nottingham / PIONEER)
  - Promote the inclusion of under-represented groups (as required)
  - Plan PPIE engagement events for external audiences 
  - Provide bespoke support to peoples (as required)
  - Promote public engagement work across DARE-FX
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

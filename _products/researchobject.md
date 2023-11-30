---
layout: product
name: research_object
title: Research Objects Crate (RO-Crate)
path: research_object
collection: products
description: Research publications, data, code and more bundled into a shareable, cite-able, reusable format
website: http://www.researchobject.org/
logo: /images/logo/ro-crate.svg
screenshot: /images/screenshots/sm_researchobject.png
#wiki: https://wikipedia.org/wiki/Research_Objects
---

_Research Object_ is an approach to the publication, and exchange of scholarly information on the Web.

Research Objects aim to improve reuse and reproducibility by:

* Supporting the publication of **more than just PDFs**, making **data**, **code**, and other resources **first class citizens of scholarship**
* Recognizing that there is often a need to publish collections of these resources together as one shareable, cite-able resource.
* **Enriching** these resources and collections with any and all additional information required to make research reusable, and reproducible!

## Research Object Crate (RO-Crate)

[RO-Crate](https://w3id.org/ro/crate) is the recommended way to package and describe Research Objects. This is a community effort to establish a lightweight approach to packaging research data with their metadata. RO-Crate is based on [schema.org](https://schema.org/) annotations in JSON-LD, and aims to make best-practice in formal metadata description accessible and practical for use in a wider variety of situations, from an individual researcher working with a folder of data, to large data-intensive computational research environments.

RO-Crate is used in several of our projects and products:

* [BioDT](/projects/biodt/) -- as a mechanism to publish [FAIR Computational Workflows](https://workflows.community/groups/fair/) as FAIR Digital Objects and for representing [digital twins](https://github.com/BioDT/biodt-fair)
* [BioExcel](/projects/bioexcel/) -- As a way to capture Canonical Workflow Building Blocks <https://doi.org/10.1162/dint_a_00135>
* [BY-COVID](/projects/by-covid/) -- As a way to package rich metadata and provenance (e.g. describe a [vaccine effectiveness study](https://w3id.org/ro/doi/10.5281/zenodo.6913045)) together with the [common provenance model](https://w3id.org/cpm/ro-crate/0.2) <https://doi.org/10.5281/zenodo.5093125>
* [ELIXIR](/projects/elixir/) -- As part of GA4GH cloud activities
* [WorkflowHub](/products/workflowhub) -- as storage format for workflows and their dependencies, using the [Workflow RO-Crate profile](https://w3id.org/workflowhub/workflow-ro-crate/) 
* [EOSC-Life](/projects/eosc-life/) -- as exchange unit with services like [LifeMonitor](https://lifemonitor.eu/) using the [Workflow Testing Crate](https://lifemonitor.eu/workflow_testing_ro_crate) profile <https://doi.org/10.5281/zenodo.4605654>
* [FAIR-IMPACT](/projects/fair-impact/) -- to help package semantic artefacts and their crosswalk mappings, published with [FAIR Signposting](https://signposting.org/FAIR/). 
* [SEEK](/products/seek/) -- being developed as an update to the previous Research Object Bundle export
* [Synthesys+](/projects/synthesys/) -- recording workflow outputs from Galaxy as a [Workflow Run Crate](https://www.researchobject.org/workflow-run-crate/) profile and working with FAIR Digital Objects <https://doi.org/10.1162/dint_a_00134>
* [EuroScienceGateway](/projects/eurosciencegateway) -- adding [Workflow Run Crate](https://www.researchobject.org/workflow-run-crate/) support to Galaxy and publishing these as FAIR Digital Objects
* [TRE-FX](/projects/trefx) and HDR UK QQ2 -- to build the [Five Safe RO-Crate](https://w3id.org/5s-crate/) profile for execution workflows on Trusted Research Environment
* [EVERSE](/projects/everse) -- as the exchange mechanism for the workflow execution service [WfExS](https://github.com/inab/WfExS-backend)
* [EOSC-ENRTUST](/projects/entrust) -- using the [Five Safe RO-Crate](https://w3id.org/5s-crate/) profile as part of workflow processing

---
layout: project
name: IBISBA
title: IBISBA 1.0
path: ibisba.html
collection: projects
description: Industrial Biotechnology Innovation and Synthetic Biology Accelerator
logo: Ibisba.png
website: http://www.ibisba.eu/
#project_reference: TODO
start_date: 2017-12-01
end_date: 2021-11-30
duration: 4 years
---

The _Industrial Biotechnology Innovation and Synthetic Biology Accelerator_ ([IBISBA 1.0](http://www.ibisba.com/)) is funded as part of [H2020 INFRAIA-02](https://ec.europa.eu/research/participants/portal/desktop/en/opportunities/h2020/topics/infraia-02-2017.html).

The overarching aim of IBISBA 1.0 is to support and accelerate the uptake of **industrial biotechnology** as a key enabling technology for advanced manufacturing. 

To do this, IBISBA 1.0 will provide a _distributed network_ of **research infrastructure facilities** to promote R&D in _bioprocess development_ and support this bioeconomy KET. The facilities cover a variety of experimental and in silico operations and disciplines, and together represent the R&D needed to build quality biomanufacturing processes for industrialization. 

In addition to hardware, IBISBA 1.0 will operate an **ICT platform**, linking all project events occurring on facilities, and external _data repositories_, and provide users with end-to-end _project management_ and access to a wide variety of research assets. 

Together, these developments create the basis for a future pan-European research infrastructure for industrial biotechnology, the feasibility of which will be established during the project. 

Through IBISBA 1.0, the participant facilities will be opened for transnational access, thus providing cutting edge technologies to a cross section of Europe’s researchers, including early career stage scientists. Users and facility operators will receive remote and on-site _training_, and immersion in the hallmark multidisciplinary environment of IBISBA 1.0. 

Transnational access will be facilitated by an ambition _outreach plan_ that will provide users, including SMEs and other industry players, with complete information about service offers, but also insight into the potentiality of IPR held by IBISBA 1.0 partners and the opportunities for innovation. 

**Interoperability** will be a focus of considerable attention, with actions directed towards harmonization and the implementation of repeatable working practices that integrate experimentation with data analysis, and data management, thus providing the basis for the sharing and reuse of data assets in a framework of Open Science.


## eScience Lab contributions

The eScience Lab is partnered with the Manchester Synthetic Biology Centre ([SynBioChem](/projects/synbiochem)), both of which contribute effort to the IBISBA project.

The eScience Lab will contribute mainly in Work Package 7 (_Meeting the e-needs of a distributed infrastructure for industrial biotechnology_), focusing on computational workflows and data management, but also experimenting with business workflows.

IBISBA want to leverage state-of-the-art workflow systems. Working with our partners at [INRA](http://www.inra.fr/) (Institut national de la recherche agronomique) and [KNIME.com GmbH](https://www.knime.com/about) we will encapsulate the many computational tools in biotechnology as _workflow nodes_ for use in existing workflow systems using the [KNIME Analytical Platform](https://www.knime.com/knime-analytics-platform). 

We will produce a **library of workflows** using these nodes that will be described
in [Common Workflow Language](http://www.commonwl.org/), marked up with rich metadata using and extending the [EDAM ontology](http://edamontology.org/).

Workflows will be stored along with associated datafiles and models in an IBISBA installation of a customised [SEEK](/products/seek/) we call the **IBISBAHub**. 

We will evaluate an open source Business Process Model system (e.g. [Activiti](https://www.activiti.org/) or [Apache ODE](http://ode.apache.org/)) to model the full path from research through to production process to create a demonstrator that includes the execution of different computational workflows, interaction with researchers and lab equipment.

All workflows and their companion [Research Objects](/products/researchobject/) will be accessible from the IBISBAHub, which will provide separate spaces for secure project collaboration.

<figure>
<img src="/images/screenshots/lg_ibisba-overview.png" width="1583" height="622" style="width: 100%; height: auto" />
<figcaption>Figure 1: Proposed IBISBA workflow architecture. (Adapted from H2020 proposal)</figcaption>
</figure>

### Related tasks

* T7.1 Development of computational and experimental nodes specific to industrial biotechnology
* T7.2 Development of computational and experimental workflows specific to industrial biotechnology
* T7.3 Development and management of the IBISBAHub for workflows (task leader)
* T7.4 Investigation of BPM workflows (task leader)

## Related projects and initiatives

* [SynBioChem](/projects/synbiochem)
* [SEEK platform](/products/seek/)
* [Common Workflow Language](/activities/cwl/) 
* [Research Object](/products/researchobject/)



<!--
## Related publications

A Author, B Other (2018):
**Title**
_Journal_ **Vol**
[doi:10.100/a1](https://doi.org/10.100/a1)
-->


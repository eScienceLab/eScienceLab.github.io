---
layout: activity
name: cwl
title: Common Workflow Language
path: cwl
collection: activities
description: Community-led specification for describing analysis workflows and tools in a way that makes them portable and scalable across a variety of software and hardware environments
logo: cwl.svg
website: http://www.commonwl.org/
---

The **[Common Workflow Language](http://www.commonwl.org/) (CWL)** is a community-led specification to express portable workflow and tool descriptions, which can be executed by multiple leading [workflow engine implementations](http://www.commonwl.org/#Implementations). Unlike previous standardisation attempts, CWL has taken a pragmatic approach and focused on what most workflow systems are able to do: *Execute command line tools and pass files around in a top-to-bottom pipeline.* At the heart of CWL workflows are the tool descriptions. A command line is described, with parameters, input and output files, in a [YAML format](http://www.commonwl.org/v1.0/UserGuide.html#Wrapping_Command_Line_Tools) so they can be shared across workflows and linked to from registries like [ELIXIR](/projects/elixir/)’s [bio.tools](https://bio.tools/). These are then combined and wired together in a second YAML file to form a [workflow template](http://www.commonwl.org/v1.0/UserGuide.html#Writing_Workflows), which can be executed on any of the supported implementations, repeatedly and on different platforms by specifying input files and workflow parameters. The [CWL User Guide](http://www.commonwl.org/v1.0/UserGuide.html) gives a gentle introduction to the language, while the more detailed [CWL specifications](http://www.commonwl.org/v1.0/) formalize CWL concepts so they can be implemented by the different workflow systems. 

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/86eY8xs-Vo8" frameborder="0" allowfullscreen></iframe>

The eScience Lab have participated in the CWL project since its early days, contributing with our workflow and reproducibility expertise from [Apache Taverna](/products/taverna/), [Research Objects](/products/researchobjects/) and [myExperiment](/products/myexperiment/). The [CWL Viewer](/products/cwlviewer/), developed by the eScience Lab with support from [BioExcel](/projects/bioexcel/), provides a graphical visualization of CWL workflows.

## References

Mark Robinson, Stian Soiland-Reyes, Michael R Crusoe, Carole Goble (2017): 
**[CWL Viewer: The Common Workflow Language viewer](https://www.research.manchester.ac.uk/portal/en/publications/cwl-viewer(b60c4d3c-303b-4b54-94f0-9cb1e9059b20).html)** [version 1; not peer reviewed]. _F1000Research_ 2017, **6**(ISCB Comm J):1075 (poster) [https://doi.org/10.7490/f1000research.1114375.1](https://doi.org/10.7490/f1000research.1114375.1)

Peter Amstutz, Michael R. Crusoe, Nebojša Tijanić (editors), Brad Chapman, John Chilton, Michael Heuer, Andrey Kartashov, Dan Leehr, Hervé Ménager, Maya Nedeljkovich, Matt Scales, Stian Soiland-Reyes, Luka Stojanovic (2016): 
**Common Workflow Language, v1.0**.
Specification, _Common Workflow Language working group_. 
[https://w3id.org/cwl/v1.0/](https://w3id.org/cwl/v1.0/)
[https://doi.org/10.6084/m9.figshare.3115156.v2](https://doi.org/10.6084/m9.figshare.3115156.v2)
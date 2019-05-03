---
layout: project
name: datastage
title: DataSTAGE FAIR4CURES
path: datastage.html
collection: projects
description: Storage, Toolspace, Access and analytics for Big Data Empowerment
logo: datastage.jpg
website: https://www.nhlbidatastage.org/
start_date: 2018-08-01
duration: 12 months
project_reference: https://www.nhlbi.nih.gov/science/data-storage-toolspace-access-and-analytics-big-data-empowerment-datastage
---

The NHLBI's [DataSTAGE](https://www.nhlbidatastage.org/) project will develop innovative computing solutions that meet the needs of the NHLBI and our research community, building on the cloud-based infrastructure of the [NIH Data Commons](https://commonfund.nih.gov/commons), which [kicked off in 2018](http://www.researchobject.org/2017-12-commonspilot/). NHLBI's DataSTAGE is a cloud-based platform, or technical framework, for tools, applications, and workflows. DataSTAGE provides secure workspaces to share, store, cross-link, and compute large sets of data generated from biomedical and behavioral research.

## FAIR4CURES

[Seven Bridges Genomics](https://www.sevenbridges.com/) and the [Elsevier Mendeley Data](https://www.elsevier.com/solutions/mendeley-data-platform) team collaborate in the DataSTAGE project in _Team Xenon_ to continue development of [FAIR4Cures](https://www.slideshare.net/mobile/anitawaard/cni-2018-a-research-object-authoring-tool-for-the-data-commons), which was [initiated](https://www.elsevier.com/about/press-releases/science-and-technology/elsevier-and-seven-bridges-receive-nih-data-commons-grant-for-biomedical-data-analysis) as a [NIH Data Commons pilot](https://commonfund.nih.gov/commons) in the [Data Commons Pilot Phase Consortium (DCPPC)](https://public.nihdatacommons.us/) and now carried forward as part of DataSTAGE.

FAIR4Cures aims to build a FAIR genomics workflow execution and data management solution. The core components are:

* [Common Workflow Language](/activities/cwl/) for interoperable definitions of the computational workflows
* [Seven Bridges Platform](https://www.sevenbridges.com/platform/) for executing scalable workflows
* [Research Object](/products/researchobject/) for packaging the result dataset including executed worklow as [BDBags](http://bd2k.ini.usc.edu/tools/bdbag/)
* [Mendeley Data](https://data.mendeley.com/) for archiving/publishing the research objects
* [GUID Broker](https://public.nihdatacommons.us/DCPPC-DRAFT-8_KC2/) for assigning and resolving permanent identifiers of workflows, datasets and research objects, using DOIs and MinIDs

## eScience Lab contribution

In DataStage, eScience Lab is a subcontractor to Mendeley Data to develop the [Research Object Composer](https://github.com/ResearchObject/research-object-composer) and consult on [Research Object](/products/researchobject/) structure, building on our existing collaboration with Seven Bridges in the [Common Workflow Language](/activities/cwl/) project.

The role of the Research Object Composer is to be the bridge between the workflow execution platform [Seven Bridges Platform](https://www.sevenbridges.com/platform/) and the repository [Mendeley Data](https://data.mendeley.com/). Instances of the composer expose a [REST API](https://researchobject.github.io/research-object-composer/api/) for the workflow platform and any other clients to incremenetally build a research object according to the slots defined in a specified profile (e.g. "prospective workflow run"), validate it according to the underlying JSON and SHACL schemas, and build a BDBag to submits the archived RO to the repository. A [Jupyter Notebook](https://github.com/ResearchObject/research-object-composer/blob/master/introduction.ipynb) demonstrates how the RO Composer API can be used by clients.

Additional responsibilities we are exploring for the RO Composer is to handle snapshotting and registering of individual data files and workflows using [MinIDs](http://minid.bd2k.org/) and checksums, as well as tracking evolution of Research Objects built using the composer.

The RO Composer is generic for building according to any Research Object profile, so we are also planning to extend it to build [BioCompute Objects](https://esciencelab.org.uk/research_object/fda/collaborations/2017/11/09/biocompute-objects/) for a [PrecisionFDA challenge](https://precision.fda.gov/challenges), as well as building more specific profiles for [RO-Crate](https://researchobject.github.io/ro-lite/).

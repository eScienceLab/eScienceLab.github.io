---
layout: project
#name: datastage
name: ro-composer
tile: Research Object Composer
#title: DataSTAGE FAIR4CURES
#path: datastage.html
path: ro-composer.html
collection: projects
#description: Storage, Toolspace, Access and analytics for Big Data Empowerment
description: 
#logo: datastage.png
#website: https://datastage.io/
website: https://github.com/ResearchObject/research-object-composer
start_date: 2018-08-01
duration: 12 months
project_reference: https://reporter.nih.gov/project-details/9732880
expirted: true
---

eScience Lab is a subcontractor to Elsevier [Mendeley Data](https://data.mendeley.com/) to develop the [Research Object Composer](https://github.com/ResearchObject/research-object-composer) and consult on [Research Object](/products/researchobject/) structure, building on our existing collaboration with Seven Bridges in the [Common Workflow Language](/activities/cwl/) project.

The role of the Research Object Composer is to be the bridge between the workflow execution platform [Seven Bridges Platform](https://www.sevenbridges.com/platform/) and the repository [Mendeley Data](https://data.mendeley.com/). Instances of the composer expose a [REST API](https://researchobject.github.io/research-object-composer/api/) for the workflow platform and any other clients to incrementally build a research object according to the slots defined in a specified profile (e.g. "prospective workflow run"), validate it according to the underlying JSON and SHACL schemas, and build a BDBag to submits the archived RO to the repository. A [Jupyter Notebook](https://github.com/ResearchObject/research-object-composer/blob/master/introduction.ipynb) demonstrates how the RO Composer API can be used by clients.

Additional responsibilities we are exploring for the RO Composer is to handle snapshotting and registering of individual data files and workflows using [MinIDs](http://minid.bd2k.org/) and checksums, as well as tracking evolution of Research Objects built using the composer.

The RO Composer is generic for building according to any Research Object profile, so we are also planning to extend it to build [BioCompute Objects](https://esciencelab.org.uk/research_object/fda/collaborations/2017/11/09/biocompute-objects/) for a [PrecisionFDA challenge](https://precision.fda.gov/challenges/7), as well as building more specific profiles for [RO-Crate](https://researchobject.github.io/ro-crate/).

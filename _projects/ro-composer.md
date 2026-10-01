---
layout: project
name: ro-composer
title: Research Object Composer
path: ro-composer.html
collection: projects
description: Bridge between Mendeley Data and Seven Bridges Platform.
website: https://github.com/ResearchObject/research-object-composer
start_date: 2018-08-01
duration: 12 months
project_reference: https://reporter.nih.gov/project-details/9732880
expired: true
---

eScience Lab was a subcontractor to Elsevier [Mendeley Data](https://data.mendeley.com/) to develop the [Research Object Composer](https://github.com/ResearchObject/research-object-composer) and consult on [Research Object](/products/researchobject/) structure, building on our existing collaboration with Seven Bridges in the [Common Workflow Language](/activities/cwl/) project.

The role of the Research Object Composer was to be the bridge between the workflow execution platform [Seven Bridges Platform](https://www.sevenbridges.com/platform/) and the repository [Mendeley Data](https://data.mendeley.com/). Instances of the composer expose a [REST API](https://researchobject.github.io/research-object-composer/api/) for the workflow platform and any other clients to incrementally build a research object according to the slots defined in a specified profile (e.g. "prospective workflow run"), validate it according to the underlying JSON and SHACL schemas, and build a BDBag to submits the archived RO to the repository. A [Jupyter Notebook](https://github.com/ResearchObject/research-object-composer/blob/master/introduction.ipynb) demonstrates how the RO Composer API can be used by clients.

Additional responsibilities we explored for the RO Composer incldue handling snapshotting and registering of individual data files and workflows using [MinIDs](http://minid.bd2k.org/) and checksums, as well as tracking evolution of Research Objects built using the composer.

The RO Composer is generic for building according to any Research Object profile, so we considered extending it to build [BioCompute Objects](https://esciencelab.org.uk/research_object/fda/collaborations/2017/11/09/biocompute-objects/) for a [PrecisionFDA challenge](https://precision.fda.gov/challenges/7), as well as building more specific profiles for [RO-Crate](https://researchobject.github.io/ro-crate/).

**Note:** For building RO-Crate using a REST API, we instead recommend the [RO-Hub API](https://reliance-eosc.github.io/ROHUB-API_documentation/html/) or [An RO-Crate API](https://ro-crate-api.crate-works.org/). See [RO-Crate Tools](https://www.researchobject.org/ro-crate/tools) for libraries for Python, Javascript, R, Rust, etc.

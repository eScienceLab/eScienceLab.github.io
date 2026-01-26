---
layout: post
title: "Collaborations at the 4th BioHackathon Germany"
date: 2026-01-26
categories: elixir hackathon
---

The [4th BioHackathon Germany](https://www.denbi.de/de-nbi-events/1840-4th-biohackathon-germany) took place from 1-5 December 2025 in Walsrode, Germany, organised by de.NBI and ELIXIR Germany. Life scientists, data managers, software developers and project leaders attended the hybrid event to work together on open source code, standards and infrastructure to advance research data practices and tools.

![Colourful umbrellas mounted the ceiling as art.](/images/posts_images/umbrellas.jpg)


## Improving RO-Crate support in federated storage systems

One of the hackathon projects was titled [Enhancing FAIR (Meta-)Data Practices in Life Science by Improving RO-Crates Support in Federated Storage Systems](https://das-abroxas.github.io/2025_Biohackathon_Documentation/project_description.html). 
It was led by Sebastian Beyvers and Jannis Schlegel (University of Giessen).

During their participation in the Biohackathon Germany 2025, their working group engaged in extensive discussions focused on the practical and technical challenges of integrating [RO-Crates](/products/researchobject/) in federated storage systems for life science data. The group produced many outputs including extensions to [ro-crate-py](https://github.com/ResearchObject/ro-crate-py/pull/244) Python library and [ro-crate-rs](https://github.com/intbio-ncl/ro-crate-rs) Rust library, an [RO-Crate indexing tool](https://github.com/arunaengine/rocrate-indexer), and  the [RO-Crate Explorer](https://github.com/arunaengine/RO-Crate-Explorer) application to parse, visualise and traverse RO-Crates.

* [Read more on the RO-Crate blog](https://www.researchobject.org/ro-crate/blog/2025-12-17/biohackathon-germany)


## Making FAIRer access to training registries and learning paths across domains

The hackathon project titled [On the path to machine-actionable training materials](https://osf.io/preprints/biohackrxiv/un6cd_v1) was led by Nick Juty (University of Manchester) and Petra Steiner (Technical University of Darmstadt). The lead author of the project report was Phil Reed (University of Manchester).

The project operated across three interrelated streams: metadata interoperability, material analysis, and the definition and representation of learning paths in a machine readable manner. 

- Content federation was demonstrated via the [mTeSS-X](/projects/mtess-x/) platform, enabling cross-instance exchange and preparing for future integration with the EOSC federation. To enhance interoperability, relevant ontologies and crosswalks were curated between established metadata models, specifically MoDALIA and Schema.org/[Bioschemas](/activities/bioschemas/). These mappings were implemented within the open-source OERbservatory Python package, providing a facility for exchanging data between platforms such as DALIA and [TeSS](/products/tess/).
- For material analysis, Large Language Models (LLMs) were utilised and vectorisation techniques were explored to calculate similarity, allowing for the identification of related materials and the potential for future deduplication of records across registries.
- To address the lack of machine-actionable trajectories across related or sequential materials, new [Bioschemas](/activities/bioschemas/) profiles were proposed, specifically for learning paths. This model was validated using SPARQL queries on knowledge graphs derived from real-world examples like the Galaxy Training Network. 

Such advancements provide a foundation for automated path generation and improved discoverability within training catalogues, and serves as a use case and strategy with broader applicability beyond those materials.

* [Read more in the project report in BioHackrXiv (doi:10.37044/osf.io/un6cd_v1)](https://doi.org/10.37044/osf.io/un6cd_v1)

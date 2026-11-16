---
layout: project
name: fortress
title: FORTRESS-TeHR
path: fortress.html
collection: projects
description: Federated, Open and Reliable TREs for Synthetic Textual Healthcare Records
# logo: 
website: https://dareuk.org.uk/how-we-work/ongoing-activities/dare-uk-next-gen-catalysts/fortress/
start_date: 2025-09-01
expired: true
duration: 12 months
project_reference: https://gtr.ukri.org/find-research-and-innovation/project/dfa0bb0f-a0fe-4646-ab51-5720ffa9106d
---

**FORTRESS-TeHR (Federated, Open and Reliable TREs for Synthetic Textual Healthcare Records) is a [DARE UK Next-Gen Catalysts](https://dareuk.org.uk/how-we-work/ongoing-activities/dare-uk-next-gen-catalysts/) project. The University of Manchester is the lead organisation, with Professor Goran Nenadić as principal investigator, working with project partners Imperial College London, MHRA, NICE and Umbizo. Funded by UKRI (reference [UKRI3800](https://gtr.ukri.org/find-research-and-innovation/project/dfa0bb0f-a0fe-4646-ab51-5720ffa9106d)), the project ran from September 2025 to September 2026.**

FORTRESS-TeHR is developing trusted, federated approaches to generating and validating synthetic clinical text, enabling the safe use of sensitive free-text data for research.

Current Trusted Research Environments (TREs) are designed for secure and efficient handling of real-world structured data. Missing from this landscape is free-text narrative, a key data source in healthcare: valuable clinical information is often recorded only in notes and reports, and some specialties, such as mental health, document care almost entirely in text. Because of its inherent sensitivity and the unquantified risks to patient privacy, real-world free-text data is rarely, if ever, hosted within TREs.

Synthetic text collections are emerging as an alternative and trustworthy solution, where data is generated through an AI process that ensures both task-specific data relevance and privacy. FORTRESS-TeHR explores embedding synthetic healthcare text generation into existing TRE infrastructures developed in DARE UK Phase 2, using de-identified real-world data from different settings as a guide for federated text generation, and differential privacy to ensure patient confidentiality.

Together with clinicians, patients and regulators, the project co-develops an early technical validation framework covering privacy validation, text quality assessment and the usefulness of generated data for analytics tasks. As a demonstrator use case, the framework is applied to federated learning for downstream language modelling tasks in cardiology, and a series of "validatathons", led by Warren Del-Pinto, was held with patients, clinicians, data scientists and regulators to explore the challenges, opportunities and acceptance of synthetic free-text data.

By the end of the project, FORTRESS-TeHR will:

-   Prototype federated workflows for generating synthetic clinical free text
-   Develop validation approaches for assessing utility and privacy risk
-   Produce guidance on the appropriate use of synthetic text in TREs
-   Support regulatory and public confidence in synthetic data methods

### eScience Lab involvement

Generated data is represented using adapted common data models for sensitive data (e.g. OMOP), with [RO-Crate](/products/researchobject/) used to represent additional metadata describing the synthetic generation process and data provenance. Carole Goble and Stian Soiland-Reyes are co-investigators on the project.

The synthetic text generation prototype, Term2Note, is packaged as a Docker container so that it can be deployed and run within TREs. FORTRESS builds on the federated TRE infrastructure of the DARE UK Phase 2 [TREvolution](/projects/trevolution/) programme, where the eScience Lab leads the FAIR metadata framework based on [Five Safes RO-Crate](https://www.researchobject.org/ro-crate/5s-crate). Using the [HDR RO-Crate Toolkits](https://github.com/eScienceLab/HDR-RO-Crate-Toolkits) ([FORTRESS instructions](https://github.com/eScienceLab/HDR-RO-Crate-Toolkits/blob/development/docs/fortress.md)), the FORTRESS container is submitted as a [GA4GH TES](https://www.ga4gh.org/product/task-execution-service-tes/) task within a Five Safes RO-Crate to a [Five Safes TES (5S-TES)](https://docs.federated-analytics.ac.uk/introduction) federated TRE stack, and its results are retrieved as an RO-Crate after approval by the TRE's data egress checks. 5S-TES, developed by Swansea University and the University of Nottingham, is foundational to [HDR UK Federated Analytics](/projects/federated-analytics/), TREvolution and [EOSC-ENTRUST](/projects/eosc-entrust/). The project also extends the RO-Crate metadata model to describe both the text generation process and its outcome, the synthetic text dataset, alongside a synthetic free-text "data card" template covering provenance, quality, privacy and utility.

## Related references and outreach by FORTRESS team

Goran Nenadic (2026):  
[**FORTRESS: Exploring generation, validation and deployment of synthetic free-text data**](https://dareuk.org.uk/news-and-events/fortress-exploring-generation-validation-and-deployment-of-synthetic-free-text-data-2/).  
_DARE UK_ (blog), 2026-10-20

Goran Nenadic (2026):  
[**Federated Synthetic Text Generation**](https://dareuk.org.uk/wp-content/uploads/2026/03/Slides_14-Mar-26_Next-Gen_Catalysts-Updated.pdf) (slides 17–29).  
_Shaping the future of data research: Meet the DARE UK Next-Gen Catalysts_ (webinar), 2026-03-04

Yuping Wu, Viktor Schlegel, Warren Del-Pinto, Srinivasan Nandakumar, Iqra Zahid, Yidan Sun, Hao Li, Usama Farghaly Omar, Amirah Jasmine, Arun-Kumar Kaliya-Perumal, Chun Shen Tham, Gabriel Connors, Anil A Bharath, Goran Nenadic (2025):  
[**Privacy-Preserving Generation of Clinical Narratives from Medical Terminologies**](https://doi.org/10.48550/arXiv.2509.10882).  
_arXiv_ (preprint)  
<https://doi.org/10.48550/arXiv.2509.10882>

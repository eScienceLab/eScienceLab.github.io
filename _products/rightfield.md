---
layout: product
name: rightfield
title: RightField
path: rightfield
collection: products
description: Semantic annotation of text by stealth
website: https://rightfield.org.uk/
logo: /images/logo/rightfield-logo-with-text.png
screenshot: /images/screenshots/rightfield.png
---


RightField is an open-source tool for adding ontology term selection to Excel spreadsheets. RightField is used by a 'Template Creator' to create semantically aware Excel spreadsheet templates. The Excel templates are then reused by Scientists to collect and annotate their data; without any need to understand, or even be aware of, RightField or the ontologies used.

For each annotation field, RightField can specify a range of allowed terms from a chosen ontology (subclasses, individuals or combinations). The resulting spreadsheet presents these terms to the users as a simple drop-down list. This reduces the adoption barrier for using community ontologies as the annotation is made by the scientist that generated the data rather than a third party, and the annotation is collected at the time of data collection.

RightField is a standalone Java application which uses Apache-POI for interacting with Microsoft documents. It enables users to import Excel spreadsheets, or generate new ones from scratch. Ontologies can either be imported from their local file systems, or from the BioPortal ontology repository. Individual cells, or whole columns or rows can be marked with the required ranges of ontology terms and an individual spreadsheet can be annotated with terms from multiple ontologies.

---
layout: project
name: Open PHACTS
title: Open PHACTS
path: openphacts.html
collection: projects
description: Bringing together pharmacological data resources in an integrated, interoperable infrastructure
logo: openphacts.svg
website: http://www.openphacts.org/
project_reference: http://www.imi.europa.eu/content/open-phacts
start_date: 2011-03-01
end_date: 2016-02-29
duration: 5 years
expired: true
---


The [Open PHACTS](http://www.openphacts.org) Discovery Platform was developed to reduce barriers to drug discovery in industry, academia and for small businesses. It contains various data sources, integrated and linked together so that the relationships between compounds, targets, pathways, diseases, tissues and publications can be easily found. [Data sources](http://www.openphacts.org/2/sci/data.html) include ChEBI, ChEMBL, ChemSpider, ConceptWiki, DisGeNET, DrugBank, Gene Ontology, neXtProt, UniProt and WikiPathways.

Open PHACTS (or _"OPS"_ for short) was [funded for 5 years by IMI](http://www.imi.europa.eu/content/open-phacts), and is now maintained by the independent [Open PHACTS Foundation](http://www.openphactsfoundation.org/) which continues collaboration with the 
eScience Lab, [BioExcel](/projects/bioexcel) and [Excelerate](/projects/excelerate).


## eScience Lab contributions

eScience Lab contributed multiple products that together form the the Open PHACTS Platform:

* Visualization: [Open PHACTS Explorer](https://explorer.openphacts.org/) - a web-app that shows pharmacological compound and target information, [ops.js](https://www.npmjs.com/package/ops.js) JavaScript library and  [Open PHACTS HTML widgets](https://github.com/openphacts/ops-html-widgets) for embedding OPS data
* API: [Open PHACTS API](https://dev.openphacts.org/docs), maintaining queries and deployment. URIs are mapped before constructing SPARQL queries in the underlying RDF store
* Packaging: [data.openphacts.org](http://data.openphacts.org/), data preparation/loading/testing/distribution, both as [Research Object BagIt](https://github.com/ResearchObject/bagit-ro)-formed [archives](http://data.openphacts.org/artifactory/data/dev/2.0/rdf/) and as a [Maven Repository](http://data.openphacts.org/artifactory/data/org/openphacts/data/)
* Mapping: [Open PHACTS Identity Mapper Service](https://github.com/openphacts/queryExpander/tree/master/docker), [QueryExpander](http://ops2.few.vu.nl/QueryExpander), [BridgeDB](http://www.bridgedb.org/) and the maintenance of its [linksets](http://data.openphacts.org/2.1/ims/linksets/)
* Searching: [Open PHACTS search service](https://github.com/openphacts/ops-search), populates an ElasticSearch instance with JSON-LD documents with searchable labels extracted from SPARQL queries
* Deployment: [Open PHACTS Docker installation](https://github.com/openphacts/ops-docker/) installs the OPS platform
* Standardization: [Open PHACTS Dataset descriptions](http://www.openphacts.org/specs/2013/WD-datadesc-20130912/) and the [W3C HCLS]() working group's [Dataset Descriptions: HCLS Community Profile](https://www.w3.org/TR/hcls-dataset/)

## Related projects and initiatives

* [BioExcel](/projects/bioexcel) 
* [Research Object](/products/researchobject/)
 
## Related publications


Mark D. Wilkinson, Michel Dumontier, IJsbrand Jan Aalbersberg, Gabrielle Appleton, Myles Axton, Arie Baak,
Niklas Blomberg, Jan-Willem Boiten, Luiz Bonino da Silva Santos, Philip E. Bourne, Jildau Bouwman, Anthony J. Brookes,
Tim Clark, Mercè Crosas, Ingrid Dillo, Olivier Dumon, Scott Edmunds, Chris T. Evelo, Richard Finkers,
Alejandra Gonzalez-Beltran, Alasdair J.G. Gray, Paul Groth, Carole Goble, Jeffrey S. Grethe, Jaap Heringa,
Peter A.C ’t Hoen, Rob Hooft, Tobias Kuhn, Ruben Kok, Joost Kok, Scott J. Lusher, Maryann E. Martone, Albert Mons,
Abel L. Packer, Bengt Persson, Philippe Rocca-Serra, Marco Roos, Rene van Schaik, Susanna-Assunta Sansone, Erik Schultes,
Thierry Sengstag, Ted Slater, George Strawn, Morris A. Swertz, Mark Thompson, Johan van der Lei, Erik van Mulligen,
Jan Velterop, Andra Waagmeester, Peter Wittenburg, Katherine Wolstencroft, Jun Zhao & Barend Mons (2016)
**The FAIR Guiding Principles for scientific data management and stewardship**
_Nature Scientific Data_ **3**, 2016
[doi:10.1038/sdata.2016.18](http://dx.doi.org/10.1038/sdata.2016.18)


Carole Goble,
Alasdair J G Gray,
Eleftherios Tatakis (2014):
**Help me describe my data: A demonstration of the Open PHACTS VoID Editor**.
_ISWC-P&D 2014: Proceedings of the ISWC 2014 Posters & Demonstrations Track_,
CEUR-WS.org online [http://ceur-ws.org/Vol-1272/paper_33.pdf](http://ceur-ws.org/Vol-1272/paper_33.pdf)

Christian Brenninkmeijer, Chris Evelo, Carole Goble, Alasdair J G Gray, Paul Groth, Steve Pettifer, Robert Stevens, Antony J Williams, Egon L Willighagen (2013):
**Scientific Lenses: An Approach to Dynamically Vary the Relationships between Datasets**.
_Intelligent Systems for Molecular Biology and European Conference on Computational Biology_ (ISMB/ECCB 2013), Berlin, Germany, July 2013.
[[pdf]](http://linkedscience.org/wp-content/uploads/2012/05/lisc2012_submission_8.pdf)

Paolo Ciccarese, Stian Soiland-Reyes, Khalid Belhajjame, Alasdair JG Gray, Carole Goble, Tim Clark (2013): **PAV ontology: provenance, authoring and versioning**.
_Journal of Biomedical Semantics_ **4**:1, 37. [doi:10.1186/2041-1480-4-37](http://dx.doi.org/10.1186/2041-1480-4-37)

Alasdair J. G. Gray, Paul Groth, Antonis Loizou, Sune Askjaer, Christian Brenninkmeijer, Kees Burger, Christine Chichester, Chris T. Evelo, Carole Goble, Lee Harland, Steve Pettifer, Mark Thompson, Andra Waagmeester, Antony J. Williams (2013):
**Applying linked data approaches to pharmacology**.
_Semantic Web_ **5**(3), 1–13.
[[pdf]](http://www.semantic-web-journal.net/system/files/swj258_1.pdf)
[[journal article]](http://www.semantic-web-journal.net/content/applying-linked-data-approaches-pharmacology-architectural-decisions-and-implementation)

Christian Y A Brenninkmeijer, Ian Dunlop, Carole Goble, Alasdair J G Gray, Steve Pettifer, Robert Stevens (2013):
**Computing Identity Co-Reference Across Drug Discovery Datasets**.
_Proceedings of the 6th International Workshop on Semantic Web Applications and Tools for Life Sciences (SWAT4LS)_; CEUR-WS.org; 2013.
[http://ceur-ws.org/Vol-1114/Session4_Brenninkmeijer.pdf](http://ceur-ws.org/Vol-1114/Session4_Brenninkmeijer.pdf)


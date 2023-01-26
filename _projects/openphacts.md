---
layout: project
name: Open PHACTS
title: Open PHACTS
path: openphacts.html
collection: projects
description: Bringing together pharmacological data resources in an integrated, interoperable infrastructure
logo: openphacts.svg
website: http://www.openphacts.org/
project_reference: https://cordis.europa.eu/project/id/115191
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
* [Open PHACTS VoID editor](https://github.com/openphacts/Void-Editor2), a web-based editor to create OPS Dataset and Linkset Descriptions with provenance

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
Jan Velterop, Andra Waagmeester, Peter Wittenburg, Katherine Wolstencroft, Jun Zhao & Barend Mons (2016):  
[**The FAIR Guiding Principles for scientific data management and stewardship**](https://doi.org/10.1038/sdata.2016.18).  
_Nature Scientific Data_ **3**, 2016  
<https://doi.org/10.1038/sdata.2016.18>

Paul Groth, Antonis Loizou, Alasdair J.G. Gray, Carole Goble, Lee Harland, Steve Pettifer (2014):  
**API-centric Linked Data integration: The Open PHACTS Discovery Platform case study**.  
_Web Semantics: Science, Services and Agents on the World Wide Web_  
<https://doi.org/10.1016/j.websem.2014.03.003>
[[preprint](https://www.research.manchester.ac.uk/portal/files/209942151/359_609_1_SM.pdf)]

Joseline Ratnam , Barbara Zdrazil, Daniela Digles, Emiliano Cuadrado-Rodriguez, Jean-Marc Neefs, Hannah Tipney, Ronald Siebes, Andra Waagmeester, Glyn Bradley, Chau Han Chau, Lars Richter, Jose Brea, Chris T. Evelo, Edgar Jacoby, Stefan Senger, Maria Isabel Loza, Gerhard F. Ecker, Christine Chichester (2014):  
[**The Application of the Open Pharmacological Concepts Triple Store (Open PHACTS) to Support Drug Discovery Research**](https://doi.org/10.1371/journal.pone.0115460).  
_PLOS ONE_ **9**(12): e115460.  
<https://doi.org/10.1371/journal.pone.0115460>

Alasdair J. G. Gray, Paul Groth, Antonis Loizou, Sune Askjaer, Christian Brenninkmeijer, Kees Burger, Christine Chichester, Chris T. Evelo, Carole Goble, Lee Harland, Steve Pettifer, Mark Thompson, Andra Waagmeester, Antony J. Williams (2014):  
**Applying linked data approaches to pharmacology: Architectural decisions and implementation**.  
_Semantic Web_ **5**(3), 1–13.  
<https://doi.org/10.3233/SW-2012-0088>
[[pdf]](http://www.semantic-web-journal.net/system/files/swj258_1.pdf)

Carole Goble, Alasdair J G Gray, Eleftherios Tatakis (2014):  
[**Help me describe my data: A demonstration of the Open PHACTS VoID Editor**](http://ceur-ws.org/Vol-1272/paper_33.pdf).  
_ISWC-P&D 2014: Proceedings of the ISWC 2014 Posters & Demonstrations Track_,
_CEUR Workshop Proeedings_ **1272**:33  
<http://ceur-ws.org/Vol-1272/paper_33.pdf>

Colin Batchelor, Christian Y. A. Brenninkmeijer, Christine Chichester, Mark Davies, Daniela Digles, Ian Dunlop, Chris T. Evelo, Anna Gaulton, Carole Goble, Alasdair J. G. Gray, Paul Groth, Lee Harland, Karen Karapetyan, Antonis Loizou, John P. Overington (2014):  
[*Scientific Lenses to Support Multiple Views over Linked Chemistry Data**](https://link.springer.com/content/pdf/10.1007%2F978-3-319-11964-9_7.pdf).  
_Proceedings of 13th International Semantic Web Conference, Part 1_, (ISWC 2014) Riva del Garda, Italy, October 19-23, 2014.
_Lecture Notes in Computer Science_ **8796**.  
<https://doi.org/10.1007/978-3-319-11964-9_7>
[[preprint](https://www.research.manchester.ac.uk/portal/en/publications/scientific-lenses-to-support-multiple-views-over-linked-chemistry-data(5eb9b5f8-2f13-478a-a99d-2b4cc3c5cf4c).html)]

Christian Brenninkmeijer, Chris Evelo, Carole Goble, Alasdair J G Gray, Paul Groth, Steve Pettifer, Robert Stevens, Antony J Williams, Egon L Willighagen (2013):  
[**Scientific Lenses: An Approach to Dynamically Vary the Relationships between Datasets**](http://ceur-ws.org/Vol-951/paper5.pdf).  
_Proceedings of the Second International Workshop on Linked Science 2012 - Tackling Big Data_ ([LISC 2012](http://ceur-ws.org/Vol-951/)).
In conjunction with the International Semantic Web Conference (ISWC2012).
_CEUR Workshop Proeedings_ **951**:5  
<http://ceur-ws.org/Vol-951/paper5.pdf>

Paolo Ciccarese, Stian Soiland-Reyes, Khalid Belhajjame, Alasdair JG Gray, Carole Goble, Tim Clark (2013):  
[**PAV ontology: provenance, authoring and versioning**](https://doi.org/10.1186/2041-1480-4-37).  
_Journal of Biomedical Semantics_ **4**:1, 37.  
<https://doi.org/10.1186/2041-1480-4-37>

Christian Y A Brenninkmeijer, Ian Dunlop, Carole Goble, Alasdair J G Gray, Steve Pettifer, Robert Stevens (2013):  
[**Computing Identity Co-Reference Across Drug Discovery Datasets**](http://ceur-ws.org/Vol-1114/Session4_Brenninkmeijer.pdf).  
_Proceedings of the 6th International Workshop on Semantic Web Applications and Tools for Life Sciences (SWAT4LS)_; 
_CEUR Workshop Proeedings_ **1114**:4  
<http://ceur-ws.org/Vol-1114/Session4_Brenninkmeijer.pdf>

Kamal Azzaoui, Edgar Jacoby, Stefan Senger, Emiliano Cuadrado Rodríguez3, Mabel Loza, Barbara Zdrazil, Marta Pinto, Antony J. Williams, Victor de la Torre, Jordi Mestres, Manuel Pastor, Olivier Taboureau, Matthias Rarey, Christine Chichester, Steve Pettifer, Niklas Blomberg, Lee Harland, Bryn Williams-Jones, Gerhard F. Ecker (2013):  
[**Scientific competency questions as the basis for semantically enriched open pharmacological space development**](https://doi.org/10.1016/j.drudis.2013.05.008).  
_Drug Discovery Today_ **18** (17-18) pp 843–852.  
<https://doi.org/10.1016/j.drudis.2013.05.008>

Antony J. Williams, Lee Harland, Paul Groth, Stephen Pettifer, Christine Chichester, Egon L. Willighagen, Chris T. Evelo, Niklas Blomberg, Gerhard Ecker, Carole Goble, Barend Mons (2012):  
[**Open PHACTS: semantic interoperability for drug discovery**](https://doi.org/10.1016/j.drudis.2012.05.016).  
_Drug Discovery Today_  **17**(21-22) pp 1188 - 1198.  
<https://doi.org/10.1016/j.drudis.2012.05.016>

Lee Harland (2012):  
**Open PHACTS: A Semantic Knowledge Infrastructure for Public and Commercial Drug Discovery Research**.  
_18th International Conference on Knowledge Engineering and Knowledge Management_ (EKAW 2012),
Galway City, Ireland, October 8-12, 2012.
<https://doi.org/10.1007/978-3-642-33876-2_1> 
[[preprint]](http://www.openphacts.org/documents/publications/Harland_Open%20PHACTS_A%20semantic%20knowledge%20infrastructure%20for%20public%20and%20commercial%20drug%20discovery%20research_Springer_Lecture%20Notes%20in%20Computer%20Science_V%207603_2012_p1-7.pdf)


---
layout: project
name: cagrid
title: caGrid
path: cagrid.html
collection: projects
description: Support for running cancer-research workflows
logo: caGrid.png
website: https://github.com/NCIP/cagrid-workflow
start_date: 2008-09-01
duration: 14 months
project_reference: http://dev.mygrid.org.uk/wiki/download/attachments/426053/Manchester+Amended+7_29_08.doc?version=1
expired: true
---

[caGrid](https://github.com/NCIP/cagrid) was part of [caBIG](https://en.wikipedia.org/wiki/CaBIG) (cancer Biomedical Informatics Grid), a US project to carry out eScience and bioinformatics in cancer research.

The myGrid team were funded by the US National Cancer Institute ([NCI](http://www.cancer.gov/)) to help caGrid integrate [Taverna](http://www.taverna.org.uk/) and caGrid, so that Taverna can [find and use](https://github.com/NCIP/cagrid-workflow) (secured) caBIG services, and so the Taverna engine could be [exposed as a caBIG service](https://github.com/NCIP/taverna-grid).

The team wrapped a selection of typical non-caBIG services used by Taverna users so that they are annotated and comply with caBIG’s compatability requirements, as described by the [caGrid Taverna deliverables](http://dev.mygrid.org.uk/wiki/display/caGrid/Deliverables) [(archived)](https://wiki.nci.nih.gov/display/GFORGEARCHIVES/Docs+Archive+Page+-+taverna-cagrid) and the [project summary report](https://ncisvn.nci.nih.gov/svn/docs/trunk/taverna-cagrid/Deliverables/Task1.4-ProjectSummaryReport.pdf).

The work on the caGrid project follows on from caGrid’s previous adoption of Taverna when the Taverna and caGrid collaborated in 2007 to develop a Taverna 1.7.0 GT4 processor as a plugin based upon the Taverna’s WSDL processor. This work has been updated for Taverna 2.1.2, making two plugins were made available: [caGrid plugin](http://www.taverna.org.uk/documentation/taverna-2-x/taverna-2-x-plugins/#cagrid_plugin) (for invoking caGrid services) and [caGrid remote execution plugin](http://www.taverna.org.uk/documentation/taverna-2-x/taverna-2-x-plugins/#cagrid_remote_execution_plugin) (for remote execution of caGrid workflows on a server).

The functionality of the Taverna 1.7.0 caGrid plugin was shown at a caGrid meeting in late 2008 where the associated poster won an outstanding poster award.

## Related publications


Wei Tan, Ravi Madduri, Alexandra Nenadic, Stian Soiland-Reyes, Dinanath Sulakhe, Ian Foster and Carole A Goble (2010):
**CaGrid Workflow Toolkit: A Taverna based workflow tool for cancer grid**
_BMC Bioinformatics_ **11**:542.
[doi:10.1186/1471-2105-11-542](http://dx.doi.org/10.1186/1471-2105-11-542)

Paolo Missier, Stian Soiland-Reyes, Stuart Owen, Wei Tan, Alexandra Nenadic, Ian Dunlop, Alan Williams, Tom Oinn, Carole Goble (2010)
**Taverna, Reloaded**
_Scientific and Statistical Database Management: 22nd International Conference, SSDBM 2010, Heidelberg, Germany, June 30--July 2, 2010. Proceedings_
[doi:10.1007/978-3-642-13818-8_33](http://dx.doi.org/10.1007/978-3-642-13818-8_33)

Alexandra Nenadic, Stian Soiland‐Reyes, Carole Goble (2009):
**Bringing caBIG services together using Taverna**
_UK e‐Science All Hands (AHM) 2009 Conference_, Oxford, UK, 2009.

Wei Tan, Kyle Chard, Dinanath Sulakhe, Ravi Madduri, Ian Foster, Stian Soiland‐Reyes, Carole Goble (2009):
**Scientific workflows as services in caGrid: a Taverna and gRAVI approach**
_IEEE International Conference on Web Services (ICWS 2009)_
[doi:10.1109/ICWS.2009.19](http://dx.doi.org/10.1109/ICWS.2009.19)


Wei Tan, Paolo Missier, Ravi Madduri, Ian Foster (2009):
**Building Scientific Workflow with Taverna and BPEL: A Comparative Study in caGrid**
_ICSOC 2008 International Workshops, Sydney, Australia, December 1st, 2008, Revised Selected Papers_
[doi:10.1007/978-3-642-01247-1_11](http://dx.doi.org/10.1007/978-3-642-01247-1_11)


Wei Tan, Paolo Missier, Ian Foster,  Ravi Madduri, David De Roure, Carole Goble (2009): 
#**A comparison of using Taverna and BPEL in building scientific workflows: the case of caGrid**
[doi:10.1002/cpe.1547](http://dx.doi.org/10.1002/cpe.1547)

#Wei Tan, Ian Foster and Ravi Madduri (2008)
**Combining the Power of Taverna and caGrid: Scientific Workflows that Enable Web-Scale Collaboration**#
_IEEE Internet Computing_ **12**(6).
[doi:10.1109/MIC.2008.120](http://dx.doi.org/10.1109/MIC.2008.120)

Wei Tan, Jia Zhang, Ian Foster (2010):
**Network Analysis of Scientific Workflows: A Gateway to Reuse**
_Computer_ **43**(9)
[doi:10.1109/MC.2010.262](http://dx.doi.org/10.1109/MC.2010.262)
[[pdf]](http://repository.cmu.edu/cgi/viewcontent.cgi?article=1108&context=silicon_valley)


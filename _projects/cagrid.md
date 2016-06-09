---
layout: project
name: cagrid
title: caGrid
path: cagrid.html
collection: projects
description: Support for running cancer-research workflows
logo: https://raw.githubusercontent.com/NCIP/cagrid/master/cagrid/Documentation/general/images/caGrid.png
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

Alexandra Nenadic, Stian Soiland‐Reyes, Carole Goble (2009):
**Bringing caBIG services together using Taverna
_UK e‐Science All Hands (AHM) 2009 Conference_, Oxford, UK, 2009.

Wei Tan, Kyle  hard, Dinanath Sulakhe, Ravi Madduri, Ian Foster, Stian Soiland‐Reyes, Carole Goble (2009):
**Scientific workflows as services in caGrid: a Taverna and gRAVI approach**
__IEEE International Conference on Web Services (ICWS 2009)__

Wei Tan, Ian Foster and Ravi Madduri (2008)
**Combining the Power of Taverna and caGrid: Scientific Workflows that Enable Web-Scale Collaboration**
[doi:10.1109/MIC.2008.120](http://dx.doi.org/10.1109/MIC.2008.120)

---
layout: product
name: taverna
title: Apache Taverna
path: taverna
collection: products
description: Design, editing and execution of scientific workflows
website: https://web.archive.org/web/20200515091110/https://taverna.incubator.apache.org/
logo: /images/logo/apache-taverna.svg
screenshot: /images/screenshots/sm_taverna.png
wiki: https://wikipedia.org/wiki/Apache_Taverna
---

[Apache Taverna (incubating)](https://web.archive.org/web/20200515091110/https://taverna.incubator.apache.org/) (archived)  
was a powerful, scalable, open source & domain independent Workflow Management
System written in Java – a suite of tools used to
design and execute scientific workflows and aid *in silico* experimentation comprising:

 *  **Workbench** (desktop client application)
 *  **Command Line Tool** (for a quick execution of workflows from a terminal)
 *  **Server** (for remote execution of workflows)
 *  **Player** (Web interface plugin for submitting workflows for remote execution written in Ruby on Rails)
 *  **Taverna Online** (for creation of Taverna workflows from a Web browser)

Taverna was used for graphically composing and executing computational
workflows combining diverse sets of WSDL/REST web services, command line tools,
spreadsheets, R scripts and user interactions. 

The core user base of Taverna was in bioinformatics, particularly for combining
public genomics databases with disparate web services, but Taverna was 
[used in many scientific domains](http://web.archive.org/web/20200515113032/https://taverna.incubator.apache.org/introduction/taverna-in-use/) 
such as astronomy, biodiversity, chemistry, data mining and digital preservation.

Developments of Taverna pioneered and experimented in many novel directions for workflow systems, including:

 * Semantic service descriptions
 * Rich structured provenance of workflow executions
 * Interactive user interface
 * Combining multiple grid backends
 * Using fine-structured web services
 * Customizable through a plugin-system
 * Formalization of workflow execution semantics


Often seen as influential for development of scientific workflow systems and
bioinformatics practices, 
[publications about Taverna](http://web.archive.org/web/20200515113741/https://taverna.incubator.apache.org/community/publications)
have received many thousands of citations.

The [Common Workflow Language](/activities/cwl/) is strongly inspired by 
[Taverna's execution semantics](https://www.research.manchester.ac.uk/portal/en/publications/taverna-reloaded(440517ff-a203-495c-88a5-4691ff9c6540).html)
and its formalisations in the [Research Object model](https://doi.org/10.1016/j.websem.2015.01.003)'s `wfdesc`.


## History

### 2020: Taverna Project Retired

> **Note** Taverna is **no longer maintained**, code base is provided for archival purposes.

From 2014 till 2020 the Taverna code base was maintained by the 
[Apache Incubator](https://incubator.apache.org/) project _Apache Taverna (incubating)_
(see [web archive](https://web.archive.org/web/20200312133332/https://taverna.incubator.apache.org/)
and [podling status](https://incubator.apache.org/projects/taverna.html)).

For several successful years, Taverna saw increased developer contributons and
progress towards open development practices and graduation from the Apache
Incubator. Several releases of Apache Taverna modules were made, involving
many new volunteers and Google Summer of Code students. However having no
funded developers seem to have hampered the project, Taverna Workbench 3
did not get released, and activity dwindled to a halt during 2019.

In 2020 the Taverna community
[voted](https://lists.apache.org/thread.html/r559e0dd047103414fbf48a6ce1bac2e17e67504c546300f2751c067c%40%3Cdev.taverna.apache.org%3E)
to **retire** Taverna as a project and withdraw the code base from the Apache Software Foundation. 

This code base remains available under the Apache License 2.0, but is now simply called 
_Taverna_ rather than ~~Apache Taverna (incubating)~~.

While the code base is no longer actively maintained, pull requests
may infrequently be considered by remaining volunteer caretakers.


## 2014: Taverna moves to the Apache Incubator

After almost a decade with development mainly led by the eScience Lab team
at the University of Manchester team, [funded](#funders) by multiple research projects, 
the Taverna community realised the need for moving to an _open development_ model 


In 2014, the Taverna project was [proposed](https://cwiki.apache.org/confluence/display/incubator/TavernaProposal)
to join the [Apache Software Foundation](https://apache.org/)

> Incubation is required of all newly accepted projects until a further review
> indicates that the infrastructure, communications, and decision making process
> have stabilized in a manner consistent with other successful ASF projects.
> While incubation status is not necessarily a reflection of the completeness or
> stability of the code, it does indicate that the project has yet to be fully
> endorsed by the ASF.

Slides:
* [2014-10-30 Taverna as an Apache Incubator project](https://www.slideshare.net/soilandreyes/20141030tavernaincubator) 

## Funders

This is a most likely **incomplete** list of funders that have directly and indirectly
sponsored development of Taverna and the Taverna ecosystem.

* OMII UK
* Engineering and Physical Sciences Research Council (EPSRC):
  * [myGrid](http://web.archive.org/web/20191018145656/http://www.mygrid.org.uk/about-us/) ([GR/R67743/01](https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=GR/R67743/01), [EP/D044324/1](https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/D044324/1), [EP/G026238/1](https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/G026238/1))
  * [e-Research South](https://web.archive.org/web/20140320051520/http://www.eresearchsouth.ac.uk/) 
  * [Software Sustainability Institute](https://www.software.ac.uk/) ([EP/N006410/1](https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/N006410/1))
* Biotechnology and Biological Sciences Research Council (BBSRC)
  * [Ondex](https://sourceforge.net/projects/ondex/) ([BB/F006012/1](https://gtr.ukri.org/projects?ref=BB%2FF006012%2F1)
  * [SynBioChem](http://www.synbiochem.co.uk/) ([BB/M017702/1](https://bbsrc.ukri.org/research/grants-search/AwardDetails/?FundingReference=BB/M017702/1))
  * [BioCatalogue](/products/biocatalogue/), formerly "WS4LS" ([BB/F01046X/1](https://bbsrc.ukri.org/research/grants-search/AwardDetails/?FundingReference=BB/F01046X/1), [BB/F010540/1](https://bbsrc.ukri.org/research/grants-search/AwardDetails/?FundingReference=BB/F010540/1))
* Microsoft Technical Computing Initiative
  * [myExperiment](https://www.myexperiment.org/), "Social Networking for Life Sciences" 
* Economic and Social Research Council (ESRC)
  * [MethodBox](https://methodbox.cs.man.ac.uk/)/[Obesity e-Lab](https://www.research.manchester.ac.uk/portal/en/publications/obesity-elab(4030a506-ba67-495c-981d-5f8f877404b8).html) [ES/F029721/1](https://gtr.ukri.org/projects?ref=ES%2FF029721%2F1), [https://gtr.ukri.org/projects?ref=ES%2FJ010014%2F1](ES/J010014/1)
* Joint Information Systems Committee (JISC)
  * [myExperiment](https://www.myexperiment.org/)
* [EU 7th Framework Programme (FP7)](https://wayback.archive-it.org/12090/20191127213419/https:/ec.europa.eu/research/fp7/index_en.cfm), incl:
  * [BioVeL project](https://web.archive.org/web/20170207093003/http://www.biovel.eu/) ([FP7-INFRASTRUCTURES-2011-2-283359](https://cordis.europa.eu/project/id/283359))
  * [SCAPE project](https://scape-project.eu/) ([FP7-ICT-2009-6-270137](https://cordis.europa.eu/project/id/270137))
  * [Wf4Ever project](http://wf4ever.org/) ([FP7-ICT-2009-6-270192](https://cordis.europa.eu/project/id/270192))
* [EU Horizon 2020 (H2020) programme](https://ec.europa.eu/programmes/horizon2020/)
  * [BioExcel](https://bioexcel.eu/) ([H2020-INFRAEDI-02-2018-823830](https://cordis.europa.eu/project/id/823830), [H2020-EINFRA-2015-1-675728](https://cordis.europa.eu/project/id/675728))
  * [IBISBA](https://ibisba.eu/) ([H2020-INFRAIA-2017-1-730976](https://cordis.europa.eu/project/id/730976), [H2020-INFRADEV-2019-2-871118](https://cordis.europa.eu/project/id/871118))



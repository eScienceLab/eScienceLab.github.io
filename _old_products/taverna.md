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
[Taverna's execution semantics](https://www.research.manchester.ac.uk/portal/en/publications/taverna-reloaded%28440517ff-a203-495c-88a5-4691ff9c6540%29.html)
and its formalisations in the [Research Object model](https://doi.org/10.1016/j.websem.2015.01.003)'s `wfdesc`.


## History

The below timeline has been extracted form the slides [2014-10-30 Taverna as an Apache Incubator project](https://www.slideshare.net/soilandreyes/20141030tavernaincubator):

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

After retirement the code repository will be moved to from
Apache's infrastructure to the [taverna GitHub organisation](https://github.com/taverna).


### 2014-2020: Taverna moves to the Apache Incubator

After almost a decade with development mainly led by the eScience Lab team
at the University of Manchester team, [funded](#funders) by multiple research projects, 
the Taverna community realised the need for moving to an _open development_ model.

The [Apache Software Foundation](https://www.apache.org/) is a non-profit
organization, forming a community of open-source software projects. ASF has a 
strong emphasis on openness, collaboration and a consensus-based development
process.
 
Moving Taverna to ASF aimed to move to fully open development, encourage further developer involvement in core codebase, and remove impression of Univ of Manchester as leader (avoiding "us vs them"-style conversations).

In 2014, the Taverna project was [proposed](https://cwiki.apache.org/confluence/display/incubator/TavernaProposal)
to join the [Apache Software Foundation](https://apache.org/).


The Taverna code base was re-licensed as Apache License 2.0, and all [infrastructure moved to ASF](http://web.archive.org/web/20200515163239/https://taverna.incubator.apache.org/download/code/). 
The [Apache Taverna website](https://web.archive.org/web/20200515113045/https://taverna.incubator.apache.org/)
was adapted for ASF incubator branding, which included this disclaimer:

> Apache Taverna is an effort undergoing incubation at The Apache Software
> Foundation (ASF) sponsored by the Apache Incubator PMC.  Incubation is
> required of all newly accepted projects until a further review
> indicates that the infrastructure, communications, and decision making process
> have stabilized in a manner consistent with other successful ASF projects.
> While incubation status is not necessarily a reflection of the completeness or
> stability of the code, it does indicate that the project has yet to be fully
> endorsed by the ASF.

The reason is that adapting to [The Apache Way](http://theapacheway.com/) 
take some time for a developer community to get used to, and in addition ASF requires
IP governance checks on the donated code, e.g. for license compatibility.

A refreshed Taverna
[community](https://web.archive.org/web/20200515113045/https://taverna.incubator.apache.org/about/) and
Project Management Committee (PMC) was formed to manage the project,
including current, new and former developers of Taverna.  The software was
reshaped into _Apache Taverna (incubating)_ and
several modules were released under the Apache Incubator banner:

* [Apache Taverna Language (incubating)](https://web.archive.org/web/20200515113756/https://taverna.incubator.apache.org/download/language)
* [Apache Taverna OSGi (incubating)](https://web.archive.org/web/20200515113756/https://taverna.incubator.apache.org/download/osgi)
* [Apache Taverna Engine (incubating)](https://web.archive.org/web/20200515113756/https://taverna.incubator.apache.org/download/engine)
* [Apache Taverna Common Activities (incubating)](https://web.archive.org/web/20200515113756/https://taverna.incubator.apache.org/download/common-activities)
* [Apache Taverna Server (incubating)](https://web.archive.org/web/20200515113756/https://taverna.incubator.apache.org/download/server)

These releases remain available at <https://archive.apache.org/dist/incubator/taverna/> and <https://repo.maven.apache.org/maven2/org/apache/taverna/>

During 2019 and 2020 developer activity for Apache Taverna podling went quiet;
with a lack of funding for the developers, this lead to the project
committee voting for retirement from ASF incubator rather than graduating.


### 2012-2020: Taverna 3.x

Development during the Taverna 2.x series highlighted that maintaining our own 
plugin system Raven was becoming a burden. This was powerful and flexible, e.g. 
allowing two different plugins to use incompatible versions of the same Java library, 
but it then also became inflexible to work with the modularized engine and workbench. 


The original intention of Taverna 2 was to allow partial upgrades of individual
modules, to move to a "rolling release" model (e.g. updating only the diagram
code), but in reality, because of cross-dependencies of the different modules, 
difficulties in testing of developer builds, Taverna was always built and
released as a full set of modules.

The `t2flow` format was also seen as a challenge, as it was tied tightly with
the implementing activity modules (serializing their Java configurations 1:1), 
and its XML was overly complex for third-party tools to process or generate 
without loading the full Taverna libraries into the classpath. It was seen as 
important to "liberate" the workflow definition file format from the Taverna
implementation.

Therefore it was decided to develop a new "abstracted" file format called
[SCUFL2](https://www.research.manchester.ac.uk/portal/en/publications/scufl2--because-a-workflow-is-more-than-its-definition%48065016ed-9e6e-45d9-a364-3777c258bde3%49.html)
that standarized the definition using a combination of XML Schemas and
ontologies, having a separate SCUFL2 Java API (later Taverna Language). 
 
Replacing the custom Raven plugin system, Taverna 3.x was planned to move to 
the industry-standard dynamic module system [OSGi](https://www.osgi.org/), with
a clearer separation between internal API interfaces and their implementations.
The level of indirection offered by OSGi was envisioned to avoid the "spaghetti
dependencies" previously encountered, but meant a change in how third-party 
developers would make plugins available for Taverna.

The previous Taverna 2.x Commandline had been made as "Workbench without the
GUI" and was therefore still loading many components not used during workflow
execution, e.g. service discovery. The Taverna 2 workbench was tightly bound 
to the `t2core` engine, e.g. for providing progress while execution, but this 
meant it could not be easily switched to remote execution. The Taverna 2.x
Server was also in effect a REST API that executed the Taverna 2.x command line, 
and thus had no access to the workflow state while it was running.

To support many ways of remote execution, and alternate integration of the
engine from other applications (e.g. from KNIME), the 
engine was separated to a new independent module called _Taverna Platform_, 
which provided a higher-level API that also exposed detailed provenance
information of the current state. Using OSGi this was intended for connecting 
the desktop workbench to Taverna Engine runnning on remote servers.

The refactored Taverna engine and Taverna 3.0 prototypes became the basis for
the code base that was donated to Apache Taverna.

Notable [Taverna 3.x releases](https://web.archive.org/web/20191023010907/http://www.taverna.org.uk/developers/work-in-progress/taverna-3/):

* Version 3.0.a1 (2013): first alpha-release workbench
* Version 3.0.a2 (2013): separated engine, command line and workbench with separate plugins

### 2007-2014: Taverna 2.x

The first adapted releases of Taverna 2.0 using `t2core` were released in early
alpha/beta releases to be tested by selected users, before the official 2.1
workbench was released. 

The workflow fileformat was changed from the FreeFluo SCUFL XML to a new
`t2flow` XML format that serialized the `t2core` layers, supporting the 
extensible and configurable [Taverna 2 execution semantics](https://www.research.manchester.ac.uk/portal/en/publications/taverna-reloaded%28440517ff-a203-495c-88a5-4691ff9c6540%29.html). 

Code maintenance was improved by moving from SourceForge CVS to GoogleCode SVN,
supporting better larger refactoring. The code was modularized into different
Maven subprojects to support partial releases and upgrades, utillizing the
Raven plugin system also for Taverna's internals, e.g. user interface and
activity plugins. 

Releases increased in number and size, with installers and JVM for multiple
operating systems and domains. The [releases were moved](https://software.ac.uk/blog/2016-10-03-thinking-about-migrating-different-repository) 
from [SourceForge](https://sourceforge.net/projects/taverna/files/), 
[Google
Code](https://web.archive.org/web/20120605122802/http://code.google.com/p/taverna/downloads/list)
(archived), [BitBucket](https://bitbucket.org/taverna/) and
[Launchpad](https://launchpad.net/taverna).  As Google Code was decommissioned,
source code was moved from a big single [SVN
tree](https://github.com/taverna/taverna-svn) to multiple git [repositories on
GitHub](https://github.com/taverna).

Focus on third-party developers was increased, providing documentation and examples, 
a (perhaps too) flexible plugin system, and extensible user-interface. This
welcomed multiple extensions, e.g. additional file format, integrations with
[myExperiment](https://www.myexperiment.org/home) for workflow discovery 
and [BioCatalogue](/products/biocatalogue/) for service discovery. Plugins
could be installed and loaded on the fly from multiple web-sites, based on
[Maven repositories](http://www.mygrid.org.uk/maven/repository/). 

New additional domain-specific activity types were added and extended, and the
focus changed from Taverna as a bioinformatics-specific workbench to a generic
tool composition platform, for instance for astronomy in _Wf4Ever_, 
biodiversity in _BioVeL_ and digital preservation in _SCAPE_.

[Provenance support](https://doi.org/10.1007/978-3-642-17819-1_16) was
reintroduced for Taverna 2; a tighter integration into the t2core engine
allowed fine-grained tracing of workflow executions, e.g. inspection of
intermediate values and individual start/stop times for step iterations. 
Provenance could be exported in RDF format according to the
[Open Provenance Model](https://openprovenance.org/opm/) (OPM), and later with
[Taverna-PROV](https://www.research.manchester.ac.uk/portal/en/publications/tracking-workflow-execution-with-tavernaprov%2826c40ab9-d80e-48d5-898c-d80e462762f0%29.html)
as [Research Objects](http://www.researchobject.org/) 
using [W3C PROV](http://www.w3.org/TR/prov-overview/). Taverna developers were
active in shaping the PROV standard and Research Object model based on
experience within the Wf4Ever project and the myExperiment workflow repository.

Support for executing arbitrary command line tools were added to Taverna, as
well as making Taverna workflows themselves executable on the command line and
through a Taverna Server REST API. This was fully utillized in projects like
[BioVel](https://doi.org/10.1186/s12898-016-0103-y), where a 
web portal allowed user-driven execution of "hidden" Taverna workflows
with interactive steps to steer the execution.


Notable [Taverna 2.x releases](https://web.archive.org/web/20191030201309/http://www.taverna.org.uk/download/workbench/):

* Version 2.0 (2008): t2core workflow engine,  Reimplemented pluggable workbench.
* Version 2.1.2 (2009) Improved support for 3rd-party plugins
* Version 2.2 (2010) Taverna Server + ruby gem. 
* Version 2.5 (2014) Domain-specific editions (astronomy, bioinformatics, biodiversity, digital preservation). Taverna-PROV.



### 2006-2009: Productizing

From 2006, with funding for the _myGrid platform_ and _OMII-UK_, the myGrid group
in Mancester grew with several developers to productize the previous Taverna
workbench, which had already seen a big uptake by bioinformatics users who were
raising requirements for usability, extensibility and functionalities.

Internally several code refactorings were also due to support plugins, to
improve the build/test/release cycle, and to provide installers for desktop
users.

Notable [Taverna 1.x releases](https://sourceforge.net/projects/taverna/files/taverna/):

* Version 1.4 (2006): Apache Maven-based build, executeworkflow command line
* Version 1.5 (2006): Raven plugin system
* Version 1.7 (2008): Taverna Remote Execution Service

During this time it also become evident that relying on the Freefluo workflow
engine, now no longer actively maintained by Southampton developers, hampered
Taverna's future directions. To support better concurrency, efficiency and tighter workflow
engine integration and logging, work began on the `t2core` workflow engine,
which was designed by Tom Oinn at EMBL-EBI and Matt Hancock, and
prototyped by the Manchester team.

The [website taverna.org.uk](http://web.archive.org/web/20200515163406/http://www.taverna.org.uk/documentation/taverna-2-x/)
was established, with extensive documentation and training materials created.
The myGrid team provided Taverna training for bioinformaticians at many
international events and summer schools.


### 2001-2006: Prototyping

In 2001 the _myGrid_ consortium was formed from 6 academic institutions and 8 industry partners.
Their challenge: Create a graphical workbench for bioinformaticians to combine data and web services.

Part of the conceived 
[myGrid workbench](https://www.research.manchester.ac.uk/portal/en/publications/the-mygrid-project%28c7382096-7d8c-4e68-a991-82e09f537139%29.html)
was the _Taverna Workbench_ for building workflows. Taverna was seen as
participating in the _Semantic Web_, other parts of myGrid included catalogues
of semantic service descriptions (discovered by Taverna), wrapped
bioinformatics web services (which Taverna called), FreeFluo workflow enactment
(which Taverna used for execution), OGSA-DAI distributed queries and the myGrid
Information Repository (mIR) storing workflow definitions, projects and data with
semantic metadata.



Notable [Taverna Workbench prototype releases](https://sourceforge.net/projects/taverna/files/taverna/):

 * Version 0.1 beta (2003-2004): First Taverna Scufl workbench
 * Version 1.0 (2005): First stable release, using FreeFluo
 * Version 1.3 (2005): Production-ready release

Taverna was developed as Open Source software from the beginning, licensed as
LGPL 2.1.  Source and binary releases were kept on SourceForge.net, the source
code was initially kept on University of Manchester CSV servers before moving
to [CSV on SourceForge](https://sourceforge.net/p/taverna/code/).


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
  * [MethodBox](https://methodbox.cs.man.ac.uk/)/[Obesity e-Lab](https://www.research.manchester.ac.uk/portal/en/publications/obesity-elab%284030a506-ba67-495c-981d-5f8f877404b8%29.html) [ES/F029721/1](https://gtr.ukri.org/projects?ref=ES%2FF029721%2F1), [https://gtr.ukri.org/projects?ref=ES%2FJ010014%2F1](ES/J010014/1)
* Joint Information Systems Committee (JISC)
  * [myExperiment](https://www.myexperiment.org/)
* [EU 7th Framework Programme (FP7)](https://wayback.archive-it.org/12090/20191127213419/https:/ec.europa.eu/research/fp7/index_en.cfm), incl:
  * [BioVeL project](https://web.archive.org/web/20170207093003/http://www.biovel.eu/) ([FP7-INFRASTRUCTURES-2011-2-283359](https://cordis.europa.eu/project/id/283359))
  * [SCAPE project](https://scape-project.eu/) ([FP7-ICT-2009-6-270137](https://cordis.europa.eu/project/id/270137))
  * [Wf4Ever project](http://wf4ever.org/) ([FP7-ICT-2009-6-270192](https://cordis.europa.eu/project/id/270192))
* [EU Horizon 2020 (H2020) programme](https://ec.europa.eu/programmes/horizon2020/)
  * [BioExcel](https://bioexcel.eu/) ([H2020-INFRAEDI-02-2018-823830](https://cordis.europa.eu/project/id/823830), [H2020-EINFRA-2015-1-675728](https://cordis.europa.eu/project/id/675728))
  * [IBISBA](https://ibisba.eu/) ([H2020-INFRAIA-2017-1-730976](https://cordis.europa.eu/project/id/730976), [H2020-INFRADEV-2019-2-871118](https://cordis.europa.eu/project/id/871118))



# __CHAOSS Whitepaper__
 --front matter--

Title: CHAOSS Whitepaper v1.0

Editors: Georg Link and Matt Germonprez

Release date: tbd

Cute image on title page

Logos: LF, CHAOSS, GrimoireLab, Cregit, GHData, Prospector (treat as sponsors)

__CHAOSS Contributors:__

First attempt at capturing who is involved.
Sources of names are the Metrics and Software mailing lists and all CHAOSS repositories on GitHub.
Names are listed in alphabetical order.

Alberto Martín,
Alberto Pérez García-Plaza,
Alexander Serebrenik,
Alvaro del Castillo,
Augustina Ragwitz,
Ben Lloyd Pearson,
Ben Nickolls,
Boris Baldassari,
Brian Proffitt,
Daniel Izquierdo,
David A. Wheeler,
Derek A. Howard,
Don Marti,
Emma Irwin,
Fil Maj,
Georg Link,
Gil Yehuda,
Harish Pillay,
Henri Yandell
Henrik Mitsch,
Ildiko Vancsa,
Jason Clark,
Javier Luis Cánovas Izquierdo,
Jeremiah Foster,
Jesus M. Gonzalez-Barahona,
Jonathan Lipps,
Jordi Cabot,
Kate Stewart,
Kevin Lumbard,
Lawrence Hecht,
Luis Cañas-Díaz,
Manrique Lopez,
Matt Germonprez,
Michael Downey,
Neil Chue Hong,
Nikki Stevens,
Peter Monks,
Rashmi Chitrakar,
Raymond Paik,
Rich Bodo,
Santiago Dueñas,
Sean Goggins,
Shane Curcuru,
Shilla Saebi,
Thanh Ha,
Tom Mens,
Vicky Janicki

# Executive Summary
 --key takeaways (contributions)--

- 1 Paragraph on community health (start with conclusion)
- 1 Paragraph with metrics and development history
- 1 Paragraph with software and development history
- 1 Paragraph with use cases and future work

# Table of Content
 --headings (pdf: with page numbers)--


# 1. CHAOSS Background

The Linux Foundation Community Health Analytics Open Source Software (CHAOSS)
community was created in response to current trends in the open source ecosystem.

## 1.1 Current Status of the Open Source Ecosystem

Open source ecosystem is growing. More lines of code are licensed open source
every year. More developers participate in open source every year.
More companies engaged open source every year.

Open source is becoming professional. Organizations are increasingly relying on
open source software for their internal software development and innovation.
Open source enables rapid innovation.

Open source is becoming the default for new software. Internally developed
software is frequently released as open source to enhance adoption and
involve users in the development process.

Open source is becoming a model for shared standards development. New
technologies are innovated within open source to ensure equal access
for everyone. Organizations benefit from engaging in open source standards
development by learning from each other and helping the standard align with
their own practices.

### 1.1.1 Stakeholders and Their Pain Points

The four main stakeholders in open source---members, communities, companies,
and foundations--- suffer from different pain points.

#### 1.1.1.1 Open Source Members

Open source members can be volunteers or be employed to work
on specific open source projects.

Open source members face the following issues:

  - large workload, sense of duty, burnout
  - don't know where to put efforts
      - within their own projects
      - or when looking for a new project
  - don't get paid, unless employed
  - don't see the impact they are making (needed for performance evaluations)
  - ...

#### 1.1.1.2 Open Source Communities

Open source communities are the place where conversation around specific
open source projects occur, including development activity and support.

Open source communities face the following issues:

  - attract new members and organizations
  - ensure consistent quality
  - reward valuable members
  - ...

#### 1.1.1.3 Open Source Companies

An open source company is any company that engages in open source.
Engagement include using open source internally,
providing services for open source software,
sending employees to participate in open source communities,
and sponsoring open source communities.

Open source companies face the following issues:
  - which open source software to engage with ?
  - communicate the impact the organization has on the community
  - determine the value derived from engaging with open source
  - evaluate the work of their employees within open source
  - ...

#### 1.1.1.4 Open Source Foundations

Open source foundations provide stability for open source communities, through
legal advice, managing assets, hosting infrastructure, and organizing events.

Open source foundations face the following issues:
  - identifying and responding to community needs
  - evaluating the impact of their work
  - promoting communities
  - ...

## 1.2 History of CHAOSS community

TODO: create image with time-line and events

  - February 2017 - Open Source Leadership Summit unconference on community health
  - September 2017 - Launch at Open Source Summit North America
      - Keynote
      - Presentation
      - Birds-of-a-feather
      - Workshop
  - October 2017 - Open Source Summit Europe
  - February 2018 - CHAOSScon + GrimoireCon Europe 2018 at FOSDEM by Bitergia
  - March 2018 - Open Source Leadership Summit
      - Several talks: TBA

## 1.3 Structure of CHAOSS community
 --committees, working groups, meetings,



### 1.3.1 Software Committee
Goal: ...

Ongoing Projects: ...

Communication Channels: ...

### 1.3.2 Metric Committee
Goal: ...

Ongoing Projects: ...

Communication Channels: ...


## 1.4 CHAOSScon
 --Goal and purpose of CHAOSScon--
 --program of 2018--
 --report from CHAOSScon--


# 2. CHAOSS Software
The CHAOSS Software committee maintains several projects that explicate community health metrics. The following section introduces the four founding projects.

## 2.1 GrimoireLab

GrimoireLab is a set of free, open source software tools for software development analytics. They gather data from many systems supporting development (git, GitHub, Jira, Bugzilla, Gerrit, mailing lists, Jenkins, Slack, Discourse, Confluence, StackOverflow, etc), merge and organize it in a database, and produce visualizations, actionable dashboards, and analytics of all of it.  GrimoireLab is focused on analyzing activity, community and processes, but can be easy tailored for other aims. They can also be easily integrated with other tools.

__More Information:__

- GrimoireLab Website → https://grimoirelab.github.io
- GrimoireLab Code → https://github.com/grimoirelab
- GrimoireLab eating GrimoireLab → http://grimoirelab.biterg.io
- GrimoireLab Tutorial → https://grimoirelab.gitbooks.io/grimoirelab-training

## 2.2 Prospector

Prospector is a tool for automated collection and continuous tracking of a wide range of metrics of open source projects useful in evaluating the health and trends of projects. Red Hat open sourced Prospector under GPLv3 as part of the launch of CHAOSS.

__More Information:__

- Prospector Code → https://github.com/chaoss/prospector
- Prospector Live Proof of Concept → http://prospector.bitergia.net

## 2.3 GHData

GHData is a Python library and REST server that provides data related
to GitHub repositories. For providing its functionality, it consumes
data from the GHTorrent dataset.

GHData has been in use by several people from the CHAOSS Metrics TC for
a while, and many of the metrics designed by them are implemented, as a
proof of concept, by GHTorrent. Because of this history, it seems
natural to consider GHTorrent as one of the founding projects of the
CHAOSS Software TC. We also expect that it helps to bridge the gap
between both CHAOSS committees. To work in this direction, we will
explore how to integrate it with GrimoireLab (likely by building a
Perceval connector for it) and other projects in the Software TC.

__More Information:__

- GHData Code  →  https://github.com/OSSHealth/ghdata

## 2.4 Cregit

Cregit is a framework of tools that facilitates the analysis and visualization
of the evolution of source code stored in git repositories.

__More Information:__

- Cregit Code → https://github.com/cregit
- Cregit applied to Linux → https://cregit.linuxsources.org/


# 3. CHAOSS Metrics v1.0

The CHAOSS project is proud to release the CHAOSS metrics in version 1.0.

__Background:__ The activity metrics have been identified based on workshops at the Open Source Leadership and the Open Source Summit North America. In addition, the activity metrics are based on active CHAOSS mailing list conversations. The activity metrics listed here are the result of compiling the discussions to data. We thank everyone who participated.

__Tooling:__ The activity metrics are intended to be a starting point for community health related tooling. It is expected that the activity metrics will evolve based on the ability (or inability) of tooling to successfully implement the activity metrics.

## 3.1 Diversity and Participation

Activity Metric | Description
--- | ---
New Contributors* vs Maintainers** | Ratio of new contributors to maintainers over time
Contributor Demographics | Gender, age, location, education, and skills over time
Leadership Demographics | Demographics of project's leadership (e.g. Board, Technical Steering Committee, Maintainers, etc.) over time
New Contributor Organizations | New organizations contributing to the project over time
Number of Contributing Organizations | Number of organizations participating in the project over time
New Contributions | Percentage of contributions (patches, pull requests, etc.) from new contributors vs all accepted contributions over time
Accepted Code Contributions | Percentage of new contributor code versus total code over time
Path to Maintainership | Path to maintainership published
Maintainer Promotion | Last time a maintainer was added
Change in Maintainer Number | Number of maintainers added/removed over time

 * Contributor = Anyone who provides a patch, pull request, wiki change, or other contribution.
 ** Maintainer = Contributor who has commit rights to the main branch and can merge contributions from others.

## 3.2 Growth-Maturity-Decline

### Issue Resolution

Activity Metric | Description
--- | ---
Open issues | Total number of open issues.
Closed issues | Total number of closed issues.
Resolution efficiency | Number of closed issues / number of abandoned issues.
Average time of open issues | The average amount of time open issues have remained open.
Percentile distribution of open issue time | Proportional frequency of open issue time duration.
Average issue resolution time | The average amount of time it takes for issues to be closed.
Percentile distribution of issue resolution time | Proportional frequency of closed issue time duration.
Average time of first response to issue | The average amount of time it takes for the first response to an issue.
Percentile distribution of first response time | The proportional frequency of time it takes for the first response to an issue.

### Code Development

Activity Metric | Description
--- | ---
Number of commits | Total number of commits.
Number of lines changed | Total number of lines of code that have been changed.
Average time to merge code | The average amount of time difference between code author and commit dates.
Percentile distribution of time to merge code |Proportional frequency of code merge to upstream time duration.
Review efficiency | Number of merged patches / number of abandoned patches over a set period of time.
Average time of first maintainer response to code merge request | The average amount of time it takes for a maintainer to make the first response to a code merge request.
Percentile distribution of first maintainer response to code merge request | The proportional frequency of time it takes for a maintainer to make the first response to a code merge request.

### Community Growth

Activity Metric | Description
--- | ---
Total contributors | The total number of contributors over time on any platform.
Total new contributors | The total number of new contributors over time on any platform.
Total contributing organizations | The total number of organizations contributing over time
Total new contributing organizations | The total number of new organizations contributing over time.
Total (sub)projects | The total number of (sub)projects over time.


## 3.3 Risk

Activity Metric | Description
--- | ---
Contributor Importance | Percentage of commits by individual contributors from identified organizations over time
Qualified Committers | Contributions over time and what components they commit to over time
User Dependency | Number of users who are aware that they depend on the software over time
Paid developers | Number of paid developers in community over time

## 3.4 Dependency

Activity Metric | Description
--- | ---
 ... | ...
 ... | ...
 ... | ...

## 3.5 Value

Activity Metric | Description
--- | ---
Development Cost | An estimate of the market cost to develop the functionality of the project.  See [OpenHub](https://blog.openhub.net/project_codebase_cost/), for example
Software Downloads | Number of project software downloads
Downloads of non-SW artifacts | Number of downloads of non-software artifacts (e.g. documentation, sample apps, test suites, etc.)
Installs | Number of software installations of the project
Number of active users | Number of "active" users of the project (for some yet-to-be-defined definition of "active")
Commercial offerings | Availability of commercial products or services based on the project
Availability of add-on products | Availability of 3rd party plug-ins, modules, utilities, etc. that provide additional functionality for the project's software


# 4. Community Health
 --define community health--

## 4.1 Success story of using metrics for health
 --advertise for our work--

### 4.1.1 Velocity
One example for using metrics to understand community health is through the
concept of velocity---level of activity and size of a community.
Velocity does not constitute a new metric but shows how metrics can be
combined and interpreted to inform community health.

https://www.cncf.io/blog/2017/06/05/30-highest-velocity-open-source-projects/

## 4.2 Where metrics fall apart
 --cautionary tale for using metrics--
 People gaming metrics
 Metrics used for marketing purposes
 Too much focus on code contributions
 Using metrics to make comparisons between very different open source projects (e.g. with different maturity-level, industry, culture, etc.)
 Ignoring non-metrics

## 4.3 Diversity and Inclusion Report
  --Daniel's work--

## 4.4 Ongoing Initiatives
  --health initiatives outside of CHAOSS--


# 5. Our Own Metrics
 --CHAOSS metrics applied to the CHAOSS community--

# 6. FAQ

## 6.1 How do the Metrics help me understand whether an open source project is healthy?
CHAOSS provides standardized metrics that uniformly generate information about open source projects. You can use these metrics to see changes in your project that might indicate changes in project health. You can also use these metrics to compare your project to similiar projects. We will not offer an opinion about the health of any project but provide objective measures that can help you make an informed decision.

## 6.2 Will you create a project health index?
No, open source projects work very differently and we believe that a single index will not do this diversity justice. Our approach, rather, is to provide a collection of standardized metrics that can inform your personal opinion about project health.

## 6.3 What do you mean with 'implementation-agnostic metrics'?
Our goal is to define metrics independent of a specific implementation.

## 6.4 What are the IP or commitments that contributing members are making to make sure that the derived IP is patent free and distributed under an open source license.
Our goal is to make our innovations available to everyone to use for free. We honor open source licenses of upstream projects. We license our own innovations under the GPLv2+ or MIT open source license. We only accept patent free contributions or where patent licenses are available for free.

---
layout: full-width
title: GSoC 2025 Ideas
tags: gsoc
permalink: /initiatives/gsoc/gsoc2025ideas
---

# {{page.title}}

[Bug Logging Tool (BLT)](#bug-logging-tool-blt) &bull;  [Juice Shop](#owaspjuiceshop) &bull; [DevSecOps Maturity Model](#owaspdevsecops-maturity-model) &bull; [OWASP OWTF](#owasp-owtf) &bull; [OWASP secureCodeBox](#owasp-securecodebox) &bull; [OWASP Nettacker](#owasp-nettacker) &bull; [OWASP Website](#owasp-website) &bull; [OWASP Nest](#owasp-nest)


<!-- Template: Use a format like below to add your project, don't forget to add it to the anchor links above:
### [Project Name]

##### Explanation of Ideas

![Preferred for "Medium" GSoC 2025 project](https://img.shields.io/badge/medium%20size%20(~175h)-preferred-green)
![Possible for "Medium" GSoC 2025 project](https://img.shields.io/badge/medium%20size%20(~175h)-possible-yellow)
![Not recommended for "Medium" GSoC 2025 project](https://img.shields.io/badge/medium%20size%20(~175h)-not%20recommended-red)

![Preferred for "Large" GSoC 2025 project](https://img.shields.io/badge/large%20size%20(~350h)-preferred-green)
![Possible for "Large" GSoC 2025 project](https://img.shields.io/badge/large%20size%20(~350h)-possible-yellow)
![Not recommended for "Large" GSoC 2025 project](https://img.shields.io/badge/large%20size%20(~350h)-not%20recommended-red)

![Difficulty: Easy](https://img.shields.io/badge/difficulty-easy-green)
![Difficulty: Medium](https://img.shields.io/badge/difficulty-medium-orange)
![Difficulty: Hard](https://img.shields.io/badge/difficulty-hard-red)

##### Expected Results

##### Getting Started

##### Mentors
-->

Tips to get you started in no particular order:
- Read the
  [Student Guidelines](gsoc2025).
- Check our
  [GitHub organization](https://github.com/OWASP).
- Contact one of the project mentors below.

## List of Project Ideas

### [Bug Logging Tool (BLT)](https://owasp.org/www-project-bug-logging-tool/)

OWASP BLT is a _bug-hunting & logging_ tool which allows users and companies to hunt for bugs, claim bug bounties and also to start bug-hunting sprees/contests respectively. It is preferred if the potential GSoC contributors get at least 5 PRs merged for the project. Preference will be given to students
who get the most work done, and this is usually by submitting the most PRs.

##### 2025 GSOC Ideas / Projects

Check our Github for now here: https://github.com/OWASP-BLT/BLT/milestones we will be adding some new projects specifically for GSOC on this page soon.


#### Expected Results

* We would expect that any projects you choose to include in your proposal are fully completed.


#### Knowledge Prerequisites

* Python / Django for Backend
* Flutter for Mobile app
* Blockchain development
* UI / UX design

##### Mentors
* Donnie (@DonnieBLT on Slack) -- lead mentor
* Yash Pandey
* looking for 10 mentors this year (if you are knowledgeable in any of the prerequisites and can review PRs, you can watch any of our videos https://blt.owasp.org/bltv/ and be up to speed and ready to mentor)

### [OWASP Juice Shop](https://owasp-juice.shop)

OWASP Juice Shop is probably the most modern and sophisticated insecure
web application! It can be used in security trainings, awareness demos,
CTFs and as a guinea pig for security tools! Juice Shop encompasses
vulnerabilities from the entire OWASP Top Ten along with many other
security flaws found in real-world applications!

To receive early feedback please:
- put your proposal on Google Docs and submit it to the OWASP
  Organization on Google's GSoC page in "Draft Shared" mode.
- Please pick "juice shop" as Proposal Tag to make them easier to find
  for us. Thank you!

##### Explanation of Ideas 

###### Test Suite Harmonization

![Preferred for "Medium" GSoC 2025 project](https://img.shields.io/badge/medium%20size%20(~175h)-preferred-green)
![Not recommended for "Large" GSoC 2025 project](https://img.shields.io/badge/large%20size%20(~175h)-not%20recommended-red)

![Difficulty: Easy](https://img.shields.io/badge/difficulty-easy-green)

Juice Shop had a full replacement of its end-to-end test suite - from Protractor to Cypress - in its GSoC 2022 project. Now it is time to take on the remainin test suites, especially the Integration/API tests currently running on Frisby.js. That library as not seen updates in 2+ years and it became more and more flaky over the years, causing occasional CI/CD failures and time-consuming retry-mechanisms to keep those in check. A new foundation for these tests is needed. In scope is also to look at the frontend and backend unit test suites, and find a way to reduce the number of test frameworks being used in order to achieve higher consistency and less complexity for maintenance of the project.

###### Juice Shop CTF Tool Rennovation

![Preferred for "Medium" GSoC 2025 project](https://img.shields.io/badge/medium%20size%20(~175h)-preferred-green)
![Not recommended for "Large" GSoC 2025 project](https://img.shields.io/badge/large%20size%20(~175h)-not%20recommended-red)

![Difficulty: Easy](https://img.shields.io/badge/difficulty-easy-green)

The Juice Shop CTF Tool is currently implemented in vanilla JavaScript. It should be migrated to TypeScript for consistency of maintenance with the main project. Furthermore, the code linting should be adapted to the main Juice Shop ESLint standards. Test coverage and relevance should be reviewed and strengthened where necessary. 

###### Your own idea

![Preferred for "Medium" GSoC 2025 project](https://img.shields.io/badge/medium%20size%20(~175h)-preferred-green)
![Preferred for "Large" GSoC 2025 project](https://img.shields.io/badge/large%20size%20(~350h)-preferred-green)

![Difficulty: Easy](https://img.shields.io/badge/difficulty-easy-green)
![Difficulty: Medium](https://img.shields.io/badge/difficulty-medium-orange)
![Difficulty: Hard](https://img.shields.io/badge/difficulty-hard-red)

You have an awesome idea to improve OWASP Juice Shop that is not on this
list? Great, please submit it!

##### Expected Results

* A new feature or improvement of an existing one that makes OWASP Juice
  Shop even better
* Your code follows our existing styleguides and passes all existing
  quality gates regarding code smells, test coverage etc.
* Code that you write comes with automated tests that fit into
  [our available test suites](https://pwning.owasp-juice.shop/companion-guide/latest/part3/contribution.html#_testing).

##### Getting started

* Make sure your JavaScript/TypeScript is sufficient to work on the
  Juice Shop codebase. Check our
  [Codebase 101](https://pwning.owasp-juice.shop/companion-guide/latest/part3/codebase.html)
  here. Students with some experience with (or willingness to learn)
  Angular and NodeJS/Express are usually prefered.
* Read our
  [Contribution Guidelines](https://pwning.owasp-juice.shop/companion-guide/latest/part3/contribution.html)
  very carefully. Best make some small contributions before GSoC, so we
  can see how you work and help you dive into the code even better.
* Get in touch with
  [Bjoern Kimminich](mailto:bjoern.kimminich@owasp.org) to discuss any
  of the listed or your own idea for GSoC!

##### Mentors

* [Bjoern Kimminich](mailto:bjoern.kimminich@owasp.org) - OWASP Juice
  Shop Project Leader
* [Shubham Palriwala](mailto:spalriwalau@gmail.com) - OWASP Juice Shop Core Team
* [Jannik Hollenbach](mailto:jannik.hollenbach@owasp.org) - OWASP Juice Shop Core Team

### [OWASP DevSecOps Maturity Model](https://dsomm.owasp.org)

Join us in enhancing the DSOMM, a pivotal tool designed to improve the security and operational efficiency of software development processes. We are looking for passionate students to contribute to two major areas: our main application development in JavaScript and our metric analyzer and collector in Java. Whether you are looking to tackle medium-sized challenges or are ready to embark on a larger project, we have exciting opportunities for you.

To receive early feedback please:
- put your proposal on Google Docs and submit it to the OWASP
  Organization on Google's GSoC page in "Draft Shared" mode.
- Please pick "dsomm" as Proposal Tag to make them easier to find
  for us. Thank you!

##### Medium Feature Pack for the DSOMM Main Application (JS)
![Preferred for "Medium" GSoC 2025 project](https://img.shields.io/badge/medium%20size%20(~175h)-preferred-green)
This pack includes tasks that are crucial for enhancing the user experience and functionality of the DSOMM main application. Contributors will address existing issues and add new features:
- Implement a **State or Tag for "Not yet assessed"**, addressing [Issue #241](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/issues/241) ![Difficulty: Easy](https://img.shields.io/badge/difficulty-easy-green)
- Enhance the **Excel download feature in "Mapping"** by adding assessment information, as discussed in [Issue #244](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/issues/244#issuecomment-1811127472) ![Difficulty: Easy](https://img.shields.io/badge/difficulty-easy-green)
- Refine the handling of **subcategories** to streamline the organization and presentation of maturity model elements, making the tool more intuitive. See [Issue #194](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/issues/194) ![Difficulty: Medium](https://img.shields.io/badge/difficulty-medium-orange)
- Introduce the **Adding of Diagrams** feature to enhance the visualization of DevSecOps processes and maturity levels, as outlined in [Issue #183](https://github.com/devsecopsmaturitymodel/DevSecOps-MaturityModel/issues/183) ![Difficulty: Medium](https://img.shields.io/badge/difficulty-medium-orange)
- **Your Idea:** Proposals that innovate or enhance the metric collection and analysis process are highly encouraged.

##### Large Feature Pack for the metric Analyzer and Collector (Java)
![Preferred for "Large" GSoC 2025 project](https://img.shields.io/badge/medium%20size%20(~175h)-possible-yellow)
This pack challenges students to develop the entire workflow from data collection to visualization for DSOMM metrics, including the implementation of a Kafka queue. Projects include:
- Design and implement a **collector for OWASP DefectDojo**, fetching Mean Time to Resolve (MTTR) and Mean Time to Patch (MTTP) via the [defectdjo-client](https://github.com/SDA-SE/defectdojo-client) which fetches MTTR/MTTP) ![Difficulty: Easy](https://img.shields.io/badge/difficulty-easy-green)
- Develop a **collector for Confluence**, to retrieve essential documents such as threat modeling and pentest reports, with a focus on document management and identification. ![Difficulty: Medium](https://img.shields.io/badge/difficulty-medium-orange)
- Engineer a **collector for GitHub**, to calculate MTTP by tracking pull request opening and merge dates. In addition, check that _branch protection_ is enabled and a .gitignore exists in the root file system. ![Difficulty: Medium](https://img.shields.io/badge/difficulty-medium-orange)
- **Your Idea:** Proposals that innovate or enhance the metric collection and analysis process are highly encouraged.

##### Large Feature Pack for the metric Analyzer and Collector (Java)
![Preferred for "Large" GSoC 2025 project](https://img.shields.io/badge/large%20size%20(~350h)-preferred-green)
This pack challenges students to develop the entire workflow from data collection to visualization for DSOMM metrics, including the implementation of a Kafka queue. Projects include:
- Design and implement a **collector for OWASP DefectDojo**, fetching Mean Time to Resolve (MTTR) and Mean Time to Patch (MTTP) via the [defectdjo-client](https://github.com/SDA-SE/defectdojo-client) which fetches MTTR/MTTP) ![Difficulty: Easy](https://img.shields.io/badge/difficulty-easy-green)
- Develop a **collector for Backstage, Jira and Confluence**, to retrieve essential documents such as threat modeling and pentest reports, with a focus on document management and identification. ![Difficulty: Medium](https://img.shields.io/badge/difficulty-medium-orange)
- Create a **collector for Jenkins**, aimed at measuring deployment frequency by team, a key metric in DevOps performance. ![Difficulty: Medium](https://img.shields.io/badge/difficulty-medium-orange)
- Engineer a **collector for GitHub**, to calculate MTTP by tracking pull request opening and merge dates. In addition, check that _branch protection_ is enabled and a .gitignore exists in the root file system. ![Difficulty: Medium](https://img.shields.io/badge/difficulty-medium-orange)
- Engineer a **collector for Dependency Track**, fetching Mean Time to Resolve (MTTR) and Mean Time to Patch (MTTP) ![Difficulty: Medium](https://img.shields.io/badge/difficulty-medium-orange)
- **Your Idea:** Proposals that innovate or enhance the metric collection and analysis process are highly encouraged.

Please take a look at the [architecture digram of DSOMM metricCA](https://github.com/devsecopsmaturitymodel/metricCA). The whole way from the collector to grafana needs to be implemented. Please note that a queue Kafka and Prometheus is currently not implemented and needs to be implemented in the collector and in the metricAnalyzer.

For Backstage, Jira and Confluence a defined format and tags might be used to identify the corresponding team and type of document (e.g. threat modeling/pentest).

#### Prerequisites
- Proficiency in the corresponding programming language (JavaScript for the main application, Java for the metric analyzer and collector)
- Previous contributions to open-source projects are highly desirable, demonstrating your commitment and collaborative skills

##### Mentors
Reach out to us on Slack to discuss these and other ideas!

- [Timo Pagel](mailto:timo.pagel@owasp.org)
- [Aryan Prasad](mailto:aryan.prasad@owasp.org)

### [OWASP OWTF](https://owasp.org/www-project-owtf/)

![Possible for "Medium" GSoC 2025 project](https://img.shields.io/badge/medium%20size%20(~175h)-possible-yellow)
![Preferred for "Large" GSoC 2025 project](https://img.shields.io/badge/large%20size%20(~350h)-preferred-green)

![Difficulty: Hard](https://img.shields.io/badge/difficulty-hard-red)

##### Explanation of Ideas

- Refactor and complete the web interface ![Difficulty: Medium](https://img.shields.io/badge/difficulty-medium-orange)
- Update plugins to new recon, discovery and attack tools ![Difficulty: Medium](https://img.shields.io/badge/difficulty-medium-orange)
- Design & implement deployment architecture ![Difficulty: Hard](https://img.shields.io/badge/difficulty-hard-red)

##### Getting Started

Repositories:

- [OWTF](https://github.com/owtf/owtf)
- [OWTF Docker](https://github.com/owtf/owtf-docker)
- [OWTF Python client](https://github.com/owtf/owtf-python-client)

Please use the repositories' issue tracker, GitHub discussions, and don't forget to read the [contributing guide](https://github.com/owtf/owtf/blob/master/CONTRIBUTING.md). Join the community at #owtf on OWASP [Slack](https://owasp.slack.com/) and share your questions, project ideas.

#### Knowledge Prerequisites

- Terraform for infra as code
- Python for application
- React/React ecosystem for application frontend
- Kubernetes/helm for infrastructure deployment
- Basic knowledge of application security, tools used in bug bounty style hunting

##### Mentors

- [Viyat Bhalodia](mailto:viyat.bhalodia@owasp.org)
- [Abraham Aranguran](mailto:Abraham.Aranguren@owasp.org)

### [OWASP secureCodeBox](https://www.securecodebox.io)

secureCodeBox is a kubernetes based, modularized toolchain for continuous security scans of your software project.
The secureCodeBox comes with many different scanners officially integrated (from Amass to Zap) and integration 
with vulnerability management backends like DefectDojo.

To receive early feedback please:
- put your proposal on Google Docs and submit it to the OWASP
  Organization on Google's GSoC page in "Draft Shared" mode.
- Please pick "securecodebox" as Proposal Tag to make them easier to find
  for us. Thank you!

##### Explanation of Ideas

###### Add a secureCodeBox CLI (scbctl)

![Preferred for "Medium" GSoC 2025 project](https://img.shields.io/badge/medium%20size%20(~175h)-preferred-green)

![Difficulty: Medium](https://img.shields.io/badge/difficulty-medium-yellow)

The primary interface to interact with the secureCodeBox is through it's Custom Resources (CRs) in the Kubernetes API.
Writing the resource (e.g. [Scans](https://www.securecodebox.io/docs/scanners/amass#examplecom)) is generally not hard but can be cumbersome as the require the creation of a new file / multi line string in the command line.

To make these interactions easier to use and more fun, a custom (but optional) secureCodeBox CLI should help by automatically connecting to the Kubernetes API.

- create a new command line client which connects to the Kubernetes API and interacts with the CRs of the secureCodeBox
- write tests & including integration / e2e test and the CI pipeline (GitHub Actions)

More context & information are listed in the [GitHub Issue](https://github.com/secureCodeBox/secureCodeBox/issues/189)

###### Your own idea

![Preferred for "Medium" GSoC 2025 project](https://img.shields.io/badge/medium%20size%20(~175h)-preferred-green)
![Preferred for "Large" GSoC 2025 project](https://img.shields.io/badge/large%20size%20(~350h)-preferred-green)

![Difficulty: Easy](https://img.shields.io/badge/difficulty-easy-green)
![Difficulty: Medium](https://img.shields.io/badge/difficulty-medium-orange)
![Difficulty: Hard](https://img.shields.io/badge/difficulty-hard-red)

You have an awesome idea to improve the OWASP secureCodeBox?
We'd love to hear it, please reach out via email / owasp slack / github to ensure that the idea fits into the project. :)

##### Getting started

* Make yourself familiar with the project by going through our HowTo guides which will guide you through different parts of the secureCodeBox.
* Make sure that you have a solid golang knowledge to be able to complete the proposed project.
* Get in touch with
  [Jannik Hollenbach](mailto:jannik.hollenbach@owasp.org) to discuss any
  of the listed or your own idea for GSoC!

##### Mentors

* [Jannik Hollenbach](mailto:jannik.hollenbach@owasp.org) - OWASP secureCodeBox Core Team
* [Robert Felber](mailto:robert.seedorff@owasp.org) - OWASP secureCodeBox Project Lead

### [OWASP Nettacker](https://owasp.org/www-project-nettacker/)

OWASP Nettacker is a Modular Automated Penetration Testing/ Information gathering Framework and Vulnerability Scanner fully written in Python. Nettacker can run a variety of scans discovering subdomains, open ports, services, vulnerabilities, misconfigurations, default credentials.

![Difficulty: Medium](https://img.shields.io/badge/difficulty-medium-orange)
![Preferred for "Medium" GSoC 2025 project](https://img.shields.io/badge/medium%20size%20(~175h)-preferred-green)

##### Explanation of Ideas

- fix scan engine multi-threading/queuing issues
- improve WebUI / add dashboard
- add DefectDojo integration / output report format
- add SARIF output report format
- implement testing framework, get 70% code coverage level

##### Getting Started

Repositories:

- [OWASP Nettacker on OWASP GitHub](https://github.com/OWASP/Nettacker)
- Join OWASP Slack and contact us on channel [#project-nettacker](https://app.slack.com/client/T04T40NHX/CQZGG24FQ)

##### Knowldege  Requirements

- Python
- Flask
- HTML/CSS/JavaScript
- previous vulnerability scanning/bug bounty hunting experience

##### Mentors

* [Sam Stepanyan](mailto:sam.stepanyan@owasp.org)
* [Ali Razmjoo](mailto:ali.razmjoo@owasp.org)
* [Arkadii Yakovets](mailto:arkadii.yakovets@owasp.org)

### [OWASP Website](https://owasp.org)

This project for Google Summer of Code (GSoC) aims to enhance the OWASP website by improving its mobile responsiveness, updating its styling, and refining navigation for a more modern and user-friendly experience. Key objectives include revamping the project’s and chapter’s discovery features to make them more intuitive and accessible, creating comprehensive “Getting Started” pages to guide new users, and streamlining the site’s overall structure to ensure it is well-organized and easy to maintain. The project will focus on delivering a clean, cohesive design that aligns with current web standards, improving accessibility and usability across all devices.

#### knowledge required

Jekyl

#### Mentors

DonnieBLT on Slack
(looking for more mentors, signup here)

### [OWASP Nest](https://nest.owasp.org)

OWASP Nest is a comprehensive platform designed to enhance collaboration and contribution within the OWASP community. The application serves as a central hub for exploring OWASP projects and ways to contribute to them, empowering contributors to find opportunities that align with their interests and expertise. Our mission is to drive real-world collaboration and elevate the OWASP organization by addressing key challenges and streamlining processes.

#### Repository

- [backend](https://github.com/OWASP/Nest/tree/main/backend)
- [frontend](https://github.com/OWASP/Nest/tree/main/frontend)
- [schema](https://github.com/OWASP/Nest/tree/main/schema)

#### Technical Stack

- Python, Django, Pytest
- TypeScript, React, Jest
- Chakra UI, Tailwind CSS
- PostgreSQL, Algolia
- Docker, k8s, AWS

#### Projects / Ideas

![Difficulty: Medium](https://img.shields.io/badge/difficulty-medium-orange) ![Difficulty: Hard](https://img.shields.io/badge/difficulty-hard-red)

- [OWASP Contribution Hub](https://github.com/OWASP/Nest/issues/710): Aiming to streamline the onboarding process and connect contributors with mentors and impactful projects. This milestone focuses on improving collaboration within the OWASP community.
- [OWASP Nest API](https://github.com/OWASP/Nest/issues/707): The development of REST and GraphQL API endpoints for OWASP Projects, Chapters, Events, and Committees. This milestone will standardize data access across OWASP’s resources.
- [OWASP Nest Kubernetes Adoption](https://github.com/OWASP/Nest/issues/706): This milestone focuses on migrating the OWASP Nest application to Kubernetes, ensuring scalability, reliability, and ease of deployment.
- [OWASP Project Health Dashboard](https://github.com/OWASP/Nest/issues/711): A dashboard for monitoring the health of OWASP projects. This includes tracking vital metrics such as release frequency, issue resolution, and contributor growth.
- [OWASP Schema](https://github.com/OWASP/Nest/issues/709): Developing and extending a standardized schema for OWASP Projects and Chapters. This milestone aims to ensure consistency and ease of integration across OWASP resources.
- [OWASP Snapshots](https://github.com/OWASP/Nest/issues/708): Creating a summary of activities within OWASP projects, chapters, and events, including new blog posts and news, to keep the community informed about recent developments.

Please visit our planned [milestones page](https://github.com/OWASP/Nest/milestones) or `gsoc2025` labeled [issues page](https://github.com/OWASP/Nest/issues?q=is%3Aissue%20state%3Aopen%20label%3Agsoc2025).

#### Your own ideas

![Possible for "Small" GSoC 2025 project](https://img.shields.io/badge/small%20size%20(90h)-possible-yellow) ![Preferred for "Medium" GSoC 2025 project](https://img.shields.io/badge/medium%20size%20(175h)-preferred-green) ![Preferred for "Large" GSoC 2025 project](https://img.shields.io/badge/large%20size%20(350h)-preferred-green)

![Difficulty: Easy](https://img.shields.io/badge/difficulty-easy-green) ![Difficulty: Medium](https://img.shields.io/badge/difficulty-medium-orange) ![Difficulty: Hard](https://img.shields.io/badge/difficulty-hard-red)

Do you have an idea to improve OWASP Nest?
We'd love to hear it, please reach out in Slack to ensure that the idea fits OWASP Nest goals.

#### Expected Results

- Your proposal projects/ideas are fully completed.
- Your code follows our existing style guides and passes quality checks, test coverage, etc.

#### Getting Started

- Check out our [contributing guidelines](https://github.com/OWASP/Nest/blob/main/CONTRIBUTING.md)
- Join OWASP Nest channel [#project-nest](https://owasp.slack.com/archives/C07JLLG2GFQ)
- Consider `good first issue` (if there are any) from OWASP Nest [issues page](https://github.com/OWASP/Nest/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22good%20first%20issue%22)

#### Mentors

- [Arkadii Yakovets](https://github.com/arkid15r/) ([arkid15r](https://owasp.slack.com/team/U060W3NKLTF) on Slack)
- [Kateryna Golovanova](https://github.com/kasya/) ([Kate](https://owasp.slack.com/team/U07PWB1JZ6Z) on Slack)
- [Tamara Lazerka](https://github.com/aramattamara/) ([Tamara](https://owasp.slack.com/team/U0881RRPBDY) on Slack)

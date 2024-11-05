# Hung Thieu
***Technical Lead | Sr. Software Engineer with 7 years of experience contributing to diverse software projects.***<br>

## Projects

Official projects that I have participated in as a full-time employee for companies<br>

- [Metro.digital](#metrodigital)
  - [FSD Domain](#fsd-domain)
  - [SAM Domain](#sam-domain)
- [mesoneer AG](#mesoneer-ag)
  - [DBH Card Module](#dbh-card-module)
  - [PSD2](#psd2)
  - [ubidoc-ng](#ubidoc-ng)
  - [ubiID](#ubiid)
  - [CIC](#cic)
- [Adnovum](#adnovum)
  - [STMP (IMO & IPM)](#stmp-imo--ipm)

### Metro.digital
#### FSD Domain
*Web application for the internal users (sales team) to manage customers delivery addresses and payment methods, as well as services for fetching data*<br>

**Technical Lead Responsibilities:**
- ***Team Development:***
  - I single-onboarded a freshly joined small team to the product, including technical and soft skills.
  - Stay close, help my team members, and provide technical and self-improvement guidance when needed.
  - Knowledge exchange and a culture of continuous improvement are important. I helped the team set personal development goals according to their plan and project requirements.
  - Fostering a culture of independent mindset, my ultimate goal is for everybody in the team should know what to do in a situation. A strong team is each of its members understands and makes the right decision in any situation.
- ***Performance and Optimization:***
  - Create multiple dashboards for monitoring resource consumption and optimizing the system as well as reducing the infrastructure cost.
  - Add SLA, SLO, DORA and North Star metrics for monitoring the product status, and encourage the team to participate and practice.
  - Despite of the fresh team, I've driven the whole team to successfully migrate the legacy product to GKE.
  - Encourage the team to upgrade the dependencies to the new stable version to reduce product vulnerability.
  - Optimize the deployment method and migrate the legacy deployment pipeline to GitHub Action.
- ***Cross-Team Collaboration:***
  - As a Technical Lead, I also have to deal with multiple requests from other teams as well as our customers such as API changes, and new feature requests.
  - When API integration is needed across services, I created the requirements and polished the API documents from our side.

**Techs/Tools:**
- Architectures: Microservices
- Back-end: Java, Kotlin, Spring Boot, Gradle, Elastic Search
- CI/CD: GitHub Action
- Cloud: GKE and GCP
- Database: PostgreSQL
- Front-end: React, NextJs, TypeScript

#### SAM Domain
*Web application for the internal users (sales team) to manage, create activities, and understand their customers*<br>

**Sr. Software Engineer Responsibilities:**
- Implement new features and maintain existing projects in the back-end and front-end.
- Writing Unit, Integration, Jest, PACT, Functional tests.
- Configuration and monitoring of the build pipelines (GoCD).
- Migrate the build job from the old tool to GitHub Action with a built-in library (WaaS).
- Engaging with user bug tickets (referred to as Firefighting work), cross-checking service logs, and releasing hotfixes.
- Generate user stories addressing Technical Debt based on the observations and insights gained during the Firefighting work.
- Pair programming team members.
- Onboarding new members.

**Techs/Tools:**
- Architectures: Microservices
- Back-end: Java, Kotlin, Spring Boot, Gradle, Solr, Kafka
- CI/CD: GoCD, GitHub Action
- Cloud: Kubernetes
- Database: PostgreSQL, Cassandra
- Front-end: React, TypeScript

### mesoneer AG
#### DBH Card Module
*Web application (portal) for mobile-users to manage their bank cards*<br>

Requirement (brief): Support multiple tenancies, UI support multiple languages and responsive for mobile and tablet devices

**Responsibilities:**
- Back-end and front-end developer
- Writing Unit/Integration tests
- Peer code review

**Techs:**
- Architectures: Microservices
- Back-end: Java, Spring Boot, OpenAPI, JUnit, Cucumber, Testcontainers, Gradle
- CI/CD: Jenkins
- Database: Oracle, MariaDB, PostgreSQL, H2, Liquibase
- Front-end: Angular, TypeScript, HTML, JS, SCSS

#### PSD2
*APIs for TPPs based on PSD2 regulations. Solution based on the basis of the European Standard for PSD2 XS2A according to the Berlin Group NextGenPSD2 Framework version 1.3.6*<br>

Requirement (brief): Support multiple tenancies, UI support multiple languages, required authentication (mTan/CrontoSign) before confirm transaction.

**Responsibilities:**
- Back-end and front-end developer
- Writing Unit/Integration tests
- Create Jenkins build jobs
- Create and deploy application-stack for dev environment
- Create docker-compose for internal testing and Openshift deployment config for customer testing environment
- Peer code review

**Techs:**
- Architectures: Microservices
- Back-end: Java, Spring Boot, OpenAPI, JUnit, Maven
- Database: PostgreSQL
- Front-end: Express.js, HTML, JS, CSS

#### ubidoc-ng
*A web app (portal) and RESTful API for user to versioning and manage document templates (MSWord DOCX type) with merge-field*<br>

- [Microsoft Word Quick Parts - Field feature](https://support.microsoft.com/en-us/office/quick-parts-4ffef7c5-7596-4e95-9faf-41c771847a7b#bm3)
- [Example of Merge Fields](https://doc.laserfiche.com/laserfiche.documentation/en-us/Subsystems/ProcessAutomation/Content/Resources/Rules/Document-Merges/Preparing-a-Document-with-Merge-Fields.htm) (random example by Google Search)

Requirement (brief): Support add/delete/update document templates by its ID, support versioning and multiple languages for templates, review existing merge fields in templates. Provide APIs for other modules to send the prepared fields-values list and generate PDF with this list, return result when requested.

**Responsibilities:**
- Back-end and front-end developer
- Writing unit tests
- Create Jenkins build jobs
- Create and deploy application-stack for dev environment (Docker)
- Create docker-compose for internal testing
- Peer code review

**Techs:**
- Back-end: Java, Spring Boot, OpenAPI, JUnit, Maven
- Database: PostgreSQL
- Front-end: Angular, Material components, TypeScript, JS, HTML, SCSS

#### ubiID
*A web app (portal) for end-users verify their identity by Passport (EU) or ID Card (specific for Switzerland and German)*<br>
*A web-app (portal) for administrators to process the request from users to check their identity*<br>

Requirement (brief): UI support multiple tenants and languages. Support multiple devices screen size for both Desktop and Mobile. Users can open an integrated or built-in camera/webcam to capture photos.

**Responsibilities:**
- Pioneer team for the first alpha release.
- Front-end developer
- Peer code review

**Techs:**
- Front-end: Angular, Material components, TypeScript, JS, HTML, SCSS
- For the photos recognition, capturing and processing, we partner with [eID](https://www.electronicid.eu/en)

#### CIC
*Internal banking application for employees, gather information from their customers to complete forms, tasks. Create a complete flow for processing dossier of customer requests.*<br>

Requirement (brief): UI support multiple languages. Create dossier by input required fields, process dossiers by its state. Create and assignable tasks login roles with permissions.

**Responsibilities:**
- Back-end and front-end developer
- Peer code review

**Techs:**
- Architectures: Microservices
- Back-end: Java, Axon Ivy, OpenAPI, Maven
- Database: Oracle Database
- Front-end: Angular, Material components, TypeScript, JS, HTML, SCSS

### Adnovum
#### STMP (IMO & IPM)
*Internal banking application for employees, based on Eclipse RCP*<br>

**Responsibilities:**
- Back-end and front-end developer
- Peer code review
- Unit testing

**Techs:**
- Architectures: Monolithic
- Back-end: Java
- Database: H2
- Front-end: Eclipse RCP, SWT

# Business Resume

## Basic Information

|key|value|
|----|----|
|name|Shogo Kusuhara
|Current address|Osaka-shi, Osaka|
|Zenn|[@mikana0918](https://zenn.dev/mikana0918)
|Blog|[Tinglehacker](https://raku-noma.site/) (PV over 50,000 per month)
|English Proficiency|TOEIC score 960 (in my 3rd year of university)|

## Overview
- I have experience in building backend Go microservices and working on them from the design phase.
- Experience building micro front-ends.
- I have strength in front-end technologies and automation technologies such as E2E test infrastructure, storybook infrastructure, component design, and CI/CD infrastructure development, as well as infrastructure code development for modern front-ends.
- In the backend, we have experience with major dynamic and statically typed languages (PHP, Python, Kotlin), various frameworks, and DB (MySQL, PostgreSQL), and can flexibly handle everything from full stacks to specialized front-end work.
- I have some experience with various GoF design patterns (Builder, Strategy, Composition, Decorator, Facade, Adapter, etc.), and I am also experienced in application architecture design.
- At least a working understanding of tactical patterns in domain-driven development. (Has work experience)
- Knowledge of AWS managed services, IaC and CI/CD infrastructure using AWS CDK, and knowledge and work experience in serverless infrastructure such as various API integration.

- He is an engineer who can easily demonstrate his value in startups, small web development teams, and other situations where a limited number of people are required to take charge of a wide range of areas.

- He also has knowledge of SEO (his personal blog has achieved more than 50,000 PV per month), web marketing and growth strategies, and practical experience as a web director.

## Skills

- Basically, I have listed only the technologies I have used in my actual work.

### Languages

PHP | JavaScript | TypeScript | Golang | Kotlin | Python | bash script

### Frameworks (ver.)

Laravel | FastAPI | Spring Boot | Gin | CakePHP(3) | Nuxt.js | Vue.js | React.js(17.x) | WordPress

### RDB/NoSQL

MySQL | PostgreSQL | CloudFirestore | MongoDB

### Search Engine

ElasticSearch

### Cloud computing

#### AWS

Amplify | VPC | S3 | Cloud Front | Lambda | ECS | Fargate | ECR | IAM | RDS(MySQL|PostgreSQL) | Aurora | SNS | SES | CloudFormation | CloudWatch | CloudTrail | SecretsManager | CodeDeploy | CodePipeline | CodeBuild | EventBridge | SSM 


#### GCP 

Cloud Functions | Cloud Firestore | Firebase Hosting

### SaaS/PaaS

GitHub | GitHub Actions | CircleCI | DataDog | Sentry | Shopify

### Other

AWS CDK | Github Actions | Terraform | Vagrant | Docker | Nginx | unicorn | Apache | Gulp | Webpack | SASS | Vuetify | ElementUI | Puppeteer | Playwright Hashicorp Vault | Redux | React Hook Form | Draft.js | UiPath | Postman | Cypress | gRPC |

## Work that can easily demonstrate value
- Front-end design
- Full stack development in BFF configuration
- Package manager implementation
- Introduction of Linter and Formatter
- Implementation of unit and integration testing
- Application design
- Proper definition of git branch model
- Build a serverless infrastructure
- CI/CD pipeline construction
- Building e2e testing infrastructure
- Infrastructure coding
- Deployment automation

## Main Work Experience

### Development of MA-based PaaS (February 2022~)

Project Summary] Development of sales support and MA tool digima

Responsibilities】 Front-end development, back-end development, and some infrastructure development
- Software engineering work in a fully English-speaking team
- golang microservices + Laravel proxy API backend development
- Full replacement of SMS sending function and development of WYSIWYG editor using Draft.js
- New development of full-text search microservice using Elasticsearch
- Development of a new microservice for sending and receiving e-mail from a mail server using SMTP/IMAP protocols
- Development of a real estate information crawler microservice using UiPath
- Deployment of HCP Vault in Vagrant environment
- Creation of local development environment for new microservice
- Creation of infrastructure for a new microservice using Terraform

Value】I was able to use my English skills to join a team that was working in an English-based environment, and developed the front-end and back-end of a new function.
I developed the front-end and back-end of the new functionality. In many cases, I was the most knowledgeable about the front-end, so my focus was on the front-end, but if there were not enough man-hours, I proactively developed the back-end.
I was new to both golang and React, but I caught up in about a month.
I started to take the lead in front-end design, library selection, legacy code improvement, etc., while back-end man-hours were heavy, so I started to focus on back-end development.
I mainly developed the backend. I was also actively involved in building the infrastructure and local development environment.


### Development of AI-based data analysis platform (May~Feb. 2021, Subsequent work)

Project Summary】Development of datagusto, an AI-based product that allows users to easily create and simulate AI.

Responsibilities】Front-end design (components, applications), front-end development (Vue.js/TypeScript/Amplify/Storybook/Playwright), offshore management (Vietnam), back-end API development (Python/ FastAPI)/Infrastructure coding with AWS CDK (PR and coding for IAM user creation)

- Front-end development with Vue.js + TypeScript + Vuetify
- Leveling of development environment by Package Manager, Editor configuration, Linter/Formatter, Makefile
- Investigation and practice of technologies such as CompositionAPI (for vue2) and functional components
- Introduction of Sentry
- Maintenance of development documentation
- Development of backend API using Python + FastAPI
- Deployment of Playwright and maintenance of infrastructure e2e code pipeline
- Developed infrastructure components using Vuetify
- Automated IAM user creation with IaC using AWSCDK
- Backup for offshore development using English language skills
- Creation of authorization module for components
- Building cross-account CI/CD pipeline for PrivateCloud version release (AWS and github)
- slack integration
- Research~implementation of updates to Vue3

The client initially asked us to design and develop a platform that could scale. We designed front-end components, built StoryBook, and implemented E2E testing. We also had to manage the offshore development, so we used English to deal with the project. I also spent my holidays learning about AWS CDK, but I caught up. He contributed to the creation of a fast and robust front-end infrastructure and DevOps infrastructure.


### Ongoing development of a side job matching website (April 2021~May 2021)

Project Summary】Development of CrowdLinks, a side hustle matching site.

Responsibilities】Development of new functions

Value】Took charge of UI and backend API modifications for new functionality development.


### Development of a job posting system for a job change site for designers (February 2021~March 2021)

Project Summary】Addition of functionality to the job posting system of a job transition site for designers.

Duties】Front-end development/design, etc.

- Responsible for developing new front-end functions
- Research and implementation of various Nuxt community plug-ins (Markdown-it, Sentry)
- Overall refactoring of error modules
- Fixing Node version by node-version and setting up package engine
- E2E test automation and base code creation by researching and incorporating Playwright
- Inventory of site improvement points to improve SEO inflow
- Creation of authorization module for components

Value Demonstrated] This was my first time using Nuxt for static typing, but I caught up with it despite some difficulties.
After catching up, we investigated and implemented new technologies at the same time, and achieved a number of new functions in about one month.
He also implemented various automations and ambitiously added new technologies to the project's infrastructure. Front-end engineers
We contributed to the creation of a project that maximized the development productivity of the front-end engineers and that could be talked about when communicating to the outside world.

### Development of PaaS EC site for D2C (October 2020 - March 2021)

Project Summary】BFF development engineer for PaaS EC site for D2C

Responsibilities】By working as a BFF engineer, you will be in charge of front-end and back-end implementation.

- Create docker-compose/bash scripts for local development when launching a new brand.
- Conducted research and inventory of problem areas to improve site speed
- Modified the entire cart module to add a new product type (contact lenses)
- Created, designed, and tested a module to avoid SEO searches in non-production environments that can be referenced directly by IP, etc.

The project was a PHP and TypeScript project that used a lot of functional libraries.
The development style was agile, DDD and high level environment, but
Caught up with quite a lot of hard work. The level of application code was high.

Translated with www.DeepL.com/Translator (free version)
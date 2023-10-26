# Curriculum Vitæ

> **If you are a recruiter, you might also want to check out my [Experience Summary](/summary),
> where I tell a bit about my work experience with several tools and methods, sorted by keyword.**

You can also download a more condensed version of this in [PDF](/pdf/cv.pdf).

## <i class="fa fa-briefcase"></i> Recent Work Experience

### Data Engineer at [42 Technologies](https://42technologies.com/)

*Mar 2021 - Now*

42 Technologies is a startup aiming to solve the big problem of data unification
and reporting in the retail space, by offering an ample variety of integrations
and great UX. I work there building data integrations and pipelines, along with
the infrastructure to run them.

My contributions there include:

- Several custom data pipelines built with PySpark on GCP Dataproc.
- Integrations with external systems using Typescript on Node.
- Custom Terraform modules for common infrastructure needs.
- Identification of several security issues and implementation of best practices.
- Improvements to service observability via Sentry integration
- Github Actions CI/CD pipeline improvements

### Site Reliability Engineer at [Roon Labs](https://roonlabs.com/)

*Jun 2020 - Mar 2023*

Roon Labs aims to make the ultimate music player for audiophiles. I worked there
mostly on the infrastructure that serves the cloud services and on the data
pipelines that deal with music metadata. I worked there on rebuilding the
infrastructure using Kubernetes on GCP, managing our PostgreSQL and Scylla
databases and overhauling the GitOps workflow and the developer experience around it.

#### Project: Infrastructure Rebuild

Soon after I joined the company, I started working on rebuilding the entire cloud
infrastructure of the company using Terraform and Kubernetes, where previously
Docker Swarm was used. Because this project only involved one more person, I was
able to contribute with several parts of the infrastructure, including:

- Several custom Terraform modules for improving code reuse.
- Automation tools and technical documentation for common tasks.
- Secrets management automation, making the adoption of security best practices easier.
- Custom Grafana dashboards and alerts for monitoring the infrastructure and services.

#### Project: Developer Experience Improvements

I also worked on improving the developer experience of the company, by automating
a lot of the manual tasks that were previously performed by the developers using
GitOps, Helm and ArgoCD. My contributions include:

- A new base Helm chart for most services, with a standardized structure and
  configuration, that made it easy for developers to follow best practices.
- A CLI tool for performing common operations on the repository files.
- Centralized logging handling.

#### Project: ScyllaDB Migration

Since some of the services of the company were not a good fit for our main PostgreSQL,
I was tasked of deploying a new database cluster using ScyllaDB. My contributions
include:

- A Terraform module for deploying ScyllaDB clusters on GCP.
- Automation for common tasks, such as backups, restores, and cluster upgrades.
- A custom Grafana dashboard for monitoring the cluster.

**Toolset:** Terraform, Kubernetes, Helm, ArgoCD, Git, GCP, AWS, Vault, Grafana,
Prometheus, PostgreSQL, Redis, ScyllaDB

### Software Engineer (Back-end and DevOps) at [Novidá](https://novida.com)

*Sep 2015 - Jun 2020*

Novidá is a startup using indoor positioning to optimize low-automation processes
in industry and facilities. I started working there right at the beginning, in
the Indoor Positioning project, and then moved on to the Process Optimization project.

#### Project: Process Optimization

In 2018, I was assigned to the development of the process optimization product,
in close collaboration with a large industrial client. I had to balance the needs of
the client with the interests of the company in creating a widely useful product,
and had to negotiate the development of features with stakeholders on both sides.

The project itself was also very challenging, as it had an intricate domain and
involved solving a particularly intractable combinatorial optimization problem.
My contributions include:

- A Domain Model for the project, based on a Ubiquitous Language built in
  collaboration with business stakeholders.
- Design of a heuristic solver for the resource optimization problem and its
  implementation in efficient Cython. Successfully used in production.
- Design and partial implementation a proper RESTful API in collaboration with
  the front-end developers.

#### Project: Indoor Positioning

The cornerstone of all products of the company, processing hundreds of positions
every second with high availability and low latency. My contributions include:

- An adaptable signal processing pipeline, including Bayesian filtering.
- Building, training, evaluating and deploying machine learning models.
- Design and implementation of a proper RESTful API, using Spring Boot.
- Tooling for monitoring and profiling the system in production with Graylog and Grafana.
- Deploying on Kubernetes with proper configuration to ensure scalability and availability.

**Toolset:** Java, Spring Boot, Python, Django, Docker, Git, SQL, GCP,
Kubernetes, AWS, Microservices, RabbitMQ

## <i class="fa fa-plus-square"></i> Personal Projects

#### <a href="https://github.com/GFlorio/operaplan" target="_blank" rel="noreferrer"><i class="fab fa-github"></i> OperaPlan</a>

A library for operations resource planning and optimization in Java. Built upon
state of the art heuristics and several experimental tweaks for improving
performance on real datasets.

#### <a href="https://github.com/GFlorio/pytimeset" target="_blank" rel="noreferrer"><i class="fab fa-github"></i> Pytimeset</a>

A library for dealing with continuous time sets in Python. Provides efficient
set arithmetics powered by Cython.

## <i class="fa fa-graduation-cap"></i> Education

#### Bachelor's Degree (2013 - 2017)

- Computer Engineering at University of São Paulo (POLI-USP)
- **Graduation project:** Decision Support for Operations Management - A software
system to help measure relative performance of the resources and strategies on
a operation and suggest optimal resource allocation based on previous
performance.

#### Certificates and major courses

- [Cloud Engineering with Google Cloud](https://www.coursera.org/account/accomplishments/specialization/certificate/FRE8HBFC9SVS)
- [Cloud Architecture with Google Cloud](https://www.coursera.org/account/accomplishments/specialization/certificate/4Q3TPM5MXBW5)
- [SRE and DevOps Engineer with Google Cloud](https://www.coursera.org/account/accomplishments/specialization/certificate/FRE8HBFC9SVS)

## <i class="fa fa-globe"></i> Languages

- **Portuguese** (native)
- **English** (fluent/proficient)
- **German** (intermediate)

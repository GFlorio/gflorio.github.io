# Curriculum Vitæ

> **If you are a recruiter, you might want to check out my [Experience Summary](/summary),
> where I tell a bit about my work experience with several tools and methods, sorted by keyword.**

You can also download a slightly more condensed version of this in [PDF](/pdf/cv.pdf).

## <i class="fa fa-briefcase"></i> Work History

### Software Engineer (Back-end and DevOps) at Novidá 

*Sep 2015 - now*

Novidá is a startup using indoor positioning to optimize low-automation processes
in industry and facilities. I started working there right at the beginning, in
the Indoor Positioning project, and then moved on to the Process Optimization project.

#### Project: Process Optimization

In 2018, I was assigned to lead the development of the process optimization product.
This was done in close collaboration with a large industrial client, which
mostly inspired its creation. I had to balance the needs of the client with the
interests of the company in creating a widely useful product, and had to
negotiate the development of features with stakeholders on both sides.

The project itself was also very challenging, as it had an intricate domain and
involved solving a particularly intractable combinatorial optimization problem.
My contributions include:

- A Domain Model for the project, based on a Ubiquitous Language built in
  collaboration with business stakeholders.
- Design of a heuristic solver for the resource optimization problem and its
  implementation in efficient Cython. Successfully used in production.
- Design and partial implementation a proper RESTful API in collaboration with
  the front-end developers.

**Toolset:** Python, Django, Domain-Driven Design, Docker, Git, SQL,
Kubernetes, Google Cloud Platform, RabbitMQ

#### Project: Indoor Positioning

The company was just starting back then, so I had to build the Android client library
and the back-end from scratch, by myself. Nowadays, it is the cornerstone of all
products of the company, processing hundreds of positions every second with high
availability and low latency. My contributions include:

- An adaptable signal processing pipeline, including Bayesian filtering.
- Building, training, evaluating and deploying machine learning models.
- Design and implementation of a proper RESTful API, using Spring Boot.
- Tooling for monitoring and profiling the system in production with Graylog and Grafana.
- Deploying on Kubernetes with proper configuration to ensure scalability and availability.

**Toolset:** Java, Spring Boot, Python, Scikit-Learn, Docker, Git, SQL,
Kubernetes, Azure, Microservices Architecture, RabbitMQ


### Software Engineering Intern at Software Architecture Lab 

*Apr 2014 - Sep 2015*

My first job was in a software factory inside the Software Architecture Lab in
my University department (POLI-USP). There, we worked under a very dedicated and
very demanding professor, building and maintaining various internal systems with
a strong focus on quality.

#### Project: eNOVA24h

Most of my time there was developing a system for the Nutrition department of
the University. The objective of the project was to support a new research
methodology, which included collecting data from patients, cross-referencing
them with a large nutritional database and creating useful automated reports for
the research at the department. My contributions include:

- Designing and building task-oriented use cases and web interfaces in .NET.
- Designing a denormalized data model to better support the reporting modules.
- Working with the researchers to design the data visualization in the reports.
- Deploying the system to IIS servers at the University.

**Toolset:** C#, ASP.NET MVC, Microsoft SQL Server, Python, Ansible,
Test-Driven Development (TDD), Layered Architecture


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

## <i class="fa fa-globe"></i> Languages

- **Portuguese** (native)
- **English** (fluent/proficient)
- **German** (intermediate)

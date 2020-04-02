# Curriculum Vitæ

If you are a recruiter, you might want to check out my [Experience Summary](/summary),
where I tell a bit about my experiences, organized by keywords.

## Work History

### Software Engineer (Backend and DevOps) at Novidá - Since Sep 2015

Novidá is a startup using indoor positioning to optimize low-automation processes
in industry and facilities. I started working there right at the beginning, in
the Indoor Positioning project, and then moved on to the Process Optimization project.

#### Project: Process Optimization

In 2018, I was assigned to lead the development of the process optimization product.
This was done in close collaboration with a large industrial client, which
mostly inspired its creation. I had to balance the needs of the client with the
interests of the company in creating a widely useful product, and had to
negotiate between stakeholders the development of features.

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
Kubernetes, Azure AKS

#### Project: Indoor Positioning

The company was just starting back then, so I had to build the Android client library
and the back-end from scratch, by myself. Nowadays, it is the cornerstone of all
products of the company, processing hundreds of positions every second with high
availability and low latency. My contributions include:

- An adaptable signal processing pipeline, including Bayesian filtering.
- Building, training, evaluating and deploying machine learning models.
- Design and implementation of a proper RESTful API, using Spring Boot
- Tooling for monitoring and profiling the system in production with Graylog and Grafana.
- Deploying on Kubernetes with proper configuration to ensure scalability and availability.

**Toolset:** Java, Spring Boot, Python, Scikit-Learn, Docker, Git, SQL,
Kubernetes, AWS, Microservices Architecture


### Software Engineering Intern at Software Architecture Lab - From Apr 2014 to Sep 2015

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

- Designing and building task-oriented use cases and web interfaces in .NET
- Designing a denormalized data model to better support the reporting modules
- Working with the researchers to design the data visualization in the reports
- Deploying the system to IIS servers at the University

**Toolset:** C#, ASP.NET MVC, Microsoft SQL Server, Python, Ansible,
Test-Driven Development (TDD), Layered Architecture



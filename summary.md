# Experience Summary
{:.no_toc}

<a id="top"/>

Once you are done with this summary, you can find out more about me in [my
resume](/cv).

## Table of Contents
{:.no_toc}

* Index
{:toc}

## Expert

### Docker

I have been using Docker in production since 2017. I think it's a superb tool,
even though sometimes it does have a few counter-intuitive and hard to debug
problems.

I'm also comfortable with image optimization and multi-stage builds.

See also: [DevOps](#devops).

[Top](#top)

### Google Cloud Platform (GCP)

I have been using GCP since 2017. I think it's a great platform for running
all kinds of workloads, and I'm comfortable with most of its characteristics and quirks.
I have done official Google courses to improve my knowledge of the platform, and I
have good experience with GKE, GCE, GCS, Cloud SQL, Pub/Sub, Dataproc and many other services.

See also: [DevOps](#devops).

[Top](#top)

### Helm

I have been using Helm daily since 2020. I think it's a great tool for managing
Kubernetes deployments, and I'm comfortable with writing complex charts from scratch,
including subcharts and dependencies. At Roon Labs, I
[used a combination of base charts and CLI tools](/cv#project-developer-experience-improvements)
to design a new developer experience with deployments, making it easy for
developers to follow best practices, and for SRE enginners to roll out changes to
multiple services at once.

[Top](#top)

### Indoor Positioning

From 2015 to 2017 I have [worked mostly on indoor
positioning](/cv#project-indoor-positioning). During that time, while the focus
was on using commodity hardware, I have tried just about any technology you
have heard about (and probably some you haven't).

I have used machine learning methods extensively, as well as methods based on
wave propagation (RSSI, AoA and TDoA), complemented with dead-reckoning. Ended
up with an approach that could combine multiple results using Bayesian sensor
fusion.

[Top](#top)

### NodeJS

I have been using NodeJS since 2015. It's a great platform for building
lightweight containers and I've used it a lot to build smaller,
functional-style, workers that would consume events from RabbitMQ or batch
process data.

In my opinion, its biggest downside is Javascript itself, being a language that
does not lend itself for building large systems with heterogeneous teams.
TypeScript is a step in the right direction to alleviate that. Remains to be
seen if it will become a reliable standard.

In April 2020 I was verified as a top 5% NodeJS Expert by PluralSight IQ.

![PluralSight IQ NodeJS Expert](/assets/node_expert.png)

### Python

I've been using Python personally since 2009, and professionally since 2015.  I
think it's a great language for a lot of tasks, and the ecosystem has some of
the best tools around for web services, machine learning and scientific
computing in general.

The main downside, which generally is performance, can normally be mitigated by
careful profiling and building an extension in Cython. My personal project
[pytimeset](/cv#-personal-projects) was inspired by one of these occasions. By
using it, I have achieved a run time reduction of around 85% for a fairly
complex algorithm I had in production, which was taking hours to run for some
of our bigger clients.

I believe I am able to write Python in a very *pythonic* and clean way, and I
follow PEP8 rigorously. In April 2020, I was verified as a top 1% Python expert
by PluralSight IQ.

![PluralSight IQ Python Expert](/assets/python_expert.png)

[Top](#top)

### REST

A lot of people use "RESTful API" to mean simply a JSON API over HTTP, but I
think there's really a lot of concrete gain to be had by adopting REST more
closely to what Roy Fieldings first envisioned.

I have been using REST more rigorously 2017, although I have been designing
"RESTful" JSON APIs over HTTP since 2015. I have good experience on properly
using the HTTP verbs (including the often forgotten OPTIONS), resources, and
HATEOAS.

[Top](#top)

### Software Architecture

From working under a software architecture professor, who then became more or
less my mentor for the whole college course, I got a strong theoretical basis in
the field. I feel comfortable with viewpoint modeling and with applying reference
architectures to concrete problems.

That said, I know most people aren't like that, and the word itself has a
([probably
deserved](https://www.joelonsoftware.com/2001/04/21/dont-let-architecture-astronauts-scare-you/))
stigma around it, so I try to have a very lightweight approach to architecture
in practice. I believe that we can get the whole team to think architecturally
just by asking the right questions at the right stage of a project and working
together to answer them, and that we can get a lot of concrete value from doing
that. No UML required, and definitely no Big Design Upfront.

[Top](#top)

## Experienced

### Agile

I strongly believe "agile" is an adjective, not a noun. Therefore, agility
should be built in on everything we do. When [building a successful startup
from scratch](/cv#project-indoor-positioning) in a economically unstable
country such as Brazil, agility was vital to the survival of the company. I
think that helped me build a natural agile mindset.

[Top](#top)

### Algorithms

I'm a bit of a Logic nerd, therefore I'm also a bit of a algorithm nerd. I feel
comfortable analyzing, designing and tweaking many kinds of algorithms, but I
especially like heuristic searches. In fact, tweaking algorithms is pretty much
all I do in my pet project [OperaPlan](/cv#-personal-projects).

[Top](#top)

### ArgoCD
See [GitOps](#gitops).

[Top](#top)

### Artificial Intelligence

Being the algorithm nerd I am, many areas of AI interest me:

- I have built, deployed and maintained machine learning models when working on
  the [Indoor Positioning project](/cv#project-indoor-positioning).
- I also have built, deployed and maintained heuristic search algorithms on the
  [Process Optimization project](/cv#project-process-optimization)
- I have a solid grasp of Game Theory. I've been wanting to get into
  [Agent-based Computational
  Economics](http://www2.econ.iastate.edu/tesfatsi/ace.htm), but still haven't
  really gotten around to that yet.

See also: [Machine Learning](#machine-learning), [Optimization](#optimization).

[Top](#top)

### Debian
See [Linux](#linux).

[Top](#top)

### DevOps

I think DevOps as the name of a position or a team [is a bit
weird](https://martinfowler.com/bliki/DevOpsCulture.html), but I get what you
mean. In that sense, I think I was lucky, because up until now I have
always worked in places with a strong DevOps culture. I have always been
responsible for taking care of my code during all its lifecycle, including
running and monitoring it, and I learned a lot because of this.

Later on, I had the opportunity to help
[rebuild from the ground up](/cv#project-infrastructure-rebuild) much of the
infrastructure at Roon Labs, which was a great learning experience working with
DevOps and GitOps at scale.

[Top](#top)

### Django

I first had contact with Django in 2014 and it was love at first sight. I have
chosen to use Django + Django Rest Framework for every application I've written
in Python since 2016. I know pretty well the ins and outs of the framework and
I think it's a great tool for many kinds of projects.

I have written applications with it in the "default" architecture as well as in
conjunction with an "Hexagonal" architecture, in order to make the domain model
stand out better, unhindered by infrastructure code.

See also: [Python](#python).

[Top](#top)

### Domain-Driven Design

Essential technique in my toolset. I have been using DDD and pushing it in my
teams in one way or another since 2017. Even though the beginning was a
little awkward (the learning curve can be pretty steep), I now consider myself
able to properly apply both the tactical and strategic patterns in a way that
makes sense to the project I'm working on.

Even though some of the techniques aren't really well suited for all software
projects, I believe that a "domain first" approach is always beneficial.

[Top](#top)

### Fast paced environments

I can't think of a faster environment than [a tiny startup rising up from the
ground](/cv#project-indoor-positioning). Honestly, I love this kind of
environment (in fact, our office was on a old house where two of the team
members lived, so there was work going on *all the time*. I have slept on their
couch more than once). I work my best when I can go to sleep with a problem in
my head, wake up with the solution, share it with everyone and go make it.

On the other hand, such environments are prone to the "permanent sense of
impending doom syndrome", and it's not a easy task for management to avoid
that. As such, I think that a open feedback culture is a hard requisite for
having a healthy fast paced work environment. Sometimes we just need to take a
step back and take a good look at our priorities, everyone works better when
they're feeling safe.

[Top](#top)

### Flask

I have used Flask on a few projects since 2016. I tend to prefer Flask over
Django when using NoSQL databases.

[Top](#top)

### Git

I have been using git professionally almost every day since 2017. At this
point, it's almost second nature for me. I have worked with trunk based
development and with feature branches workflows.

[Top](#top)

### GitOps

I'm a strong proponent of GitOps. I have been using it since 2018, in different forms
and I think it's a great way to manage infrastructure for many kinds of projects.
The specific tools will vary by project, but the benefits of having a detailed and
precise log of all changes to the infrastructure are too good to pass up.

[Top](#top)

### Java

I first learned Java when I was 13 years old, because I wanted to make
cross-platform GUI programs for my friends. Since then, I have been using it on
some of my projects (mostly whatever needs high throughput), but more intensely
since 2018.

Java doesn't get much love out there, but it's one of my favorite languages.
It's compatible with absolutely everything, the JVM is a wonder of modern
engineering, and the language lends itself very well for work with larger,
heterogeneous teams.

I think most of the hate on Java is caused by people misusing or abusing OOP. I
have good OOP foundations and practice, I keep myself updated on new Java
features, and my copy of [Effective
Java](https://www.amazon.com/Effective-Java-Joshua-Bloch-ebook/dp/B078H61SCH)
always close by.

[Top](#top)

### Kubernetes

I have been using Kubernetes since 2017 for managing several projects in a
auto-scalable cloud of around 20 nodes, serving upwards of 2000 requests per second,
including many mission-critical services.  I have experience configuring clusters
from scratch using Terraform, GKE and Helm, and also applying the current best
practices for availability and security.

See also: [DevOps](#devops).

[Top](#top)

### Linux

I have been using Linux on my personal computer since 2008, and then on almost
every server, container and VM I have ever managed. I would say I have a pretty
good grasp on Linux operation and administration. Through the years, I have
used Ubuntu, Debian, Fedora and Alpine.

See also: [DevOps](#devops).

[Top](#top)

### Machine Learning

I first started looking into machine learning when I started the [Indoor
Positioning project](/cv#project-indoor-positioning) in 2015. Thankfully, I had
a solid statistical background from [engineering school](/cv#-education), so
many of the concepts were relatively easy to grasp.

Because of that, I have acquired experience in building, deploying and
maintaining machine learning models in production, complete with unsupervised
outlier detection, data cleaning and normalization, cross-validation and
metaparemeter optimization by local search.

As for the actual algorithms, I tend to prefer something tweakable and
interpretable than the absolute best performance, because I think that's what
brings more value to most real business cases.

[Top](#top)

### Microservices Architecture

Back in 2015, I had the opportunity to participate in a completely greenfield
project, and we chose the way of microservices. We did a pretty good job, I
believe, because the services were really autonomous, the communication was
entirely done with asynchronous messages, and we did eventual consistency
right.

Even so, I probably wouldn't do that again. Experience has nudged me in the
way of a little more coarse autonomous services, as aligned as possible with
the subdomains of the business. There is some discussion to if that qualifies
as "micro" services.

Then again, I don't think "microservices" really describes an architecture,
it's more like a deployment strategy. While that's important, it's only a part
of the architecture.

See also: [RabbitMQ](#rabbitmq), [Software Architecture](#software-architecture)

[Top](#top)

### MongoDB

I have been using MongoDB on some of my projects since 2016, sometimes as an
auxiliary database, sometimes as the main database. Although it's usually not
my first choice (too easy to run on nasty N+1 problems), I think MongoDB can
work very well when paired with Domain-Driven Design, as properties of a
Document fit quite nicely those of an Aggregate.

[Top](#top)

### MySQL
See [SQL](#sql).

[Top](#top)

### Optimization

Sort of my favorite theme in Computer Science right now. I think that
applications based on heuristic optimization have a potential to transform a
lot of businesses, especially when paired with machine learning.

My [graduation project](/cv#-education) in college was about this and, since
then, the more I learn, the more excited I get. On my job, I have designed,
implemented and deployed a [optimization
system](/cv#project-process-optimization) for job distribution among
maintenance workers of a large industrial client, complete with a constructive
heuristic and local search.

I also have a [pet project](/cv#-personal-projects) that is really just an
excuse to tweak around algorithms and see what happens.

[Top](#top)

### PostgreSQL

I have been working with PostgreSQL since 2016, and managing it in production since
2020. I have a good grasp of the best practices and the most common pitfalls related
to operating simple databases.

See also: [SQL](#sql).

[Top](#top)

### RabbitMQ

It's a great tool to build autonomous services around. I have
been using it in production since 2016 for processing hundreds of messages per
second and I've found it's really reliable and relative easy to manage.

I have also used it just for scheduling asynchronous tasks (such as with
Celery), but I think it might be a little overkill just for that.

[Top](#top)

### Redis

I have been using Redis since 2016, mostly as a cache. I'm also used to managing
it in production, both standalone and inside Kubernetes clusters.

[Top](#top)

### Remote working

I have been working with varying degrees of "remoteness" since 2015.
The best thing about it, in my opinion, is being able to work with the best people
from all over the world, without being restricted by geographic barriers.

[Top](#top)

### Spring Boot

My framework of choice when building Java applications. I have been using it
professionally since 2018, and I'm always amazed at the sheer amount of
functionality it offers, and the quality of (most) design decisions that went
into it.

Of course, because of that, one risks having the whole application swallowed up
by it, but that can be avoided by having a separate domain model, independent
from the framework.

See also: [Java](#java).

[Top](#top)

### SQL

I have been working with SQL databases since 2015. During this time, I have
worked with Microsoft SQL Server, MySQL and PostgreSQL. I have used ORMs
(Django and JPA2/Hibernate) and have experience hand-crafting optimized queries.

As far as building and maintaining an application goes, I would say that I have
no problems using any of those tools whatsoever.

[Top](#top)

### Terraform

I have experience using Terraform to manage infrastructure as code, such as
Kubernetes clusters, databases, load balancers and other cloud resources.
I have written custom reusable modules, and have experience managing infrastructure
in an immutable paradigm with it.

[Top](#top)

### Ubuntu
See [Linux](#linux).

[Top](#top)

## Some Experience

### Ansible

I've used Ansible for about two years, to manage both on-premises and virtual
cloud servers. In 2017 my team has moved on to cloud-managed Kubernetes, and
since then my Ansible skills got a little rusty, but I'm confident I could pick
it up again fast, should the need arise.

See also: [DevOps](#devops).

[Top](#top)

### AWS
See [DevOps](#devops).

[Top](#top)

### Golang

I've been actively wanting to learn Go since 2022. I've had the opportunity of
writing a few Kubernetes operators with it, and I'm looking for ways to use it more
on my work.

[Top](#top)

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

### Python

I've been using Python personally since 2013, and professionally since 2015.  I
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

From [working under a software architecture
professor](/cv#software-engineering-intern-at-software-architecture-lab), who
then became more or less my mentor for the whole course, I got a strong
theoretical basis on the field. I feel comfortable with viewpoint modeling and
with applying reference architectures to concrete problems.

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

The methodology with which I have most experience is Kanban.

[Top](#top)

### Algorithms

I'm a bit of a Logic nerd, therefore I'm also a bit of a algorithm nerd. I feel
comfortable analyzing, designing and tweaking many kinds of algorithms, but I
especially like heuristic searches. In fact, tweaking algorithms is pretty much
all I do in my pet project [OperaPlan](/cv#-personal-projects).

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

The [first years at Novidá](/cv#project-indoor-positioning) were quite
Ops-heavy because, in order to save money with server bills, we would change
cloud providers every year, seeking those "free trials" for startups that almost
all of the cloud providers offer.

We started at AWS, then IBM's Softlayer, then Azure and finally Google Cloud
Platform. All those changes were naturally very stressful and required a lot of
work, but they have led us to operate in a very cloud-agnostic way, based on
Kubernetes.

In the end, that left me with some knowledge of all those cloud providers,
although I didn't have much chance to explore their tools in depth, since we
were mostly rolling our own.

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
team in one way or another since 2017. Even though the beginning was a
little awkward (the learning curve can be pretty steep), I now consider myself
able to properly apply both the tactical and strategic patterns in a way that
makes sense to the project I'm working on.

Even though some of the techniques aren't really well suited for all software
projects, I believe that a "domain first" approach is always beneficial.

[Top](#top)

### Git

I have been using git professionally almost every day since 2017. At this
point, it's almost second nature for me, although I still have to take a look
at the docs to do some of the "set and forget" things such as submodules and
hooks. I have worked with trunk based development and with feature branches.

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
auto-scalable cloud of around 80 pods. I like to use it in conformity with the
recommended best practices and In the spirit of a true DevOps culture. Each
team manages their own infrastructure configuration files in a central Git
repository. That way, we have a true versioned and reproducible environment.

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

### RabbitMQ

It's really the best tool available to build autonomous services around. I have
been using it in production since 2016 for processing hundreds of messages per
second and its reliability surprises me every time.

I have also used it just for scheduling asynchronous tasks (such as with
Celery), but I think it might be a little overkill just for that.

[Top](#top)

### Remote working

I have been working with varying degrees of "remoteness" since 2015, 2 years of
that period being fully remote. The best thing about it, in my opinion, is
being able to live away from large urban centers without wasting hours upon
hours of commuting.

The only "remote workflow" I have ever experienced is fully asynchronous
communication, but I'm really excited to try other methods.

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
(Django and JPA2/Hibernate) and have hand-crafted optimized queries without any
problems.

As far as building and maintaining an application goes, I would say that I have
no problems using any of those tools whatsoever.

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

### Azure
See [DevOps](#devops).

[Top](#top)

### Google Cloud Platform
See [DevOps](#devops).

[Top](#top)

### PostgreSQL
See [SQL](#sql).

[Top](#top)

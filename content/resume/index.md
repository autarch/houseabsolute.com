---
title: Resume
author: Dave Rolsky
type: page
url: /resume/
---

<div class="web-only">

Contact me at [dave@urth.org](mailto:dave@urth.org).

- [My GitHub profile <i class="fab fa-github"
  aria-hidden="true"></i>](https://github.com/autarch/)
- [The houseabsolute organization](https://github.com/houseabsolute/) contains most of my code for
  easier collaboration.
- [House Absolute(ly Pointless)](https://blog.urth.org/), my (mostly) technical blog.

</div>

## Experience

### [MongoDB](https://www.mongodb.com/) {.resume-sub-heading}

**Senior Software Engineer, 5/2022 - present**

### [ActiveState Software Inc.](https://www.activestate.com/) {.resume-sub-heading}

**Team Lead, Senior Software Engineer, 2/2017 – 10/2021**

- Led a team providing **backend services**, including a key **REST API** for our SaaS product's
  backend, using **Go**, **Swagger**, **Postgres**, and **Kafka**.
- Built services that ran on **AWS** with **Docker**, **Kubernetes**, and **RDS**.
- Improved team workflow by introducing **code review**, **testing**, and an **ordered backlog** of
  work.
- **Provided mentoring for junior developers and interns**.
- **Worked closely with other teams and product management** to **understand user needs**, **write
  design docs**, **design our APIs**, **plan changes and rollouts**, and address bugs and
  performance issues that affected the product.
- Led **blame-free postmortems** for outages and other severe incidents.
- Engaged in quarterly planning with the CTO, Director of Engineering, and product team to **define
  my team's OKRs and KPIs based on customer and company needs**.
- Wrote significant **engineering department documentation**, including rewriting our FOSS usage and
  release policy with the CTO and CEO.
- Led **technical hiring** by helping **define our hiring and onboarding processes for engineers**
  while the company grew from approximately 15 to 55 staff.

### [MaxMind, Inc.](https://www.maxmind.com/) {.resume-sub-heading}

**Software Engineering Team Lead, 7/2011 – 1/2017**

- Led the engineering team in the development of **websites and REST APIs**, **queue processing
  systems**, and **build tools** using **Modern Perl**, **Go**, **RabbitMQ**, and **Postgres**.
- Developed and supported new and old **services receiving hundreds of requests per second**.
- Provided **technical leadership** for the engineering team by defining our **development
  workflow** using **agile tools**, as well as our **code review** practices.
- Wrote the first **unit tests** at the company and later worked on **integration tests** as well
  our **production simulation** tools.
- Introduced **continuous integration**, initially with **Jenkins** and later with **TeamCity**.
- **Benchmarked and optimized** the test suite, bringing the run time from nearly an hour to about
  15 minutes.
- Created a a parallelizable **build system** to implement the entire build process for our line of
  [GeoIP2 databases](https://dev.maxmind.com/geoip/geoip2/downloadable/).
- Defined and documented the [MaxMind DB file format](https://maxmind.github.io/MaxMind-DB/),
  including writing a comprehensive spec for it, as well as participating in the development of
  client libraries in **Perl (XS)**, Python, Java, C#, PHP, and JavaScript.
- Created the **C** library for this file format,
  [libmaxminddb](https://github.com/maxmind/libmaxminddb), as well as the Perl library to write the
  format, [MaxMind::DB::Writer](https://github.com/maxmind/MaxMind-DB-Writer-perl), mostly written
  in C and XS.
- Developed and extended tools for our **development environment**, including **Git** hooks,
  linters, and tidiers.
- **Led all hiring** for technical staff, growing the engineering team from three to fifteen,
  including front-end and back-end developers, a sysadmin, and QA engineers.
- Created the **resume screening and interview process** used for all of these hires.

### [Thomson Reuters](https://www.reuters.com/) {.resume-sub-heading}

**Consulting Software Engineer, 11/2007 – 4/2011**

### [LiveText, Inc.](https://www.livetext.com/) {.resume-sub-heading}

**Senior Developer, 3/2007 – 11/2007**

### Socialtext, Inc.  {.resume-sub-heading}

**Senior Developer - Database Lead, 9/2004 – 3/2007**

### House Absolute Consulting {.resume-sub-heading}

**Sole Proprietor, 2/2002 – 9/2004**

### Various {.resume-sub-heading}

**Too Old to List, 1995 – 2002**

Do you really want to read about my TA position in Music Theory or my first programming jobs?

## FOSS Software

- I've created many FOSS projects. Here are a few highlights:
  - [precious](https://github.com/houseabsolute/precious) is a meta-linting code quality tool (a
    tool to run many linters and prettifiers) in **Rust**.
  - [ubi](https://github.com/houseabsolute/ubi) is a tool to install single-file binaries from
    GitHub releases, in **Rust**.
  - [omegasort](https://github.com/houseabsolute/omegasort) is a CLI tool for sorting text files
    written in **Go**.
  - I kicked off the **Perl DateTime Project** in the early 2000s, which developed a comprehensive
    suite of interoperating Perl libraries for dealing with dates and times. Distributions in the
    DateTime suite are under the
    [DateTime namespace on CPAN](https://metacpan.org/search?q=datetime).
- My [houseabsolute GitHub organization](https://github.com/houseabsolute?type=source) contains the
  vast majority of my projects.
- [My crates.io profile](https://crates.io/users/autarch).
- [My CPAN profile](https://metacpan.org/author/DROLSKY).

## Skills

- **Management and Leadership**: KPI and OKR creation, agile development, blame-free postmortems,
  development processes, technical hiring and onboarding, design docs, change/rollout planning
- **Languages**: Go, JavaScript, SQL, Pl/pgSQL, C, Rust, HTML, CSS, Perl (and XS)
- **Tools, Frameworks, and Protocols**: React, Bootstrap, Tailwind, Swagger, GraphQL, GRPC
- **Databases**: Postgres, MySQL, Redis, RDS, AWS
- **Operating Systems, Services and Deployment**: Linux, Docker, Kubernetes, Kafka, RabbitMQ,
  Prometheus, distributed tracing
- **CI systems**: GitHub Actions, CircleCI, Azure Pipelines, TeamCity, Jenkins
- **Other**: API design, database schema design, documentation writing, benchmarking and profiling,
  date and time standards, I18N and L10N, email parsing, Hugo

## Publications and Presentations

- LWN.net - [Perl 5.16 and beyond](https://lwn.net/Articles/487216/) - March 22, 2012
- For the Perl core, rewrote [perlootut](https://perldoc.perl.org/perlootut) from scratch and
  completely revised [perlobj](https://perldoc.perl.org/perlobj) for the Perl 5.16.0 release
  in 2012.
- Received a grant from The Perl Foundation to work on the
  [Moose distribution](https://metacpan.org/dist/Moose) documentation and revised all of the
  existing API docs, wrote new cookbook recipes, and wrote the
  [Moose::Manual](https://metacpan.org/dist/Moose/view/lib/Moose/Manual.pod) documentation from
  scratch.
- Co-authored
  [Embedding Perl in HTML with Mason](https://www.oreilly.com/library/view/embedding-perl-in/0596002254/)
  with Ken Williams from O'Reilly and Associates, published 10/2002. It is also
  [freely available online](https://masonbook.houseabsolute.com/book/).
- See [my complete list of publications]({{% ref "/publications/index.md"%}}).

I've presented at conferences around the world, with presentations ranging from 5-minute lightning
talks to all-day intensive classes.

- [My slides]({{% ref "/presentation-slides/index.md" %}})
- [My class descriptions]({{% ref "/classes/index.md" %}})

## Education

Wow, you read this far? Amazing!

### University of Minnesota, School of Music {.resume-sub-heading}

**1995 – 1997**

Master of Arts in Music Composition

### Bard College {.resume-sub-heading}

**1991 – 1995**

Bachelor of Arts in Music

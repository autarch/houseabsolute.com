---
title: Resume
author: Dave Rolsky
type: page
date: 2015-06-20T19:15:18+00:00
url: /resume/
---
<div class="web-only">
  <ul>
    <li><a href="mailto:dave@urth.org">dave@urth.org</a></li>
    <li>Minneapolis, MN (no to relocation, yes to some travel)</li>
  </ul>
</div>

## Quick Links

* [My GitHub profile <i class="fab fa-github" aria-hidden="true"></i>][6], but
  most of my code lives in the [houseabsolute organization][7] for easier
  collaboration.
* [House Absolute(ly Pointless)][8], my (mostly) technical blog

## The Highlights

* **Team lead** capable of providing technical leadership for a team, shaping
  the development workflow, providing mentoring for other staff, and managing
  a team.
* Able to **gather requirements** and **communicate clearly about technical
  problems**.
* A proven **track record of
  [hiring](https://blog.urth.org/2019/07/11/a-technical-hiring-process-revisited/)**
  excellent developers.
* Creator of several handy
  [utilities](https://github.com/houseabsolute/precious) in
  [Rust](https://github.com/houseabsolute/ubi) and
  [Go](https://github.com/houseabsolute/omegasort).
* Author of Perl core **documentation** pages [perlootut][4] and [perlobj][5],
  and author of much of the [documentation for Moose][3], a Perl OO framework.
* Co-author of two O'Reilly books.
* **Prolific FOSS author**, of [a variety of projects][7] in Rust and Go as
  well as Perl's [DateTime.pm][1] library and [many other Perl modules][2].

I've been working as a professional software developer since 1998, starting
with Perl, and more recently focused on Go, with some JS and C in
there. I've also worked with SQL, webapps, REST APIs, and more.

I enjoy solving problems for humans. This means more than just "making it go",
it also means really understanding the needs of your users. I also have a
great interest in data. Solid data representation and handling is the key to
building powerful, flexible applications.

Over the years, I've created or contributed to hundreds of free software
projects and libraries. I've also written extensive technical documentation
and articles, co-written two books, and presented at many conferences,
including teaching two all-day classes.

I care greatly about the development process. Getting clear requirements,
breaking work up into small pieces, automated testing, good deployment tools,
QA, bug tracking, source control; all of these are crucial to building quality
software. Why build something that works if it doesn't do what your users
want, or if you can't maintain it?. Why fix a bug if you reintroduce it in the
next release? Software should provide value to users and get better over time,
not worse.

## Experience {#experience}

### [ActiveState Software Inc.][9] {.resume-sub-heading}

**Team Lead, Senior Software Engineer, 2/2017 - present**

When I began at ActiveState, I was the Team Lead for the Languages Team, which
produced binary builds of ActivePerl, ActivePython, and ActiveTcl for our
customers. Builds used a system written in Perl that built all the languages
on a variety of operating systems, including Linux, Windows, macOS, and
several big iron systems.

As the new Team Lead, I helped the team improve our workflow by introducing
**code review** and an **ordered backlog** of work. I also worked with the
rest of the company to **define future work**.

After we began work on the [ActiveState
Platform](https://platform.activestate.com/), my team developed several of the
key **backend services** for the platform, including the **REST API** for our
entire database of packages. This was done using **Go**, **Swagger**,
**Postgres**, and **Kafka**. All of our services run on **AWS** using **RDS**
for the database and **Docker** containers on **Kubernetes** for services and
jobs. We also developed the first version of the service that handled requests
for builds across all operating systems.

Since our services form the backbone of the ActiveState Platform, every other
technical team in the company is a customer for our services. I've **worked
closely with these other teams and Product Management** to **design our
APIs**, **write design docs**, **plan changes and rollouts**, and address bugs
and performance issues that affect the Platform.

I also work closely with the CTO, Director of Engineering, and Product team to
do quarterly planning. During this process we **define my team's OKRs and
KPIs**, as well as determine which projects to prioritize based on customer
and company needs.

In addition to my Team Lead responsibilities, I've also worked extensively on
our **Engineering department documentation** and rewrote our FOSS
usage/release policy.

I've been a leader in our **technical hiring**, helping **define our hiring
process for engineers**, as well as contributing to our **onboarding
process**.

### [MaxMind, Inc.][10] {.resume-sub-heading}

**Software Engineering Team Lead, 7/2011 - 1/2017**

At MaxMind, I led a team developing **websites and REST APIs**, **queue
processing systems**, and **build tools** using **Modern Perl**, **Go**,
**RabbitMQ**, and **Postgres**.

As Team Lead, I provided technical leadership for the engineering team. This
included defining our **development workflow** using **agile tools**, as well
as our **code review** practices (using GitHub Enterprise Pull Requests). I
also set standards for the engineering team including **coding standards** and
**testing practices**.

I wrote the first **unit tests** at the company and later worked on
**integration tests** as well our **production simulation** tools. I also
introduced **continuous integration**, initially with **Jenkins** and later
with **TeamCity**. As our test suite grew I also worked on **benchmarking and
optimizing** the test suite itself, bringing the run time form nearly an hour
to about 15 minutes.

One of the most interesting tools I created at MaxMind is a Perl module to
implement a parallelizable **build system** called [Stepford][11]. It is
similar to `make`, but with Perl classes as the main unit of work instead of
processes. This system was then used to implement the entire build process for
our line of [GeoIP2 databases][12].

I helped define and document the [MaxMind DB file format][13], including
writing a comprehensive spec for it, as well as participating in the
development of client libraries in **Perl (XS)**, Python, Java, C#, PHP, and
JavaScript. I also created the **C** API for this format, [libmaxminddb][14],
as well as the Perl module to write the format, [`MaxMind::DB::Writer`][15],
which is mostly written in C and XS.

To help improve developer productivity, I developed and extended tools for our
**development environment**, including **Git** hooks, `Perl::Critic` policies,
and `Code::TidyAll`, a multi-language linting and tidying tool.

As Team Lead, I led all **hiring** for technical staff, growing the
engineering team from three to fifteen, including front-end and back-end
developers, a sysadmin, and QA engineers. I also developed the **resume
screening and interview process** used for all of these hires.

### [Thomson Reuters][16] {.resume-sub-heading}

**Consulting Software Engineer, 11/2007 - 4/2011**

### [LiveText, Inc.][17] {.resume-sub-heading}

**Senior Developer, 3/2007 - 11/2007**

### Socialtext, Inc. {.resume-sub-heading}

**Senior Developer - Database Lead, 9/2004 - 3/2007**

### House Absolute Consulting {.resume-sub-heading}

**Sole Proprietor, 2/2002 - 9/2004**

### Various {.resume-sub-heading}

**Too Old to List, 1995 - 2002**

Do you really want to read about my TA position in Music Theory or my first
programming jobs?

## Publications {#publications}

### Articles {.resume-sub-heading}

* Perl Advent Calendar - [The Grinch's Well-Tested Second Attempt][19] -
  December 24, 2016
* Perl Advent Calendar - [Building Santa's Naughty and Nice List with
  Stepford][20] - December 16, 2015
* LWN.net - [Perl 5.16 and beyond][21] - March 22, 2012
* LWN.net - [The Perl 5 release process][22] - March 7, 2012

### Perl Core Documentation {.resume-sub-heading}

I wrote [perlootut][4] from scratch and revised [perlobj][5] from the ground
up for the Perl 5.16.0 release in 2012. I also made major edits to several
other documents in the Perl core, including [perlhack][23], [perlhacktut][24],
[perlhacktips][25], and [perlsource][26].

### [Moose documentation][3] {.resume-sub-heading}

In 2009 I received a grant from The Perl Foundation to work on the
documentation for Moose, an OO system for Perl. I revised all of the existing
API docs, wrote new cookbook recipes, and wrote the Moose::Manual
documentation from scratch.

### RT Essentials {.resume-sub-heading}

I contributed two chapters to this book. For more details see the [O'Reilly
page for the book][27].

### Embedding Perl in HTML with Mason {.resume-sub-heading}

This book, which I co-authored with Ken Williams, is available from [O'Reilly
and Associates][28], and was published in October of 2002. It is also freely
available in an [online version][29].

## Presentations {#speaking}

I have presented at many conferences around the world. These presentations
have ranged from 5 minute lightning talks to all day intensive classes
featuring extensive coding exercises as part of the class.

See [my list of slides][30] and [class descriptions][31] for more details.

## FOSS Software {#foss}

Besides contributing patches to hundreds of projects and libraries, I have
created and/or maintained a number of FOSS projects. Here are a few
highlights:

* [detest](https://pkg.go.dev/github.com/houseabsolute/detest) is a test
  assertion library for **Go**.
* [omegasort](https://github.com/houseabsolute/omegasort) is a CLI tool for
  sorting text files written in **Go**.
* [precious](https://github.com/houseabsolute/precious) is a meta-linting code
  quality tool (a tool to run many linters and prettifiers) in **Rust**.
* [ubi](https://github.com/houseabsolute/ubi) is a tool to install single file
  binaries from GitHub releases, in **Rust**.
* I kicked off the **Perl DateTime Project** in the early 2000s, which
  developed a comprehensive suite of inter-operating Perl modules for dealing
  with dates and times. Distributions in the DateTime suite are under the
  [DateTime][33] namespace on CPAN

See my [houseabsolute GitHub
organization](https://github.com/houseabsolute?type=source) for the vast
majority of my projects.

## Other Skills

It's hard to jam everything I've ever done into a list of jobs and
projects. Here's a list of other things I'd be happy to talk about in
interviews:

* CI systems, including GitHub Actions, CircleCI, Azure Pipelines, and others.
* Rust, it's super fun but I've yet to use it for paid work.
* SQL, PL/pgSQL, and Postgres extensions.
* Date and time standards.
* Database schema design.
* HTML, CSS (including Less & Sass), Bootstrap, JavaScript, and React.
* I18N and L10N.
* Email parsing and generation.

## Education

Wow, you read this far? Amazing!

### University of Minnesota, School of Music {.resume-sub-heading}

**1995-1997**

Master of Arts in Music Composition

### Bard College {.resume-sub-heading}

**1991-1995**

Bachelor of Arts in Music

 [1]: https://metacpan.org/pod/DateTime
 [2]: http://metacpan.org/author/DROLSKY
 [3]: https://metacpan.org/release/Moose
 [4]: http://perldoc.perl.org/perlootut.html
 [5]: http://perldoc.perl.org/perlobj.html
 [6]: https://github.com/autarch/
 [7]: https://github.com/houseabsolute/
 [8]: http://blog.urth.org/
 [9]: https://www.activestate.com/
 [10]: https://www.maxmind.com/
 [11]: https://metacpan.org/release/Stepford
 [12]: http://dev.maxmind.com/geoip/geoip2/downloadable/
 [13]: http://maxmind.github.io/MaxMind-DB/
 [14]: https://github.com/maxmind/libmaxminddb
 [15]: https://github.com/maxmind/MaxMind-DB-Writer-perl
 [16]: http://www.reuters.com/
 [17]: http://www.livetext.com/
 [18]: http://www.socialtext.com/
 [19]: http://perladvent.org/2016/2016-12-24.html
 [20]: http://perladvent.org/2015/2015-12-16.html
 [21]: http://lwn.net/Articles/487216/
 [22]: http://lwn.net/Articles/485569/
 [23]: http://perldoc.perl.org/perlhack.html
 [24]: http://perldoc.perl.org/perlhacktut.html
 [25]: http://perldoc.perl.org/perlhacktips.html
 [26]: http://perldoc.perl.org/perlsource.html
 [27]: http://www.oreilly.com/catalog/rtessentials/
 [28]: http://www.oreilly.com/catalog/perlhtmlmason/
 [29]: http://masonbook.houseabsolute.com/book/
 [30]: /presentation-slides/
 [31]: /classes/
 [32]: http://moose.perl.org/
 [33]: https://metacpan.org/search?q=datetime
 [34]: https://metacpan.org/release/Catalyst-Runtime
 [35]: http://mojolicious.org/

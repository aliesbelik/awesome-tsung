# Awesome Tsung [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="assets/images/tsung-logo.svg" align="right" width="260" alt="Tsung">](http://tsung.erlang-projects.org/)

A curated collection of resources covering all aspects of load-testing using [Tsung](http://tsung.erlang-projects.org/) and related stuff: plugins, integrations, testing techniques, devops practicies, etc.

> [Tsung](http://tsung.erlang-projects.org/) is an open-source multi-protocol distributed load testing tool, developed in Erlang.

## Contents

- [Official Resources](#official-resources)
- [Getting Started](#getting-started)
- [Tutorials](#tutorials)
- [Distributed Testing](#distributed-testing)
- [Presentations](#presentations)
- [Plugins](#plugins)
- [Deployment](#deployment)
- [Tips & Tricks](#tips--tricks)
- [Community](#community)
  - [Blogs](#blogs)
  - [Forums](#forums)
  - [Newsletters](#newsletters)
  - [Q&A](#qa)
- [Related](#related)
  - [Awesome Lists](#awesome-lists)

## Official Resources

- [Homepage](http://tsung.erlang-projects.org/)
- [Downloads](http://tsung.erlang-projects.org/dist/)
- [Documentation](http://tsung.erlang-projects.org/user_manual/index.html)
- [Source code](https://github.com/processone/tsung/)
- [Mailing list](https://lists.process-one.net/mailman/listinfo/tsung-users)

## Getting Started

- [Load Testing using Tsung](https://medium.com/helpshift-engineering/load-testing-using-tsung-ef26a662929b)
- [Test the Performance and Scalability of Your Web Applications with Tsung](https://web.archive.org/web/20160826102121/https://beebole.com/blog/erlang/test-performance-and-scalability-of-your-web-applications-with-tsung/)
- [Introduction to Load Testing with Tsung](https://erlangcentral.org/wiki/Introduction_to_Load_Testing_with_Tsung)
- [Tsung: Нагрузочное тестирование Web-приложений](https://habr.com/en/post/132459/) - Tsung: Load testing of web applications *(Russian)*.
- [Load Testing with Tsung: Pros & Cons](https://getcookie.wordpress.com/2013/02/13/load-testing-with-tsung/)
- [Benchmarking Websites with ab and Tsung](https://www.rsreese.com/benchmarking-websites-with-ab-and-tsung/)
- [Installing and Initial setup of Tsung Load Testing CentOS](http://whatizee.blogspot.com/2015/01/installing-and-initial-setup-of-tsung_21.html)

## Tutorials

- Load Testing with Tsung Quick Start @ Canonical:
  - [part 1](https://web.archive.org/web/20150905161702/http://voices.canonical.com/isd/2010/11/14/load-testing-with-tsung-quick-start/)
  - [part 2](https://web.archive.org/web/20150905162148/http://voices.canonical.com/isd/2010/12/10/tsung-quick-start-part-2/)
- [Building a test setup for load testing with Tsung](https://hml.io/2015/08/04/loadtesting-with-tsung-and-multiple-ips/) - Multiple IPs for using different sources and destinations for web requests.
- [Running Tsung against opentaps server](https://opentaps.org/docs/Running_Tsung_against_opentaps_server)
- [Building a Load Test with Tsung for a Login and Post Session with dynamic url-encoded variables](https://www.innoq.com/en/blog/building-a-load-test-with-tsung/) - Blogpost covers a step-by-step instruction on how to build a loadtest for a Ruby on Rails app with a login and post session and dynamic variables with Tsung.
- Series about building a high-performance web cluster @ Stefanie Forrester:
  - [part 1](https://web.archive.org/web/20190112103031/http://dak1n1.com/blog/14-http-load-generate/) - How to Generate Millions of HTTP Requests.
  - [part 2](https://web.archive.org/web/20190123062716/http://dak1n1.com/blog/12-nginx-performance-tuning/) - Tuning Nginx for Best Performance.
  - [part 3](https://web.archive.org/web/20180826004438/http://dak1n1.com/blog/13-load-balancing-lvs/) - Building a Load-Balancing Cluster with LVS.

## Distributed Testing

- [An introduction to distributed load testing with tsung](https://www.brightbox.com/blog/2014/11/07/distributed-load-testing-with-tsung/)
- [Distributed load testing with Tsung](https://raymii.org/s/articles/Basic_Website_load_testing_with_Tsung.html)

## Presentations

- [Introduction to Load Testing with Tsung](https://github.com/erszcz/euc-2014) - Presentation for Erlang User Conference 2014 @ Radek Szymczyszyn.
- [Load Testing with Tsung](https://cs291.com/slides/2019/09_tsung/) - Slides for Scalable Internet Services (CS291A) course @ Bryce Boe.
- [Easy distributed load test with Tsung](https://github.com/ngocdaothanh/tsart) - Presentation @ Ngoc Dao.

## Plugins

- [Writing a Tsung plugin](http://web.archive.org/web/20150208112949/http://www.process-one.net/en/wiki/Writing_a_Tsung_plugin/) - A simple tutorial on writing a Tsung plugin from official documentation.
- [Собственный плагин tsung](http://lin-techdet.blogspot.com/2013/04/tsung.html) - Creating custom Tsung plugin *(Russian)*.
- [tsung_ws](https://github.com/wulczer/tsung_ws) - Tsung plugin for WebSockets.
- [tsung-gis](https://github.com/rodo/tsung-gis) - Tsung module for load-testing GIS systems.

## Deployment

- [ansible-tsung](https://github.com/rodo/ansible-tsung) - Ansible playbooks for Tsung deployment.
- [puppet-tsung](https://github.com/rodo/puppet-tsung) - Puppet module to install Tsung from source.

## Tips & Tricks

- [tsung-tricks](https://github.com/rodo/tsung-tricks) - Miscellanous tricks and modules to use with Tsung @ Rodolphe Quiédeville.

## Community

### Blogs

### Forums

### Newsletters

### Q&A

- [Tsung-users Archives](http://lists.process-one.net/pipermail/tsung-users/)
- [Tsung @ Stack Overflow](https://stackoverflow.com/questions/tagged/tsung)

## Related

### Awesome Lists

- [Awesome](https://github.com/sindresorhus/awesome) - The original awesome list of awesome lists.
- [Awesome Awesomeness](https://github.com/bayandin/awesome-awesomeness) - A curated list of amazingly awesome awesomeness.
- [Awesome Software Quality](https://github.com/ligurio/awesome-software-quality) - A list of free software testing and verification resources.
- [Awesome Testing](https://github.com/TheJambo/awesome-testing) - A curated list of testing resources.
- [Awesome Page Speed Metrics](https://github.com/csabapalfi/awesome-pagespeed-metrics) - Metrics to help understand page speed and user experience.
- [Awesome Web Performance Optimization](https://github.com/davidsonfellipe/awesome-wpo) - A curated list of Web Performance Optimization.
- [Awesome Scalability](https://github.com/binhnguyennus/awesome-scalability) - The Patterns of Scalable, Reliable, and Performant Large-Scale Systems.
- [Awesome Site Reliability Engineering](https://github.com/dastergon/awesome-sre) - A curated list of Site Reliability and Production Engineering resources.
- [Awesome JMeter](https://github.com/aliesbelik/awesome-jmeter) - Open-source load testing and performance measurement tool, written in Java.
- [Awesome Gatling](https://github.com/aliesbelik/awesome-gatling) - Open-source load and performance testing framework based on Scala, Akka and Netty.
- [Awesome k6](https://github.com/k6io/awesome-k6) - Open-source, developer-centric performance monitoring and load testing solution.
- [Awesome Locust](https://github.com/aliesbelik/awesome-locust) - Open-source scalable load-testing framework written in Python.

## Contributing

Contributions are welcome!<br>
Please take a look at the [contribution guidelines](CONTRIBUTING.md) first.

<a rel="license" href="https://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://licensebuttons.net/l/by/4.0/88x31.png" /></a><br />

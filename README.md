# Awesome Tsung [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<!--lint ignore double-link-->
[<img src="assets/images/tsung-logo.svg" align="right" width="260" alt="Tsung">](http://tsung.erlang-projects.org/)
<!--lint ignore double-link-->
A curated collection of resources covering all aspects of load testing using [Tsung](http://tsung.erlang-projects.org/) and related stuff: plugins, integrations, testing techniques, DevOps practices, etc.
<!--lint ignore double-link-->
> [Tsung](http://tsung.erlang-projects.org/) is an open-source multi-protocol distributed load testing tool, developed in Erlang.

## Contents

- [Official Resources](#official-resources)
- [Getting Started](#getting-started)
- [Tutorials](#tutorials)
- [Distributed Testing](#distributed-testing)
- [Tools](#tools)
  - [Plugins](#plugins)
  - [Configuration Management](#configuration-management)
  - [Distributed](#distributed)
  - [Wrappers](#wrappers)
  - [Miscellaneous](#miscellaneous)
- [Tips & Tricks](#tips--tricks)
- [Talks](#talks)
- [Reference Projects](#reference-projects)
- [Community](#community)
- [Related](#related)
  - [Awesome Lists](#awesome-lists)
  - [Other](#other)

## Official Resources
<!--lint ignore double-link-->
- [Homepage](http://tsung.erlang-projects.org/)
- [Downloads](http://tsung.erlang-projects.org/dist/)
- [Documentation](http://tsung.erlang-projects.org/user_manual/index.html)
- [Source code](https://github.com/processone/tsung/)

## Getting Started

- [Load Testing using Tsung](https://medium.com/helpshift-engineering/load-testing-using-tsung-ef26a662929b)
- [Test the Performance and Scalability of Your Web Applications with Tsung](https://web.archive.org/web/20160826102121/https://beebole.com/blog/erlang/test-performance-and-scalability-of-your-web-applications-with-tsung/)
- [Tsung: Нагрузочное тестирование Web-приложений](https://habr.com/en/post/132459/) - Tsung: Load testing of web applications :ru:.
- [Load Testing with Tsung: Pros & Cons](https://getcookie.wordpress.com/2013/02/13/load-testing-with-tsung/)
- [Benchmarking Websites with ab and Tsung](https://www.rsreese.com/benchmarking-websites-with-ab-and-tsung/)
- [Installing and Initial setup of Tsung Load Testing CentOS](http://whatizee.blogspot.com/2015/01/installing-and-initial-setup-of-tsung_21.html)

## Tutorials

- Load Testing with Tsung Quick Start @ Canonical:
  - [part 1](https://web.archive.org/web/20150905161702/http://voices.canonical.com/isd/2010/11/14/load-testing-with-tsung-quick-start/)
  - [part 2](https://web.archive.org/web/20150905162148/http://voices.canonical.com/isd/2010/12/10/tsung-quick-start-part-2/)
- [Building a test setup for load testing with Tsung](https://hml.io/2015/08/04/loadtesting-with-tsung-and-multiple-ips/) - Multiple IPs for using different sources and destinations for web requests.
- [Running Tsung against opentaps server](https://docs.opentaps.org/docs/index.php/Running_Tsung_against_opentaps_server)
- [Building a Load Test with Tsung for a Login and Post Session with dynamic url-encoded variables](https://www.innoq.com/en/blog/building-a-load-test-with-tsung/) - Blogpost covers a step-by-step instruction on how to build a load test for a Ruby on Rails app with a login and post session and dynamic variables with Tsung.
- Series about building a high-performance web cluster @ Stefanie Forrester:
  - [part 1](http://dak1n1.com/blog/14-http-load-generate/) - How to Generate Millions of HTTP Requests.
  - [part 2](http://dak1n1.com/blog/12-nginx-performance-tuning/) - Tuning Nginx for Best Performance.
  - [part 3](http://dak1n1.com/blog/13-load-balancing-lvs/) - Building a Load-Balancing Cluster with LVS.

## Distributed Testing

- [An introduction to distributed load testing with tsung](https://www.brightbox.com/blog/2014/11/07/distributed-load-testing-with-tsung/)
- [Distributed load testing with Tsung](https://raymii.org/s/articles/Basic_Website_load_testing_with_Tsung.html)
- [Easy distributed load test with Tsung](https://github.com/ngocdaothanh/tsart) - Presentation @ Ngoc Dao.

## Tools

### Plugins

- [Writing a Tsung plugin](http://web.archive.org/web/20150208112949/http://www.process-one.net/en/wiki/Writing_a_Tsung_plugin/) - A simple tutorial on writing a Tsung plugin from official documentation.
- [Собственный плагин tsung](http://lin-techdet.blogspot.com/2013/04/tsung.html) - Creating custom Tsung plugin :ru:.
- [tsung_ws](https://github.com/wulczer/tsung_ws) - Tsung plugin for WebSockets.
- [tsung-gis](https://github.com/rodo/tsung-gis) - Tsung module for load testing GIS systems.
- [tsung_dns](https://github.com/reith/tsung_dns) - DNS testing plugin for Tsung.

### Configuration Management

- [ansible-tsung](https://github.com/rodo/ansible-tsung) - Ansible playbooks for Tsung deployment.
- [puppet-tsung](https://github.com/rodo/puppet-tsung) - Puppet module to install Tsung from source.
- [tsung-helm-chart](https://github.com/timran1/tsung-helm-chart) - Helm chart to deploy Tsung.
- [tsung-pack](https://github.com/mkornatz/tsung-pack) - Tsung load testing toolkit.

### Distributed

- [tsung-in-swarm](https://github.com/ffantasy/tsung-in-swarm) - Tsung distributed stress testing in docker swarm.
- [tsung-docker](https://github.com/ddragosd/tsung-docker) - Docker image to run Tsung distributed.
- [tsung_rsh](https://github.com/weibomobile/tsung_rsh) - Replace SSH tunnel for Tsung clusters.
- [tsung-in-kubernetes](https://github.com/kubeup/tsung-in-kubernetes) - Running Tsung in Kubernetes.

### Wrappers

- [shang_tsung](https://github.com/amilkr/shang_tsung) - A DSL and web wrapper for Tsung.

### Miscellaneous

- [curl2tsung](https://github.com/perfectayush/curl2tsung) - A simple utility to convert a curl request to Tsung's xml request.

## Tips & Tricks

- [tsung-tricks](https://github.com/rodo/tsung-tricks) - Miscellanous tricks and modules to use with Tsung @ Rodolphe Quiédeville.

## Talks

- [Introduction to Load Testing with Tsung](https://github.com/erszcz/euc-2014) - Presentation for Erlang User Conference 2014 @ Radek Szymczyszyn.

## Reference Projects

- [Load Testing with Tsung](https://cs291.com/slides/2021w/10_tsung/) - Slides for Scalable Internet Services (CS291A) course @ Bryce Boe.
- [Load-testing a Rails app with Tsung on AWS Elastic Beanstalk](https://justinppearson.com/projects.html#load-testing-a-rails-app-on-aws-elastic-beanstalk) - Materials for Scalable Internet Services (CS291A) course @ Justin Pearson.

## Community

- [`tsung` on Stack Overflow](https://stackoverflow.com/questions/tagged/tsung)
- [Tsung-users Archives](https://web.archive.org/web/20161021032702/http://lists.process-one.net/pipermail/tsung-users/) 💀

## Related

### Awesome Lists

- [Awesome Software Quality](https://github.com/ligurio/software-quality-wiki) - A list of free software testing and verification resources.
- [Awesome Testing](https://github.com/TheJambo/awesome-testing) - A curated list of testing resources.
- [Awesome JMeter](https://github.com/aliesbelik/awesome-jmeter) - Open-source load testing and performance measurement tool, written in Java.
- [Awesome Gatling](https://github.com/aliesbelik/awesome-gatling) - Open-source load and performance testing framework based on Scala, Akka and Netty.
- [Awesome k6](https://github.com/grafana/awesome-k6) - Open-source, developer-centric performance monitoring and load testing solution.
- [Awesome Locust](https://github.com/aliesbelik/awesome-locust) - Open-source scalable load testing framework written in Python.

### Other

- [How They Load Test](https://github.com/aliesbelik/how-they-load) - A curated collection of publicly available resources on how companies around the world perform load testing.
- [Load Testing Toolkit](https://github.com/aliesbelik/load-testing-toolkit) - Collection of open-source tools for debugging, benchmarking, load and stress testing your code or services.

## Contributing

Contributions are welcome!<br>
Please take a look at the [CONTRIBUTING](CONTRIBUTING.md) guidelines first.

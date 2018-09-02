# awesome-list

My Awesome List of anything cool that my curious mind finds interesting

- [CI/CD](#continious-integration)
  - [Circle-CI](#circle-ci)
  - [Concourse](#concourse)
  - [Jenkins](#jenkins)
- [Docker](#docker)
  - [RaspberryPi ARM Images](#raspberrypi-arm-images)
  - [Docker Image Repositories](#docker-image-repositories)
  - [Docker Awesome Lists](#docker-awesome-lists)
  - [Docker Storage](#docker-storage)
  - [OpenFaas](#openfaas)
- [DynamoDB](#dynamodb)
  - [DynamoDB Docs](#dynamodb-docs)
  - [DynamoDB Best Practices](#dynamodb-best-practices)
  - [DynamoDB General Info](#dynamodb-general-info)
- [Elasticsearch](#elasticsearch)
  - [Elasticsearch Documentation](#elasticsearch-documentation)
  - [Elasticsearch Cheetsheets](#elasticsearch-cheetsheets)
  - [Elasticsearch Blogs](#elasticsearch-blogs)
  - [Elasticsearch Tools](#elasticsearch-tools)
- [Environment Setups](#environment-setups)
- [Knowledge Base](#knowledge-base)
  - [How does HTTPS Work](#kb-https)
- [MongoDB](#mongodb)
  - [MongoDB Monitoring Tools](#mongodb-monitoring-tools)
  - [MongoDB Scripts](#mongodb-scripts)
- [Programming](#programming)
  - [Golang](#golang)
  - [Java](#java)
  - [Python](#python)
  - [Ruby](#ruby)
- [Sysadmin References](#sysadmin-references)
- [VPN](#vpn)
  - [VPN HowTo](#vpn-howto)
- [Web Frameworks](#web-frameworks)
  - [Python Flask](#python-flask)

## Awesome Lists
- [Awesome ChatOps](https://github.com/exAspArk/awesome-chatops)
- [Awesome Scalability](https://github.com/binhnguyennus/awesome-scalability)

## Authentication
- [Nginx ES and Kibana Proxy with LDAP](https://mapr.com/blog/how-secure-elasticsearch-and-kibana/)

## Docker

#### RaspberryPi ARM Images:
- [arm32v6/alpine:edge](https://hub.docker.com/r/arm32v6/alpine/)
- [arm32v6/golang:alpine](https://hub.docker.com/r/arm32v6/golang/)
- [arm32v6/haproxy:alpine](https://hub.docker.com/r/arm32v6/haproxy/)
- [arm32v6/node:alpine](https://hub.docker.com/r/arm32v6/node/)
- [arm32v6/openjdk:alpine](https://hub.docker.com/r/arm32v6/openjdk/)
- [arm32v6/postgres:alpine](https://hub.docker.com/r/arm32v6/postgres/)
- [arm32v6/python:2.7-alpine3.6](https://hub.docker.com/r/arm32v6/python/)
- [arm32v6/python:3.6-alpine3.6](https://hub.docker.com/r/arm32v6/python/)
- [arm32v6/rabbitmq:alpine](https://hub.docker.com/r/arm32v6/rabbitmq/)
- [arm32v6/redis:alpine](https://hub.docker.com/r/arm32v6/redis/)
- [arm32v6/ruby:alpine3.6](https://hub.docker.com/r/arm32v6/ruby/)
- [arm32v6/tomcat:alpine](https://hub.docker.com/r/arm32v6/tomcat/)
- [arm32v6/traefik:latest](https://hub.docker.com/r/arm32v6/traefik/)
- [arm32v7/debian:lates](https://hub.docker.com/r/arm32v7/debian/)
- [hypriot/rpi-redis](https://hub.docker.com/r/hypriot/rpi-redis/)
- [jixer/rpi-mongo](https://github.com/jixer/rpi-mongo)
- [alexellis/armhf](https://github.com/alexellis/docker-arm/tree/master/images/armhf)
- [zeiot: rpi-prometheus stack](https://github.com/zeiot)
- [larmog](https://hub.docker.com/u/larmog/)
- [Rpi MongoDB](https://github.com/andresvidal/rpi3-mongodb3)
- [ARM Swarm](https://github.com/armswarm)

#### Docker Image Repositories
- [Docker Hub: arm32v6](https://hub.docker.com/u/arm32v6/)
- [Docker Hub: armv7](https://hub.docker.com/u/armv7/)
- [Github: Luvres Armhf](https://github.com/luvres/armhf)
- [Apache/PHP7 on Alpine](https://github.com/ulsmith/alpine-apache-php7)
- [Tomcat on Alpine](https://github.com/docker-library/tomcat/blob/master/8.0/jre8-alpine/Dockerfile)
- [Nginx (jwilder)](https://github.com/jwilder/nginx-proxy)
- [Alpine Images (smebberson)](https://github.com/smebberson/docker-alpine)
- [SameerSbn](https://hub.docker.com/u/sameersbn/)
- [Linuxserver.io](https://hub.docker.com/u/linuxserver/)
- [Apache-PHP5](https://hub.docker.com/r/nimmis/alpine-apache-php5/)

#### Docker-Awesome-Lists
- [Java Docker Services](https://github.com/AdamBien/docklands)
- [shouse Docker Awesome List](https://gist.github.com/shouse/a14c44e97a2cd2a1f030)

#### Docker Blogs:
- [Whoami used in Traefik Docs](https://hub.docker.com/r/emilevauge/whoami/)
- [Sqlite with Docker](https://github.com/spartakode/my-docker-repos/blob/master/sqlite3/Dockerfile)
- [Rails with Postgres and Redis](https://github.com/mookjp/rails-docker-example)
- [Async Tasks with Flask and Redis](https://testdriven.io/asynchronous-tasks-with-flask-and-redis-queue)
- [Flask and Postgres](https://github.com/davidmukiibi/docker-flask)
- [Elastic Beats on RaspberryPi](http://ict.renevdmark.nl/2016/07/05/elastic-beats-on-raspberry-pi/)

#### Docker Storage
- [Rancher Convoy](https://github.com/rancher/convoy)
- [Flocker](https://flocker.readthedocs.io/en/latest/flocker-features/storage-backends.html#supported-backends)
- [EMC ScaleIO](http://node.mu/2017/06/30/scaleio-on-ubuntu-xenial/)
- [RexRay Ceph with Ansible](https://github.com/lucj/swarm-rexray-ceph)

#### OpenFaas:
- [FaaS Releases](https://github.com/openfaas/faas/releases)

#### Prometheus / Grafana on Swarm:
- [StefanProdan - SwarmProm](https://github.com/stefanprodan/swarmprom)
- [Monitoring with Prometheus](https://medium.com/@soumyadipde/monitoring-in-docker-stacks-its-that-easy-with-prometheus-5d71c1042443)
- [UschtWill - Prometheus Grafana Elastalert](https://github.com/uschtwill/docker_monitoring_logging_alerting)
- [Chmod-Org Promethus with Blackbox](https://github.com/chmod666org/docker-swarm-prometheus)

## Continious Integration:

#### Circle-CI
- [PHP with Circle-CI](https://circleci.com/docs/1.0/language-php/)

#### Concourse
- [Setup Concourse Environment with Docker](https://concourse.ci/docker-repository.html)
- [Getting Started with Concourse and Docker](https://blog.anynines.com/getting-started-with-concourse-ci-and-docker/)

## Email

## Email Server Setups
- [Postfix Dovecot MySQL Virtual Users Postfixadmin](https://linuxize.com/post/set-up-an-email-server-with-postfixadmin/)

## Great Blogs

- [Exratione.com](https://www.exratione.com/blog/)
- [Joelabrahamsson.com](http://joelabrahamsson.com/elasticsearch-101/)
- [Benjamin Cane](http://bencane.com/)
- [Michael Herman](http://mherman.org/)

#### Jenkins
- [Modess - PHP with Jenkins](https://modess.io/jenkins-php/)
- [CI/CD Nodejs Tutorial with Jenkins](https://code.tutsplus.com/tutorials/setting-up-continuous-integration-continuous-deployment-with-jenkins--cms-21511)
- [CI/CD Nodejs Tutorial with Jenkins @medium](https://medium.com/@mosheezderman/how-to-set-up-ci-cd-pipeline-for-a-node-js-app-with-jenkins-c51581cc783c)

#### Travis-CI
- [Getting Started with Travis-CI (Original Docs)](https://docs.travis-ci.com/user/getting-started/)
- [Getting Started with Travis-CI (dwyl - nodejs)](https://github.com/dwyl/learn-travis)
- [Blog Site with Travis-CI (Python)](https://matthewmoisen.com/blog/how-to-set-up-travis-ci-with-github-for-a-python-project/)
- [Build Tests with Python on Travis-CI](https://github.com/softwaresaved/build_and_test_examples/blob/master/travis/HelloWorld.md)
- [Moving app with Travis-CI](https://www.raywenderlich.com/109418/travis-ci-tutorial)

#### LambCI
- [LambCI](https://github.com/lambci/lambci)

## DynamoDB

#### DynamoDB Docs

- [AWS DynamoDB: SQL to NoSQL](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/SQLtoNoSQL.ReadData.Query.html)

#### DynamoDB Best Practices

- [Choosing the Right Partition Key](https://aws.amazon.com/blogs/database/choosing-the-right-dynamodb-partition-key/)
- [10 Things you should know](https://cloudacademy.com/blog/amazon-dynamodb-ten-things/)

#### DynamoDB General Info

- [Understanding DynamoDB](https://medium.com/@yaofei/understand-dynamodb-b278f718ddb8)

## Elasticsearch

#### Elasticsearch Documentation
- [General Recommendation](https://www.elastic.co/guide/en/elasticsearch/reference/current/general-recommendations.html)
- [How Many Shards in my Cluster](https://www.elastic.co/blog/how-many-shards-should-i-have-in-my-elasticsearch-cluster)
- [Managing Time-Based Indices Efficiently](https://www.elastic.co/blog/managing-time-based-indices-efficiently)
- [Elasticsearch Best Practices (Bonsai.io)](https://bonsai.io/2016/01/11/ideal-elasticsearch-cluster)
- [AWS ES - Scaling up my Domain](https://aws.amazon.com/premiumsupport/knowledge-center/elasticsearch-scale-up/)

#### Elasticsearch Cheetsheets:
- [My ES Cheatsheet](https://gist.github.com/ruanbekker/e8a09604b14f37e8d2f743a87b930f93)

#### Elasticsearch Blogs
- [Maximize Elasticsearch Indexing Performance](https://qbox.io/blog/maximize-guide-elasticsearch-indexing-performance-part-1)
- [Autoritative Guide to ES Performance Tuning](https://qbox.io/blog/authoritative-guide-elasticsearch-performance-tuning-part-1)

#### Elasticsearch Tools
- [Export Data from ES to ES](https://github.com/mallocator/Elasticsearch-Exporter)

## Environment Setups:
- [Golang](https://medium.com/aishik/install-golang-the-right-way-4743fee9255f)

## Knowledge Base

## KB HTTPS
- [How does HTTPS work (Miguel Grinberg)](https://blog.miguelgrinberg.com/post/running-your-flask-application-over-https)

## Linuxkit:
- [Getting Started with Linuxkit](https://medium.com/aishik/getting-started-with-linuxkit-and-moby-project-ff7121c4e321)

## Metrics:
- [AppMetrics with Flask](https://github.com/avalente/appmetrics)
- [Scales: Metrics for Python](https://github.com/Cue/scales)
- [Graphite: Python Flask Metrics](https://pypi.org/project/graphite-pymetrics/)

## MongoDB:
- [Setup MongoDB Cluster](https://linode.com/docs/databases/mongodb/build-database-clusters-with-mongodb/)
- [MongoDB Scripts](https://github.com/AD7six/mongo-scripts)
- [MongoDB Monitoring Tools](https://docs.mongodb.com/v2.4/administration/monitoring/#self-hosted-monitoring-tools)

## Programming

#### Golang:
- [Golang Tutorials](http://golangtutorials.blogspot.co.za/2011/05/table-of-contents.html)
- [Golang Wiki](https://github.com/golang/go/wiki)

#### Java:
- [Java Spring Boot Examples](https://wiki.ruanbekker.com/index.php/Java_Spring_Boot_App_Examples)

#### Python

#### Ruby:
- [Learn Ruby: Learn Ruby the Hard Way](https://learnrubythehardway.org/book)
- [Learn Ruby: Ruby for Beginners](http://ruby-for-beginners.rubymonstas.org/index.html)
- [Learn Ruby: Launch School](https://launchschool.com/books/ruby/read/loops_iterators#forloops)
- [Learn Ruby: Arrays](https://gistpages.com/posts/ruby_arrays_insert_append_length_index_remove)
- [Install Ruby Environment on Mac](https://gorails.com/setup/osx/10.12-sierra)

#### Ruby on Rails:
- [Tutorial: Ruby On Rails](https://www.railstutorial.org/book/beginning)
- [Tutorial: ROR on Docker](http://codingnudge.com/2017/03/17/tutorial-how-to-run-ruby-on-rails-on-docker-part-1/)

## Sysadmin References:
- [Sysadmin Command References](https://gist.github.com/ruanbekker/3118ed23c25451132becacd3b974db08)
- [Linux Performance Observability Tools](https://medium.com/@chrishantha/linux-performance-observability-tools-19ae2328f87f)
- [Troubleshooting High IO Wait](http://bencane.com/2012/08/06/troubleshooting-high-io-wait-in-linux/)
- [IO Monitoring in Linux](https://blog.pythian.com/basic-io-monitoring-on-linux/)
- [IOStat and VMStat for Performance Monitoring](http://xiayubin.com/blog/2014/01/29/how-i-use-iostat-and-vmstat-for-performance-analysis/)

## Self Hosting

#### Financial
- [SelfHosted Firefly](https://github.com/firefly-iii/firefly-iii)

#### Self Hosting Frameworks:
- [Sandstorm](https://sandstorm.io/)

## VPN:
#### VPN-Howto:
- [Ubuntu OpenVPN Script](https://www.cyberciti.biz/faq/howto-setup-openvpn-server-on-ubuntu-linux-14-04-or-16-04-lts/)
- [Ubuntu IPSec Script](https://github.com/hwdsl2/setup-ipsec-vpn)
- [DO - Setup OpenVPN on Ubuntu](https://www.digitalocean.com/community/tutorials/how-to-set-up-an-openvpn-server-on-ubuntu-16-04)
- [Elasticshosts - IPSec VPN](https://www.elastichosts.com/blog/linux-l2tpipsec-vpn-client/)
- [PPTP/IPSec/OpenVPN Auto Install](https://github.com/bedefaced/vpn-install)

## Web Frameworks

#### Python Flask:
- [Python Flask Upload Example](https://gist.github.com/dAnjou/2874714)
- [Awesome Flask - humiaozuzu](https://github.com/humiaozuzu/awesome-flask#awesome-flask)
- [Flask over HTTPS (MG)](https://blog.miguelgrinberg.com/post/running-your-flask-application-over-https)
- [Flask Advanced Patterns](https://speakerdeck.com/mitsuhiko/advanced-flask-patterns-1)

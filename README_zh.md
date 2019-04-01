# Docker Resources All In One
docker资源汇总。现在更新较慢，非常欢迎诸位提PR更新。

英文版本[链接](https://github.com/hangyan/docker-resources)

# 目录
* [资源汇集](#资源汇集)
  * [书籍](#书籍)
  * [网站](#网站)
  * [开源文档](#开源文档)
  * [内容聚合](#内容聚合)
  * [社区博客](#社区博客)
  * [个人博客](#个人博客)
  * [创业公司](#创业公司)
  * [镜像中心](#镜像中心)
* [相关项目](#相关项目)
  * [操作系统](#操作系统)
  * [虚拟机](#虚拟机)
  * [竞争者](#竞争者)
  * [管理工具](#管理工具)
  * [Paas平台](#paas平台)
  * [Caas平台](#caas平台)
  * [项目集成](#项目集成)
  * [监控](#监控)
  * [网络](#网络)
  * [持续集成](#持续集成)
  * [开发部署](#开发部署)
  * [日志](#日志)
  * [服务发现](#服务发现)
  * [私有仓库](#私有仓库)
  * [可视化工具](#可视化工具)
  * [存储](#存储)
  * [卷管理](#卷管理)
  * [安全](#安全)
  * [应用](#应用)
  * [镜像及Dockerfile](#镜像及dockerfile)
  * [容器](#容器)
  * [扩展](#扩展)
  * [客户端](#客户端)
  * [其他](#其他)
* [博文](#博文)
  * [介绍](#介绍)
  * [Docker技术](#docker技术)
    * [镜像相关](#镜像相关)
    * [存储相关](#存储相关)
    * [卷管理相关](#卷管理相关)
    * [Dockerfile](#dockerfile)
    * [容器相关](#容器相关)
    * [安全相关](#安全相关)
    * [资源管理](#资源管理)
    * [网络相关](#网络相关)
    * [监控相关](#监控相关)
    * [私有仓库相关](#私有仓库相关)
    * [API](#API)
    * [性能](#性能)
    * [进程管理](#进程管理)
  * [思考](#思考)
  * [Rocket](#rocket)
  * [底层技术](#底层技术)
    * [LXC](#lxc)
    * [cgroups](#cgroups)
    * [Systemd](#systemd)
    * [Namespaces](#namespaces)
  * [相关项目](#相关项目)
    * [Compose](#compose)
    * [Swarm](#swarm)
    * [Mesosphere](#mesosphere)
    * [Kubernetes](#kubernetes)
    * [Openstack](#openstack)
    * [Azure](#azure)
    * [Others](#others)
  * [应用](#应用)
    * [Apps](#apps)
    * [GUI](#gui)
    * [服务发现相关](#服务发现相关)
    * [开发部署测试](#开发部署测试)
    * [企业实践](#企业实践)
    * [其他平台](#其他平台)

# 资源汇集
## 书籍
* [第一本Docker书](http://book.douban.com/subject/26285268/) (7.4分)
* [Docker —— 从入门到实践](http://yeasy.gitbooks.io/docker_practice/content/) (内容一般)
* [The Docker Book](http://www.dockerbook.com/)
* [Docker in Action](http://www.manning.com/nickoloff/) (Early Access Edition)
* [Docker in Practice](http://manning.com/miell/?a_aid=zwischenzugs&a_bid=e0d48f62) (Early Access Edition)
* [Docker 技术入门与实战](http://book.douban.com/subject/26284823/) (6.1分)
* [Docker源码分析](http://book.douban.com/subject/26581184/)
* [Docker——容器与容器云](http://book.douban.com/subject/26593175/)
* [Docker in the Trenches:Successful Production Deployment](http://book.douban.com/subject/26477632/)
* [docker cookbook:80 hands-on recipes to efficiently work with the Docker 1.6 environment on Linux](http://book.douban.com/subject/26426431/)
* [Using docker](http://book.douban.com/subject/26423831/)
* [Orchestrating Docker](http://book.douban.com/subject/26333028/)
* [Docker:Up and Running](http://book.douban.com/subject/26413766/)
* [Docker开发实践](http://book.douban.com/subject/26432893/)
* [Build Your Own PaaS with Docker:Create, modify, and run your own PaaS with modularized containers using Docker](http://book.douban.com/subject/26423913/)
* [Docker for Java Developers](https://www.nginx.com/resources/library/docker-for-java-developers/)


## 网站
### 英文
* [官方文档](https://docs.docker.com/) 
* [Docker项目地址](https://github.com/docker/docker)
* [Dockerhub](https://docs.docker.com/docker-hub/)
* [Coreos官方文档](https://coreos.com/docs/)

### 中文
* [Dockerpool](http://dockerpool.com/) 
* [Docker中文](http://www.docker.org.cn/) 
* [Dockerone](http://dockerone.com/)
* [infoq Docker专栏](http://www.infoq.com/cn/dockers/)
* [CSDN Docker 社区](http://docker.csdn.net/)

## 开源文档
* [Docker中文指南](https://github.com/widuu/chinese_docker)  (中文，质量一般，较老)
* [Docker Cheat Sheet](https://github.com/wsargent/docker-cheat-sheet#volumes)
* [Docker Guidebook](https://github.com/kencochrane/docker-guidebook)
* [The Docker Ecosystem](https://www.digitalocean.com/community/tutorial_series/the-docker-ecosystem)

## 内容聚合
* [awesome-docker](https://github.com/veggiemonk/awesome-docker) (英文docker资源汇总)
* [Docker Weekly Archives](http://blog.docker.com/docker-weekly-archives/)
* [Valuable Docker Links](http://www.nkode.io/2014/08/24/valuable-docker-links.html)
* [Docker Ecosystem](https://www.mindmeister.com/389671722/docker-ecosystem)
* [Digital Ocean Community](https://www.digitalocean.com/community/search?primary_filter=tutorials&query=docker)
* [开源中国社区Docker技术翻译文章](http://www.oschina.net/translate/tag/docker)
* [Dockerone周报](http://weekly.dockerone.com/index)
* [InfoQ](http://www.infoq.com/cn/dockers/)

## 社区博客
* [Docker官方博客](http://blog.docker.com/)
* [Coreos官方博客](https://coreos.com/blog/)
* [Century Links Labs](http://www.centurylinklabs.com/category/docker/)
* [SequenceIQ Blog](http://blog.sequenceiq.com/)
* [Tutum Blog](http://blog.tutum.co/)
* [Weave Blog](http://weaveblog.com/)
* [Odd Bits](http://blog.oddbit.com/)
* [Project Atomic](http://www.projectatomic.io/blog/)
* [Container Solutions](http://container-solutions.com/blog/)
* [灵雀云博客](http://www.alauda.cn/blog/)

## 个人博客
* [jpetazzo](http://jpetazzo.github.io/)
* [Jeff Lindsay](http://progrium.com/blog/)
* [Jason Wilder](http://jasonwilder.com/)
* [Michael Crosby](http://crosbymichael.com/)
* [Matt Bajor](http://technolo-g.com/)
* [Scott's Weblog](http://blog.scottlowe.org/2015/02/06/quick-intro-to-consul/)
* [Luis Elizondo](http://www.luiselizondo.net)
* [zwischenzugs](https://zwischenzugs.wordpress.com)
* [Musings of Matt Williams](http://matthewkwilliams.com/)

## 创业公司
* [云雀科技](https://www.alauda.cn)
* [DaoCloud](https://www.daocloud.io/)
* [云栈科技](https://csphere.cn)
* [tutum](https://www.tutum.co/)
* [时速云](https://www.tenxcloud.com/)
* [数人科技](http://www.dataman-inc.com/)
* [网易蜂巢](https://c.163.com/)
* [好雨云](https://www.goodrain.com/)

## 镜像中心
* [Dockerhub](http://hub.docker.com/)
* [灵雀云镜像中心](https://hub.alauda.cn/)
* [时速云镜像中心](https://www.tenxcloud.com/marketplace)

# 相关项目
## 操作系统
* [Coreos](https://coreos.com/) (比较成熟)
* [Atomic](http://www.redhat.com/en/technologies/linux-platforms/enterprise-linux) (新出，内置kubernetes)
* [Rancheio](http://rancher.com/) (较新)
* [Snappy](http://developer.ubuntu.com/en/snappy/) (A new, transactionally updated Ubuntu for clouds and devices)
* [Photon](https://github.com/vmware/photon)
* [ClearLinux](https://clearlinux.org) (The Clear Linux™ Project for Intel® Architecture is a project that is building a Linux OS distribution for various cloud use cases)
* [Mirage OS](https://mirage.io/)

## 虚拟机
* [boot2docker](https://github.com/boot2docker/boot2docker) (Lightweight Linux for Docker)
* [dvm](https://github.com/fnichol/dvm) (An on demand Docker virtual machine)


## 竞争者
* [rocket](https://github.com/coreos/rocket) (coreos推出)
* [dockerlite](https://github.com/docker/dockerlite) (Lightweight virtualization system based on LXC and BTRFS)
* [lmctfy](https://github.com/google/lmctfy) (lmctfy is the open source version of Google’s container stack, which provides Linux application containers.)
* [OpenVZ](https://openvz.org/Main_Page)
* [Hyper](https://www.hyper.sh/) (Hyper = Hypervisor + Kernel + Docker Image)
* [bocker](https://github.com/p8952/bocker) (100行bash实现的docker)
* [lxd](https://github.com/lxc/lxd)(Daemon based on liblxc offering a REST API to manage containers)

## 管理工具
* [kubernetes](https://github.com/GoogleCloudPlatform/kubernetes) (最有可能成为事实标准的一个，已经获得诸多平台支持)
* [shipyard](https://github.com/shipyard/shipyard)  (带GUI)
* [swarm](https://github.com/docker/swarm) (官方出品，尚在初期)
* [citadel](https://github.com/citadel/citadel) (用于创建管理工具的tookit,shipyard即是基于此开发)
* [docker-cluster](https://github.com/tsuru/docker-cluster) (使用`Docker remote api`)
* [compose](https://github.com/docker/compose) (Define and run complex applications using Docker.原来的Fig)
* [shutit](https://github.com/ianmiell/shutit) (Complex and Dynamic Docker Builds Made Simple)
* [maestro](https://github.com/toscanini/maestro) (Container orchestration for Docker environments)
* [decking](https://github.com/meetfinch/decking) (A Docker helper to create, manage and run clusters of containers)
* [flocker](https://github.com/ClusterHQ/flocker) (Easily manage Docker containers & their data)
* [serf](https://github.com/hashicorp/serf) (Service orchestration and management tool)
* [marathon](https://github.com/mesosphere/marathon) (Deploy and manage containers (including Docker) on top of Apache Mesos at scale)
* [gaudi](https://github.com/marmelab/gaudi) (Gaudi allows to share multi-component applications, based on Docker, Go, and YAML)
* [panamax](http://panamax.io/) (Docker management for humans)
* [clocker](https://github.com/brooklyncentral/clocker) (Brooklyn managed Docker containers)
* [fleet] (https://github.com/coreos/fleet) (将systemd的能力扩展到多个机器)
* [Meteor](https://github.com/meteorhacks/cluster)(Clustering solution for Meteor with load balancing and service discovery)
* [helios](https://github.com/spotify/helios) (Docker container orchestration platform)
* [maestro-ng](https://github.com/signalfuse/maestro-ng) (Orchestration of Docker-based, multi-host environments)
* [shipper](https://github.com/mailgun/shipper) (Fabric for docker containers)
* [origin](https://github.com/openshift/origin) (OpenShift 3 - build, deploy, and manage your applications with Docker and Kubernetes)
* [autodock](https://github.com/cholcombe973/autodock) (The docker container automation tool.)
* [virtkick](https://github.com/virtkick/virtkick) (Manage virtual machines or Docker containers easily)
* [blockade](https://github.com/dcm-oss/blockade) (Docker-based utility for testing network failures and partitions in distributed applications,[docs](http://blockade.readthedocs.org/))
* [rancher](https://github.com/rancherio/rancher) (A Platform for Operating Docker in Production.[rancher.com](http://rancher.com/))
* [cSphere](https://csphere.cn/) (容器虚拟化管理平台,提供可视化界面，容器、镜像、机器、仓库等管理。商业软件，有试用版)
* [rocker-compose](https://github.com/grammarly/rocker-compose) (Docker composition tool with idempotency features for deploying apps composed of multiple containers.)
* [chronos](https://github.com/mesos/chronos)(Fault tolerant job scheduler for Mesos which handles dependencies and ISO8601 based schedules)

## Paas平台
* [flynn](https://github.com/flynn/flynn) (A next generation open source platform as a service)
* [deis](http://deis.io/) (Your PaaS. Your Rules)
* [peas](https://github.com/tombh/peas) (Docker and Ruby based PaaS)
* [dawn](https://github.com/dawn/dawn) (Docker-based PaaS in Ruby)
* [octohost](https://github.com/octohost/octohost)(Simple web focused Dockerfile based PaaS server)
* [dokku](https://github.com/progrium/dokku) (Docker powered mini-Heroku in around 100 lines of Bash)
* [cloudfoundry](https://github.com/cloudfoundry)
* [paz](https://github.com/yldio/paz) (A pluggable in-house service platform with a PaaS-like workflow, built on Docker, CoreOS, Etcd and Fleet)
* [armada](https://github.com/armadaplatform/armada) (Complete solution for development, deployment, configuration and discovery of microservices)
* [rainbond](https://github.com/goodrain/rainbond) (Serverless PaaS , A new generation of easy-to-use cloud management platforms based on kubernetes.)

## Caas平台
* [Docker Datacenter](https://www.docker.com/products/docker-datacenter)
* [Aluda](http://www.alauda.cn/)(灵雀云容器服务) (英文版[Alauda.io](http://www.alauda.io/))

## 项目集成
* [openstack-docker](https://github.com/docker/openstack-docker) (Nova driver and Glance backend to use Docker inside OpenStack)
* [Jenkins Cloud Plugin for Docker](https://github.com/jenkinsci/docker-plugin/)
* [deimos](https://github.com/mesosphere/deimos) (Mesos containerizer hooks for Docker)
* [garether-docker](https://github.com/garethr/garethr-docker) (Puppet module for managing docker)
* [systemd-docker](https://github.com/ibuildthecloud/systemd-docker) (Wrapper for "docker run" to handle systemd quirks)
* [docker-ansible](https://github.com/cove/docker-ansible) (Ansible module for Docker)

## 监控
* [seagull](https://github.com/tobegit3hub/seagull) (Friendly Web UI to monitor docker daemon)
* [dockerana](https://github.com/dockerana/dockerana) (Docker Monitoring with support for Grafana and Graphite)
* [docker-mon](https://github.com/icecrime/docker-mon)(Console-based Docker monitoring)
* [cadvisor](https://github.com/google/cadvisor) (Analyzes resource usage and performance characteristics of running containers)
* [Prometheus](https://github.com/prometheus/prometheus) (The Prometheus  monitoring system and time series database,see the [docker exporter](https://github.com/docker-infra/container_exporter))
* [ctop](https://github.com/bcicen/ctop)(Top-like interface for container metrics https://bcicen.github.io/ctop/)
* [NexClipper](https://github.com/TheNexCloud/NexClipper) - Simple web UI for container monitoring by [@Nexcloud](https://github.com/TheNexCloud)

## 网络
* [weave](https://github.com/zettio/weave) (The Docker Network)
* [wormhole](https://github.com/vishvananda/wormhole) (A smart proxy to connect docker containers.)
* [flannel](https://github.com/coreos/flannel) (flannel is an etcd backed network fabric for containers)
* [calico-docker](https://github.com/Metaswitch/calico-docker)(Docker version of Project Calico,Calico can provide networking in a Docker environment)
* [libnetwork](https://github.com/docker/libnetwork) (networking for containers)

## 持续集成
* [drone](https://github.com/drone/drone) (A Continuous Integration platform built on Docker)


## 开发部署
* [tug](https://github.com/nitrous-io/tug) (Docker development workflow)
* [vagga](https://github.com/tailhook/vagga)(Vagga is a tool to create development environments)
* [longshoreman](https://github.com/longshoreman/longshoreman) (Automated deployment with Docker)
* [centurion](https://github.com/newrelic/centurion) (A mass deployment tool for Docker fleets)
* [shutit](https://github.com/ianmiell/shutit) (Complex and Dynamic Docker Builds Made Simple)
* [dockership](https://github.com/mcuadros/dockership) (dead simple docker deploy tool)
* [devstep](https://github.com/fgrehm/devstep) (Development environments powered by Docker and buildpacks)
* [docker-devenv](https://github.com/wsargent/docker-devenv) (Docker based development environment)
* [dexec](https://github.com/docker-exec/dexec) (Command line interface for running code with Docker Exec images)

## 日志
* [logspout](https://github.com/gliderlabs/logspout) (Log routing for Docker container logs)
* [logjam](https://github.com/gocardless/logjam) (a log shipping tool)


## 服务发现
* [skydock](https://github.com/crosbymichael/skydock) (基于DNS)
* [Consul](https://www.consul.io/) (Consul is a tool for service discovery, monitoring and configuration)
* [registrator](https://github.com/gliderlabs/registrator)(Service registry bridge for Docker with pluggable adapters)
* [etcd](https://github.com/coreos/etcd) (A highly-available key value store for shared configuration and service discovery)
* [docker-grand-ambassador](https://github.com/cpuguy83/docker-grand-ambassador) ( fully dynamic docker link ambassador)
* [confd](https://github.com/kelseyhightower/confd) (Manage local application configuration files using templates and data from etcd or consul)
* [ambassadord](https://github.com/progrium/ambassadord) (Magic Docker ambassador)
* [logcabin](https://github.com/logcabin/logcabin) (LogCabin is a distributed storage system built on Raft that provides a small amount of highly replicated, consistent storage)

## 私有仓库
* [docket](https://github.com/netvarun/docket) (Custom docker registry that allows for lightning fast deploys through bittorrent)
* [docker-registry](https://github.com/docker/docker-registry) (Registry server for Docker (hosting/delivering of repositories and images))
* [wharf](https://github.com/dockercn/wharf)(ContainerOps Open Source Platform)
* [distribution](https://github.com/docker/distribution) (The Docker toolset to pack, ship, store, and deliver content)
* [dogestry] (https://github.com/blake-education/dogestry) (simple docker image storage on s3)
* [docker-private-registry](https://github.com/shipyard/docker-private-registry) (Private Docker Registry)
* [speedy](https://github.com/jcloudpub/speedy) (a distributed docker image storage)
* [harbor](https://github.com/vmware/harbor) (An enterprise-class container registry server based on Docker Distribution)

## 可视化工具
* [dockerboard](https://github.com/dockerboard/dockerboard)  (Simple dashboards, visualizations, managements for your dockers)
* [Kitematic](https://kitematic.com/) (现在包含在Docker Toolbox中，支持Mac OS X 10.8+ 和 Windows 7+ (64-bit) )
* [dockerui](https://github.com/crosbymichael/dockerui) (A web interface for docker)
* [docker-registry-web](https://github.com/atc-/docker-registry-web) (A web UI for easy private/local Docker Registry integration)
* [Portus](https://github.com/SUSE/Portus) (Authorization service and frontend for Docker registry v2)
* [panamax-ui](https://github.com/CenturyLinkLabs/panamax-ui) (The Web GUI for Panamax)
* [seagull](https://github.com/tobegit3hub/seagull) (Friendly Web UI to monitor docker daemon)
* [docker-swarm-visualizer](https://github.com/ManoMarks/docker-swarm-visualizer)(A visualizer for Docker Swarm using the Docker Remote API, Node.JS, and D3)
* [portainer](http://portainer.io/) (简单的UI管理工具)
* [Swirl](https://github.com/cuigh/swirl) (专注于 Swarm 集群的 Docker 管理工具)

## 存储
* [pfs](http://pachyderm-io.github.io/pfs/#whats-new-in-v02) (A git-like distributed file system for a dockerized world)

## 卷管理
* [docker-volumes](https://github.com/cpuguy83/docker-volumes) (Docker Volume Manager)

## 安全
* [TUF](http://theupdateframework.com/) (Like the S in HTTPS, a plug-and-play library for securing a software updater)
* [container-compliance](https://github.com/OpenSCAP/container-compliance)(Assessing compliance of a container)

## 应用
* [ferry](https://github.com/cirruspath/ferry) (使用docker来构建部署大数据应用(hadoop,spark...),[ferry.opencore.io](http://ferry.opencore.io/))
* [codecube](https://github.com/hmarr/codecube) (Docker-powered runnable code snippets)
* [DUnit](https://github.com/Vectorface/dunit) (Test code against multiple versions of PHP with the help of docker)
* [PHP Stack](https://github.com/kasperisager/phpstack) (Docker- and Shipyard-managed PHP development stack: Nginx, MySQL, MongoDB, PHP-FPM, HHVM, Memcached, Redis, and Elasticsearch. Includes an optional Vagrant-managed CoreOS proxy box at your leisure.)
* [Django Demo](https://github.com/kencochrane/django-docker) (Demo Django App using Docker)
* [dnt](https://github.com/rvagg/dnt) (Docker Node Tester)
* [dockermail](https://github.com/adaline/dockermail) (A secure, minimal-configuration mail server in a docker container.)
* [docker-rpm-builder](https://github.com/alanfranz/docker-rpm-builder) (Build native RPM packages by leveraging docker capabilities)
* [tmpnb](https://github.com/jupyter/tmpnb) (Creates temporary Jupyter Notebook servers using Docker containers)
* [open-ocr](https://github.com/tleyden/open-ocr) (Run your own OCR-as-a-Service using Tesseract and Docker)
* [dray](https://github.com/CenturyLinkLabs/dray) (An engine for managing the execution of container-based workflows)
* [kolla](https://github.com/stackforge/kolla) (Deploying OpenStack using Kubernetes and Docker)
* [docker-desktop](https://github.com/rogaha/docker-desktop) (Docker Desktop enables you to create virtual desktops that can be accessed remotely. It comes with Firefox and Libreoffice already installed)
* [dockercraft](https://github.com/docker/dockercraft) (在我的世界中管理docker容器~)

## 镜像及Dockerfile
* [dockly](https://github.com/swipely/dockly) (DSL and Gem for building ready-to-launch Docker images)
* [baseimage-docker](https://github.com/phusion/baseimage-docker) (A minimal Ubuntu base image modified for Docker-friendlines)
* [busybox](https://github.com/jpetazzo/docker-busybox) (Busybox for Stackbrew)
* [busybox](https://github.com/progrium/busybox) (Busybox container with glibc+opkg)
* [dockerfile-examples](https://github.com/komljen/dockerfile-examples)
* [passenger-docker](https://github.com/phusion/passenger-docker) (Docker base images for Ruby, Python, Node.js and Meteor web apps)
* [Dockerfile Project](http://dockerfile.github.io/)
* [Dockerfiles](https://github.com/crosbymichael/Dockerfiles)(Collection of Dockerfiles)
* [docker-desktop](https://github.com/rogaha/docker-desktop) (create virtual desktops that can be accessed remotely)
* [StealthBox](https://github.com/Toilal/stealthbox)(Share your favorite content remotely without spoiling your home network)
* [Machine Learning](https://github.com/StartupML/jetpack) (Get up and running with machine learning using Docker)
* [Gitlab](https://github.com/sameersbn/docker-gitlab) (Dockerized gitlab web server)
* [Discourse](https://github.com/discourse/discourse_docker) (A Docker image for Discourse)
* [OpenVPN](https://github.com/jpetazzo/dockvpn) (Recipe to build an OpenVPN image for Docker)
* [Wordpress+Nginx](https://github.com/eugeneware/docker-wordpress-nginx) (A
  Dockerfile that installs the latest wordpress, nginx and php-fpm.Another
  wordpress [image](https://github.com/jbfink/docker-wordpress)) 另一个[wordpress](https://github.com/dz0ny/docker-wpdev)
* [Nginx-Proxy](https://github.com/jwilder/nginx-proxy) (Automated nginx proxy for Docker containers using docker-gen)
* [docker-squash](https://github.com/jwilder/docker-squash) (Squash docker images to make them smaller)
* [Mysql](https://github.com/tutumcloud/tutum-docker-mysql) (Docker image to run an out-of-the-box MySQL server)
* [CentOS-Dockerfiles](https://github.com/CentOS/CentOS-Dockerfiles) (Dockerfiles for various common implementations)
* [Redmine](https://github.com/sameersbn/docker-redmine) (Dockerized redmine app server)
* [Spark](https://github.com/amplab/docker-scripts) (Dockerfiles and scripts for Spark and Shark Docker images)
* [docker-grafana-graphite](https://github.com/kamon-io/docker-grafana-graphite) (Docker image with StatsD, Graphite, Grafana and a Kamon Dashboard)
* [Elasticsearch](https://github.com/dockerfile/elasticsearch) (ElasticSearch Dockerfile for trusted automated Docker builds)
* [docker-alpine](https://github.com/gliderlabs/docker-alpine) (Docker image based on Alpine Linux will help you win at minimalism
* [Hadoop](https://github.com/sequenceiq/hadoop-docker) (Hadoop docker image)
* [R](https://github.com/rocker-org/rocker) (R configurations for Docker)
* [ASP.NET](https://github.com/aspnet/aspnet-docker) (Docker image for ASP.NET 5.)
* [nmpjs](https://github.com/terinjokes/docker-npmjs) (Docker image for a private npmjs repository)
* [Jenkins](https://github.com/aespinosa/docker-jenkins) (Builds a Docker image for Jenkins)
* [Postgres](https://github.com/docker-library/postgres) (Docker Official Image packaging for Postgres)
* [Logstash](https://github.com/pblittle/docker-logstash) (Docker image for Logstash 1.4 )

## 容器
* [dockize](https://github.com/jwilder/dockerize) (Utility to simplify running applications in docker containers)
* [Supervisor](http://supervisord.org/) (A Process Control System)
* [CFEngine](http://cfengine.com/) (Process management)
* [docker-gen](https://github.com/jwilder/docker-gen) (Generate files from docker container meta-data)
* [tini](https://github.com/krallin/tini) (A tiny but valid `init` for containers)
* [S6](http://skarnet.org/software/s6/) (s6 is a small suite of programs for UNIX, designed to allow process supervision)

## 扩展
* [powerstrip](https://github.com/clusterhq/powerstrip) (A tool for prototyping Docker extensions)

## 客户端
* [docker-py](https://github.com/docker/docker-py) (**Python**)
* [docker-api](https://github.com/swipely/docker-api) (**Ruby**)
* [dockernode](https://github.com/apocas/dockerode) (**Node.js**)
* [go-dockerclient](https://github.com/fsouza/go-dockerclient) (**Golang**)
* [docker-php](https://github.com/stage1/docker-php) (**PHP**)
* [dockerclient](https://github.com/samalba/dockerclient) (**Golang**)
* [docker-java](https://github.com/kpelykh/docker-java) (**Java**)

## 其他
* [dockersh](https://github.com/Yelp/dockersh) (A shell which places users into individual docker containers)
* [buildstep](https://github.com/progrium/buildstep) (Buildstep uses Docker and Buildpacks to build applications like Heroku)
* [dind](https://github.com/jpetazzo/dind)(Docker in Docker)
* [building](https://github.com/CenturyLinkLabs/building) (Build a Docker container for any app using Heroku Buildpacks)
* [torrent-docker](https://github.com/mafintosh/torrent-docker) (realtime boot of remote docker images using bittorrent)
* [docker-backup](https://github.com/docker-infra/docker-backup) (Tool for backing up docker volume / data containers)
* [Docker Support in IntelliJ IDEA 14.1](http://blog.jetbrains.com/idea/2015/03/docker-support-in-intellij-idea-14-1/)
* [dockerception](https://github.com/jamiemccrindle/dockerception) (Docker building dockers - keeping them small)
* [habitus](https://github.com/cloud66/habitus)(A Build Flow Tool for Docker)
* [ofelia](https://github.com/mcuadros/ofelia) (A docker job scheduler (aka. crontab for docker))

# 博文
## 介绍
* [The Frontend Developer's Guide to Docker](http://www.bryanbraun.com/2014/07/15/the-frontend-developers-guide-to-docker)
* [Docker and Go: why did we decide to write Docker in Go?](http://pan.baidu.com/s/1qWlybDE)(pdf)
* [How to Use Docker on OS X: The Missing Guide](http://viget.com/extend/how-to-use-docker-on-os-x-the-missing-guide)
* [24 random docker tips](http://csaba.palfi.me/random-docker-tips/)
* [The 5 Most Important Things I’ve Learned From Using Docker](http://blog.tutum.co/2014/10/28/the-5-most-important-things-ive-learned-from-using-docker/)
* [A Simple Way to Dockerize Applications](http://jasonwilder.com/blog/2014/10/13/a-simple-way-to-dockerize-applications/)
* [Docker orchestration](http://chrisbarra.me/posts/docker-orchestration.html)
* [Docker's rise from sleeper to open source king](http://www.cnbc.com/id/102422954)
* [Faster Builds with Container-Based Infrastructure and Docker](http://blog.travis-ci.com/2014-12-17-faster-builds-with-container-based-infrastructure/)
* [How to Use Docker on Windows](http://blog.tutum.co/2014/11/05/how-to-use-docker-on-windows/)
* [Run ARM binaries in your Docker Container using Boot2Docker…](http://neophob.com/2014/10/run-arm-binaries-in-your-docker-container-using-boot2docker/)
* [Docker on OS X with VMWare Fusion](http://ewen.mcneill.gen.nz/blog/entry/2014-09-20-docker-on-osx-with-vmware-fusion/)
* [Docker 笔记](http://opskumu.github.io/docker.html) 
* [关于Docker你应该知道的10件事](http://www.lupaworld.com/portal.php?mod=view&aid=250966)
* [Docker的大坑小洼](http://blog.daocloud.io/docker_troubleshootings/) / [再谈《Docker的大坑小洼》](http://dockerone.com/question/92)

## Docker技术
### 镜像相关
* [Docker Image Insecurity](https://titanous.com/posts/docker-insecurity)
* [Building good docker images](http://jonathan.bergknoff.com/journal/building-good-docker-images)
* [Your docker image might might be broken without you knowing it](http://phusion.github.io/baseimage-docker/)
* [Flat Docker images](http://3ofcoins.net/2013/09/22/flat-docker-images/)
* [Baseimage-docker, fat containers and "treating containers as VMs"](https://blog.phusion.nl/2015/01/20/baseimage-docker-fat-containers-treating-containers-vms/)
* [Create The Smallest Possible Docker Container](http://blog.xebia.com/2014/07/04/create-the-smallest-possible-docker-container/)
* [Creating a Docker image from your code](http://blog.tutum.co/2014/04/10/creating-a-docker-image-from-your-code/)
* [Optimizing Docker Images](http://www.centurylinklabs.com/optimizing-docker-images/?hvid=1OW0br)
* [Building Docker Images for Static Go Binaries](https://medium.com/@kelseyhightower/optimizing-docker-images-for-static-binaries-b5696e26eb07)
* [Squashing Docker Images](http://jasonwilder.com/blog/2014/08/19/squashing-docker-images/)
* [Building a Multi-Purpose Docker Image](https://medium.com/docker-news/building-a-multi-purpose-docker-image-7762378ebc2e)
* [Docker layers cost](https://medium.com/@vaceletm/docker-layers-cost-b28cb13cb627)
* [Deterministic and minimal docker images](http://gregoryszorc.com/blog/2014/10/13/deterministic-and-minimal-docker-images/)

### 存储相关
* [Comprehensive Overview of Storage Scalability in Docker](http://developerblog.redhat.com/2014/09/30/overview-storage-scalability-docker/?utm_content=buffer8a955&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)
* [Resizing Docker containers with the Device Mapper plugin](http://jpetazzo.github.io/2014/01/29/docker-device-mapper-resize/)
* [Where are Docker images stored?](http://blog.thoward37.me/articles/where-are-docker-images-stored/)
* [Persistent Distributed Filesystems in Docker without NFS or Gluster](http://www.centurylinklabs.com/persistent-distributed-filesystems-in-docker-without-nfs-or-gluster/)
* [深入Docker存储驱动](http://static.dockerone.com/ppt/filedriver.html#1) (slide)
* [Deep dive into Docker storage drivers](http://jpetazzo.github.io/assets/2015-03-03-not-so-deep-dive-into-docker-storage-drivers.html#1)

### 卷管理相关
* [Understanding Volumes in Docker](http://container-solutions.com/2014/12/understanding-volumes-docker/)
* [Powerstrip-flocker: Portable volumes using just the Docker CLI](https://clusterhq.com/blog/powerstrip-flocker-portable-volumes-using-just-docker-cli/)

### Dockerfile
* [6 Dockerfile Tips from the Official Images](http://container-solutions.com/2014/11/6-dockerfile-tips-official-images/)
* [Writing Dockerfile](http://www.techbar.me/writing-dockerfile/)
* [How to Optimize Your Dockerfile](http://blog.tutum.co/2014/10/22/how-to-optimize-your-dockerfile/)
* [Dockerfile Golf (or optimizing the Docker build process)](http://www.davidmkerr.com/2014/08/dockerfile-golf-or-optimizing-docker.html)
* [Dockerfile Best Practices](http://crosbymichael.com/dockerfile-best-practices.html)



### 容器相关
* [What is the difference between CMD and ENTRYPOINT in a Dockerfile?](http://stackoverflow.com/questions/21553353/what-is-the-difference-between-cmd-and-entrypoint-in-a-dockerfile)
* [Docker and the PID 1 zombie reaping problem](https://blog.phusion.nl/2015/01/20/docker-and-the-pid-1-zombie-reaping-problem/)
* [Data-only container madness](http://container42.com/2014/11/18/data-only-container-madness/)
* [On-demand activation of Docker containers with systemd](https://developer.atlassian.com/blog/2015/03/docker-systemd-socket-activation/)
* [Docker and S6 – My New Favorite Process Supervisor](http://blog.tutum.co/2014/12/02/docker-and-s6-my-new-favorite-process-supervisor/)
* [On Docker Container Composition](https://medium.com/on-docker/on-docker-container-composition-a98788f1aa3c)
* [Introducing a *Super* Privileged Container Concept](http://developerblog.redhat.com/2014/11/06/introducing-a-super-privileged-container-concept/)
* [Docker Inspect Template Magic](http://container-solutions.com/2015/03/docker-inspect-template-magic/)
* [‘Piping’ Hot Docker Containers](http://matthewkwilliams.com/index.php/2015/04/21/piping-hot-docker-containers/)
* [Checkpoint and restore Docker container with CRIU](http://blog.circleci.com/checkpoint-and-restore-docker-container-with-criu/)

### 安全
* [WHY YOU DON'T NEED TO RUN SSHD IN YOUR DOCKER CONTAINERS](http://blog.docker.com/2014/06/why-you-dont-need-to-run-sshd-in-docker/)
* [shocker: docker PoC VMM-container breakout](http://stealth.openwall.net/xSports/shocker.c)
* [Containers&Docker: How secure are they?](https://blog.docker.com/2013/08/containers-docker-how-secure-are-they/)
* [Docker and SELinux](http://www.projectatomic.io/docs/docker-and-selinux/)
* [Bringing new security features to Docker](https://opensource.com/business/14/9/security-for-docker)
* [Docker Secure Deployment Guidelines](https://github.com/GDSSecurity/Docker-Secure-Deployment-Guidelines)
* [Docker Container Breakout Proof-Of-Concept Exploit](http://outofmemory.cn/wr/?u=http%3A%2F%2Fblog.docker.com%2F2014%2F06%2Fdocker-container-breakout-proof-of-concept-exploit%2F)
* [The dangers of UFW + Docker](http://blog.viktorpetersson.com/post/101707677489/the-dangers-of-ufw-docker)
* [Tuning Docker with the newest security enhancements](https://opensource.com/business/15/3/docker-security-tuning)

### 资源管理
* [Resource management in Docker](https://goldmann.pl/blog/2014/09/11/resource-management-in-docker/) (与systemd有关)

### 网络相关
* [Advanced networking](https://docs.docker.com/articles/networking/)
* [DNS And docker containers](http://wiredcraft.com/blog/dns-and-docker-containers/)
* [Coupling Docker and Open vSwitch](http://fbevmware.blogspot.com/2013/12/coupling-docker-and-open-vswitch.html)
* [Connecting Docker containers on multiple hosts](https://goldmann.pl/blog/2014/01/21/connecting-docker-containers-on-multiple-hosts/)
* [Docker部署基于Ryu的SDN环境](http://www.csdn.net/article/2014-12-05/2822974)
* [Muti-host Docker Network](http://wiredcraft.com/blog/multi-host-docker-network/)
* [Life and Docker networking](http://weaveblog.com/2014/11/13/life-and-docker-networking/)
* [Docker intercontainer networking explained](http://blog.sequenceiq.com/blog/2014/08/12/docker-networking/)
* [Four ways to connect a docker container to a local network](http://blog.oddbit.com/2014/08/11/four-ways-to-connect-a-docker/)
* [Docker intercontainer networking explained](http://blog.sequenceiq.com/blog/2014/08/12/docker-networking/)
* [从SDN以及Docker看网络模型发生的变革](http://dockerone.com/article/188) ([English](http://thenewstack.io/sdn-docker-real-changes-ahead/))

### 监控相关
* [GATHERING LXC AND DOCKER CONTAINERS METRICS](http://blog.docker.com/2013/10/gathering-lxc-docker-containers-metrics/)
* [nsinit: per-container resource monitoring of Docker containers on RHEL/Fedora](http://www.breakage.org/2014/09/03/nsinit-per-container-resource-monitoring-of-docker-containers-on-rhelfedora/)
* [Runtime Metrics](https://docs.docker.com/articles/runmetrics/)
* [Monitor Docker Containers with Prometheus](http://5pi.de/2015/01/26/monitor-docker-containers-with-prometheus/)


### 私有仓库相关
* [Docker Registry Rest API](http://tuhrig.de/docker-registry-rest-api/)


### API
* [DOCKER FROM A DISTANCE - THE REMOTE API](http://blog.trifork.com/2013/12/24/docker-from-a-distance-the-remote-api/) 
* [KVM and Docker LXC Benchmarking with OpenStack](http://bodenr.blogspot.com/2014/05/kvm-and-docker-lxc-benchmarking-with.html)

### 性能
* [PostgreSQL Performance on Docker](http://www.davidmkerr.com/2014/06/postgresql-performance-on-docker.html)
* [Performance Analysis of Docker on Red Hat Enterprise Linux 7](http://developerblog.redhat.com/2014/08/19/performance-analysis-docker-red-hat-enterprise-linux-7/)
* [Preview of Docker Benchmarking at Flux7](http://blog.flux7.com/blogs/docker/preview-of-docker-benchmarking-at-flux7)
* [Getting Started with Performance Analysis of Docker](http://www.breakage.org/2014/06/06/getting-started-with-performance-analysis-of-docker/)
* [Docker network performances](http://blog.loof.fr/2014/10/docker-network-performances.html)
* [Docker Containers: Smaller is not always better](http://matthewkwilliams.com/index.php/2015/04/19/docker-containers-smaller-is-not-always-better/)

### 进程管理
* [Running systemd within a Docker Container](http://developerblog.redhat.com/2014/05/05/running-systemd-within-docker-container/)

## 思考
* [唱衰Docker](http://www.infoq.com/cn/articles/bad-mouthing-docker) ([English](http://iops.io/blog/docker-hype/))
* [docker is the heroku killer](http://www.brightball.com/devops/docker-is-the-heroku-killer)
* [boycott docker](http://www.boycottdocker.org/)
* [Docker isn't so bad](http://grahamc.com/blog/docker-isnt-so-bad/)
* [Is docker ready for production?](https://t37.net/is-docker-ready-for-production-feedbacks-of-a-2-weeks-hands-on.html?)
* [After Docker:Unikernels and Immutable Infrastructure](https://medium.com/@darrenrush/after-docker-unikernels-and-immutable-infrastructure-93d5a91c849e)
* [Docker’s Killer Feature](https://www.joyent.com/blog/dockers-killer-feature)
* [Linux Containers: Parallels, LXC, OpenVZ, Docker and More](http://aucouranton.com/2014/06/13/linux-containers-parallels-lxc-openvz-docker-and-more/)
* [dockerizability is better than dockerized](https://medium.com/@behruz/dockerizability-is-better-than-dockerized-3c08b9dbd84c)
* [Java开发人员需要注意的五大Docker误区](http://dockerone.com/article/236) ([English](http://blog.takipi.com/ignore-the-hype-5-docker-misconceptions-java-developers-should-consider/))
* [Challenges With Randomness In Multi-tenant Linux Container Platforms](http://blog.pivotal.io/cloud-foundry-pivotal/features/challenges-with-randomness-in-multi-tenant-linux-container-platforms)
* [Docker in Production: A History of Failure](https://thehftguy.wordpress.com/2016/11/01/docker-in-production-an-history-of-failure/)


## Rocket
* [App Container and Docker](https://coreos.com/blog/app-container-and-docker/)
* [App Container Specification](https://github.com/appc/spec/blob/master/SPEC.md)
* [Why Docker and Coreos'split was predictable](http://danielcompton.net/2014/12/02/modular-integrated-docker-coreos)
* [Of Containers, Dockers, Rockets, and Daemons](http://3ofcoins.net/2014/12/06/of-containers-dockers-rockets-and-daemons/)
* [Rocket vs Docker and The Myth of the “Simple, Lightweight Enterprise Platform](http://blog.xebialabs.com/2014/12/05/rocket-vs-docker-myth-simple-lightweight-enterprise-platform/)
* [Why CoreOS just fired a Rocket at Docker](https://gigaom.com/2014/12/02/why-coreos-just-fired-a-rocket-at-docker/)
* [What is Rocket and How It’s Different Than Docker](http://www.centurylinklabs.com/interviews/what-is-rocket-and-how-its-different-than-docker/)

## 底层技术
### LXC
* [Exploring LXC Networking](http://containerops.org/2013/11/19/lxc-networking/)
* [Linux Containers](https://wiki.archlinux.org/index.php/Linux_Containers) (archwiki上的内容)

### cgroups
* [cgroups](https://www.kernel.org/doc/Documentation/cgroups/cgroups.txt) (内核官方文档)
* [Managing system resources on Red Hat Enterprise Linux 6](https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/6/html-single/Resource_Management_Guide/index.html) (推荐）
* [Cgroups](https://wiki.archlinux.org/index.php/cgroups) (archwiki上的内容)

### Systemd
* [The systemd for Administrators Blog Series](http://0pointer.de/blog/projects/systemd-for-admins-1.html) (great series,check the index in [here](http://www.freedesktop.org/wiki/Software/systemd/))
* [Getting Started with systemd](https://coreos.com/using-coreos/systemd/) (from
  coreos)
* [Systemd](https://wiki.archlinux.org/index.php/Systemd) (from archwiki)
* [Running Docker Containers with Systemd](http://container-solutions.com/2015/04/running-docker-containers-with-systemd/)
* [Docker without Docker](https://chimeracoder.github.io/docker-without-docker) (slide)

### Namespaces
* [Namespaces in operation](http://lwn.net/Articles/531114/)
* [Introduction to Linux namespaces – Part 1: UTS](https://blog.jtlebi.fr/2013/12/22/introduction-to-linux-namespaces-part-1-uts/)
  /
  [part2](https://blog.jtlebi.fr/2013/12/28/introduction-to-linux-namespaces-part-2-ipc/)
  /[part3](https://blog.jtlebi.fr/2014/01/05/introduction-to-linux-namespaces-part-3-pid/)
  /
  [part4](https://blog.jtlebi.fr/2014/01/12/introduction-to-linux-namespaces-part-4-ns-fs/)
  /[part5](https://blog.jtlebi.fr/2014/01/19/introduction-to-linux-namespaces-part-5-net/)
* [Docker背后的内核知识——Namespace资源隔离](http://www.infoq.com/cn/articles/docker-kernel-knowledge-namespace-resource-isolation)


## 相关项目
### Compose
* [Docker Compose](http://docs.docker.com/compose/)
* [Announcing Docker Compose
](https://blog.docker.com/2015/02/announcing-docker-compose/)


### Swarm
* [剖析Docker Swarm和Mesos：是什么？如何结合？有什么优势？](http://dockerone.com/article/213) ([English](http://mesosphere.com/2015/02/26/deploying-with-docker-swarm/))
* [Getting Started with docker swarm](http://www.blackfinsecurity.com/getting-started-with-docker-swarm/)
* [Scaling docker with swarm](http://blog.docker.com/2015/02/scaling-docker-with-swarm/)
* [Docker Swarm入门（一）概观](http://dockerone.com/article/168) / [(二）配置选项与基本运行环境要求](http://dockerone.com/article/178) / [（三）Swarm SOA举例](http://dockerone.com/article/192) / [（四）Demo](http://dockerone.com/article/203)
* [Creating SSL/TLS Certificates for Docker and Docker Swarm](http://technolo-g.com/generate-ssl-for-docker-swarm/)
* [Running a Small Docker Swarm Cluster](http://blog.scottlowe.org/2015/03/06/running-own-docker-swarm-cluster/)


### Mesosphere
* [Launching a Docker Container on Mesosphere](https://mesosphere.com/docs/tutorials/launch-docker-container-on-mesosphere/) 
* [Managing Docker Clusters Using Mesos and Marathon](http://beingasysadmin.wordpress.com/2014/06/27/managing-docker-clusters-using-mesos-and-marathon/)
* [Docker on Mesos](https://mesosphere.com/2013/09/26/docker-on-mesos/)
* [Running Docker Containers on Marathon](https://mesosphere.github.io/marathon/docs/native-docker.html)
* [Mesos + Docker Tutorial: How to Build Your Own Framework](http://codefutures.com/mesos-docker-tutorial-how-to-build-your-own-framework/)
* [ArangoDB on Apache Mesos using Marathon and Docker](https://github.com/arangodb/Cookbook/blob/master/recipes/UsingArangoDBMesosphere.md)
* [Continuous Delivery with Docker on Mesos in less than a minute – Part 1](http://container-solutions.com/2015/03/continuous-delivery-with-docker-on-mesos-in-less-than-a-minute/) / [part2](http://container-solutions.com/2015/03/continuous-delivery-with-docker-on-mesos-in-less-than-a-minute-part-2/)
* [TOWARDS DOCKER IN PRODUCTION WITH APACHE MESOS](http://www.ivoverberk.nl/towards-docker-in-production-with-apache-mesos/)

### Kubernetes
* [Deploying Kubernetes on CoreOS with Fleet and Flannel](https://github.com/kelseyhightower/kubernetes-fleet-tutorial)
* [Running Kubernetes Example on CoreOS, Part 1](https://coreos.com/blog/running-kubernetes-example-on-CoreOS-part-1/)
* [How To Install and Configure Kubernetes on top of a CoreOS Cluster](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-kubernetes-on-top-of-a-coreos-cluster)
* [Corekube: Running Kubernetes on CoreOS via OpenStack](https://developer.rackspace.com/blog/running-coreos-and-kubernetes/)
* [基于Kubernetes构建Docker集群管理详解](http://www.csdn.net/article/2014-12-24/2823292-Docker-Kubernetes)
* [Play With Kubernetes Quickly Using Docker](https://zwischenzugs.wordpress.com/2015/04/06/play-with-kubernetes-quickly-using-docker/)

### Openstack
* [docker](https://wiki.openstack.org/wiki/Docker)
* [Mesos vs OpenStack?谁才是私有云的未来](http://dockerone.com/article/224) ([English](http://www.quora.com/What-is-the-future-of-the-private-cloud-world-Mesos-or-OpenStack?from=timeline&isappinstalled=0))

### Azure
* [Docker and Microsoft: Integrating Docker with Windows Server and Microsoft Azure](http://weblogs.asp.net/scottgu/docker-and-microsoft-integrating-docker-with-windows-server-and-microsoft-azure)
* [Windows Docker内部原理猜想](http://weibo.com/p/1001603824898261799110)

### Others
* [Chef, Puppet, Heat, Juju, Docker, etc](https://docwhat.org/chef-puppet-heat-juju-docker-etc/)
* [Powerstrip: prototype Docker extensions today](https://clusterhq.com/blog/powerstrip-prototype-docker-extensions-today/?)
* [Docker extensions: the new Docker plugins model](https://clusterhq.com/blog/docker-extensions/)
* [Docker Without Containers: Introducing Pullcontainer --docker and CVFS](http://blog.terminal.com/docker-without-containers-pulldocker/)
* [Process Management with CFEngine](https://docs.docker.com/articles/cfengine_process_management/) (CFEngine)
* [Introducing flannel: An etcd backed overlay network for containers](https://coreos.com/blog/introducing-rudder/) (flannel)
* [Tiny docker operating system](https://blog.docker.com/2015/03/tiny-docker-operating-systems/) (Boot2Docker,RancherOS)
* [Deploying Docker applications on YARN via Slider](http://pan.baidu.com/s/1jGy1utC) (PPT)(YARN)

## 应用

### Apps
* [Dockerizing a Python Web App](http://blogs.aws.amazon.com/application-management/post/Tx1ZLAHMVBEDCOC/Dockerizing-a-Python-Web-App)
* [Deploying NGINX and NGINX Plus with Docker](http://nginx.com/blog/deploying-nginx-nginx-plus-docker/)
* [Automated Nginx Reverse Proxy for Docker](http://jasonwilder.com/blog/2014/03/25/automated-nginx-reverse-proxy-for-docker/)
* [Transparent Squid in a container](https://github.com/jpetazzo/squid-in-a-can)
* [Deploying and migrating a multi-node ElasticSearch-Logstash-Kibana cluster using Docker](https://clusterhq.com/blog/deploying-multi-node-elasticsearch-logstash-kibana-cluster-using-docker/)
* [Node With Docker - Continuous Integration and Delivery](http://mherman.org/blog/2015/03/06/node-with-docker-continuous-integration-and-delivery/#.VPsh0YGUerE)
* [Rails on Docker](https://robots.thoughtbot.com/rails-on-docker)
* [Ad Hoc Log Analysis with Kibana and Docker](https://www.cloudgear.net/blog/2015/apache-log-analysis-with-kibana-docker/)
* [Networking Spark Cluster on Docker with Weave](http://weaveblog.com/2015/02/19/networking-spark-cluster-on-docker-with-weave/)
* [Breaking Data Out of the Enterprise](http://read.payne.io/2015/02/19/breaking_data_out_of_the_enterprise.html)
* [Using dockeer to build a data acqusition pipeline with kafka and hbase](http://svds.com/post/using-docker-build-data-acquisition-pipeline-kafka-and-hbase)
* [How to use MongoDB & NodeJS with Docker](http://ifdattic.com/how-to-mongodb-nodejs-docker/)
* [Wrapping Desktop Apps with Docker](http://container-solutions.com/2014/10/wrapping-desktop-apps-docker/)
* [Deploying RethinkDB applications with Docker using Dokku](http://rethinkdb.com/blog/dokku-deployment/)
* [Shipping Node.js Applications with Docker and Codeship](http://blog.risingstack.com/shipping-node-js-applications-with-docker-and-codeship/)
* [Using Docker with Apache Flume - Part 1](http://probablyfine.co.uk/2014/05/05/using-docker-with-apache-flume-1/) / [part2](http://probablyfine.co.uk/2014/08/24/using-docker-with-apache-flume-2/)
* [Multi-node Hadoop cluster on Docker](http://blog.sequenceiq.com/blog/2014/06/19/multinode-hadoop-cluster-on-docker/)
* [Elasticsearch, Weave and Docker](http://weaveblog.com/2015/01/20/elasticsearch-and-weave/)
* [Running libvirtd in a container](http://www.projectatomic.io/blog/2014/10/libvirtd_in_containers/)
* [Creating honeypots using Docker](http://itinsight.hu/blog/posts/2015-05-04-creating-honeypots-using-docker.html)


### GUI
* [Docker Containers on the Desktop](https://blog.jessfraz.com/posts/docker-containers-on-the-desktop.html)
* [Running GUI apps with Docker](http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/)
* [Docker desktop: Your desktop over ssh running inside of a docker container ](http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/)

### 服务发现相关
* [Service Discovery Overview](http://www.simplicityitself.com/learning/getting-started-microservices/service-discovery-overview/)
* [Consul Service Discovery with Docker](http://www.davidmkerr.com/2014/08/dockerfile-golf-or-optimizing-docker.html)
* [Understanding Modern Service Discovery with Docker](http://progrium.com/blog/2014/07/29/understanding-modern-service-discovery-with-docker/)
* [Automatic Docker Service Announcement with Registrator](http://progrium.com/blog/2014/09/10/automatic-docker-service-announcement-with-registrator/)
* [Docker Service Discovery Using Etcd and Haproxy](http://jasonwilder.com/blog/2014/07/15/docker-service-discovery/)
* [Simulating service discovery in a development context with Docker and etcd](http://talwai.github.io/#/blog/post/discovery)

### 开发部署测试
* [Docker: Git for deployment](http://blog.scoutapp.com/articles/2013/08/28/docker-git-for-deployment)
* [Eight Docker Development Patterns](http://www.hokstad.com/docker/patterns)
* [Deploy Java Apps With Docker = Awesome](http://blogs.atlassian.com/2013/06/deploy-java-apps-with-docker-awesome/)
* [Docker for Java Developers: How to sandbox your app in a clean environment](http://zeroturnaround.com/rebellabs/docker-for-java-developers-how-to-sandbox-your-app-in-a-clean-environment/)
* [Using Docker with Github and Jenkins for repeatable deployments](http://blog.buddycloud.com/post/80771409167/using-docker-with-github-and-jenkins-for)
* [Creating an ASP.NET vNext Docker Container using Mono](https://msopentech.com/blog/2014/11/07/creating-asp-net-vnext-docker-container-using-mono-2/)
* [Move fast and don’t break things! Testing with Jenkins, Ansible and Docker](http://blog.mist.io/post/82383668190/move-fast-and-dont-break-things-testing-with)
* [Docker and Phoenix: How to Make Your Continuous Integration More Awesome](http://ariya.ofilabs.com/2014/12/docker-and-phoenix-how-to-make-your-continuous-integration-more-awesome.html)
* [Docker实战：更轻松、更愉快、更高效](http://dockerone.com/article/217) ([English](https://realpython.com/blog/python/docker-in-action-fitter-happier-more-productive/))
* [Docker in Action - Development to Delivery ](https://blog.rainforestqa.com/2014-11-19-docker-in-action-from-deployment-to-delivery-part-1-local-docker-setup/) / [part2](https://blog.rainforestqa.com/2014-12-08-docker-in-action-from-deployment-to-delivery-part-2-continuous-integration) / [part3](https://blog.rainforestqa.com/2015-01-15-docker-in-action-from-deployment-to-delivery-part-3-continuous-delivery)
* [ASP.NET 5 development on OS X with Docker](http://open.bekk.no/aspnet5-development-on-osx-with-docker)
* [减少使用Java应用服务器，迎接Docker容器](http://dockerone.com/article/267) ([English](https://medium.com/@jstrachan/the-decline-of-java-application-servers-when-using-docker-containers-edbe032e1f30))

### 企业实践
* [Docker at Lyst](http://developers.lyst.com/devops/2014/12/08/docker/)
* [Docker at Shopify: How we built containers that power over 100,000 online shops](http://www.shopify.com/technology/15934308-docker-at-shopify-how-we-built-containers-that-power-over-100-000-online-shops)
* [Intro to Docker ...and how we use it at writeLaTex](http://jdlm.info/ds-docker-demo/)
* [How We Use Docker For Continuous Delivery – Part 1](http://contino.co.uk/use-docker-continuously-deliver-microservices-part-1/)
* [How Syncano Used Docker to Simplify Their Development Process](https://www.hakkalabs.co/articles/use-docker-cant-live-without)
* [Docker in Production — What We’ve Learned Launching Over 300 Million Containers](http://blog.iron.io/2014/10/docker-in-production-what-weve-learned.html)
* [10x: Docker at Clay.io](http://zolmeister.com/2014/12/10x-docker-at-clay-io.html)
* [BATTLEFY : How We Ship](http://blog.battlefy.com/how-we-ship/)
* [Docker in Production — What We’ve Learned Launching Over 300 Million Containers](http://blog.iron.io/2014/10/docker-in-production-what-weve-learned.html)
* [A production ready Docker workflow](http://www.luiselizondo.net/a-production-ready-docker-workflow/) / [part2](http://www.luiselizondo.net/a-production-ready-docker-workflow-part-2-the-storage-problem/) / [part3](http://www.luiselizondo.net/a-production-ready-docker-workflow-part-3-orchestration-tools/) / [part4](http://www.luiselizondo.net/a-production-ready-docker-workflow-part-4-service-discovery-and-the-load-balancer/) 
* [How We Deploy Containers at Grammarly](http://tech.grammarly.com/blog/posts/How-We-Deploy-Containers-at-Grammarly.html)
* [Developing With Docker At 500px, Part One](http://developers.500px.com/2015/09/10/developing-with-docker-at-500px-pt1.html)
* [大规模Docker集群助力微博迎接春晚峰值挑战](http://weibo.com/p/1001603811301997572906)
* [Docker在春晚中的实际表现](http://weibo.com/p/1001603816339658657489)
* [Docker系列之二：基于容器的自动构建](http://tech.meituan.com/autobuild.html) (美团)
* [Mesos在去哪儿网的应用](http://dockone.io/article/675)

### 其他平台
* [Docker on Raspberry Pi](https://resin.io/blog/docker-on-raspberry-pi/)
* [The IoT Singularity: Docker for Internet of Things Devices](http://blogs.intel.com/evangelists/2015/01/28/iot-singularity-docker-internet-things-devices/)
* [Heavily ARMed after major upgrade: Raspberry Pi with Docker 1.5.0](http://blog.hypriot.com/heavily-armed-after-major-upgrade-raspberry-pi-with-docker-1-dot-5-0)
* [Getting Docker to run on Power8](https://blog.jtlebi.fr/2014/10/28/getting-docker-to-run-on-power8/)
* [Swarming Raspberry Pi – Part 1](http://matthewkwilliams.com/index.php/2015/03/21/swarming-raspberry-pi-part-1/)

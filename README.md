# docker-resources
docker资源汇总,随时更新，欢迎补充。

# 目录
* [资源汇集](#资源汇集)
  * [书籍](#书籍)
  * [网站](#网站)
  * [开源文档](#开源文档)
  * [内容聚合](#内容聚合)
* [相关项目](#相关项目)
  * [OS](#OS)
  * [竞争者](#竞争者)
  * [管理工具](#管理工具)
  * [Paas平台](#Paas平台)
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
  * [镜像及Dockerfile](#镜像及Dockerfile)
  * [容器](#容器)
  * [扩展](#扩展)
* [博文](#博文)
  * [介绍](#介绍)
  * [Docker技术](#Docker技术)
    * [镜像](#镜像)
    * [存储](#存储)
    * [Dockerfile](#Dockerfile)
    * [容器](#容器)
    * [安全](#安全)
    * [资源管理](#资源管理)
    * [网络](#网路)
    * [监控](#监控)
    * [私有仓库](#私有仓库)
    * [API](#API)
    * [性能](#性能)
  * [思考](#思考)
  * [底层技术](#底层技术)
    * [LXC](#LXC)
  * [相关组件](#相关组件)
    * [compose](#compose)
    * [swarm](#swarm)
  * [应用](#应用)
    * [Apps](#Apps)
    * [GUI](#GUI)
    * [服务发现](#服务发现)
    * [开发部署测试](#开发部署测试)
    * [企业实践](#企业实践)
    * [其他平台](#其他平台)

# 资源汇集
## 书籍
* [第一本Docker书](http://book.douban.com/subject/26285268/) (收费，推荐。)
* [Docker —— 从入门到实践](http://yeasy.gitbooks.io/docker_practice/content/) (开源，内容一般，慎入)
* [THE DOCKER BOOK](http://www.dockerbook.com/)

## 网站
### 英文
* [官方文档](https://docs.docker.com/) 
* [Docker项目地址](https://github.com/docker/docker)
* [Dockerhub](https://docs.docker.com/docker-hub/)
* [Century Links Labs](http://www.centurylinklabs.com/category/docker/)


### 中文
* [Dockerpool](http://dockerpool.com/) 
* [Docker中文](http://www.docker.org.cn/) 
* [Dockerone](http://dockerone.com/)

## 开源文档
* [Docker中文指南](https://github.com/widuu/chinese_docker)  (中文，质量一般，较老)
* [Docker Cheat Sheet](https://github.com/wsargent/docker-cheat-sheet#volumes)

## 内容聚合
* [awesome-docker](https://github.com/veggiemonk/awesome-docker) (英文docker资源汇总)
* [Docker Weekly Archives](http://blog.docker.com/docker-weekly-archives/)
* [Valuable Docker Links](http://www.nkode.io/2014/08/24/valuable-docker-links.html)
* [Docker Ecosystem](https://www.mindmeister.com/389671722/docker-ecosystem)
* [Digital Ocean Community](https://www.digitalocean.com/community/search?primary_filter=tutorials&query=docker)

# 相关项目
## OS
* [coreos](https://coreos.com/) (比较成熟)
* [RHEL Atomic Host](http://www.redhat.com/en/technologies/linux-platforms/enterprise-linux) (新出，内置kubernetes)
* [rancheio](http://rancher.com/) (较新)

## 竞争者
* [rocket](https://github.com/coreos/rocket) (coreos推出)

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
* 


## Paas平台
* [flynn](https://github.com/flynn/flynn)
* [deis](http://deis.io/)
* [peas](https://github.com/tombh/peas) (Docker and Ruby based PaaS)
* [dawn](https://github.com/dawn/dawn) (Docker-based PaaS in Ruby)
* [octohost](https://github.com/octohost/octohost)(Simple web focused Dockerfile based PaaS server)
* [dokku](https://github.com/progrium/dokku) (Docker powered mini-Heroku in around 100 lines of Bash)


## 项目集成
* [openstack-docker](https://github.com/docker/openstack-docker) (Nova driver and Glance backend to use Docker inside OpenStack)
* [Jenkins Cloud Plugin for Docker](https://github.com/jenkinsci/docker-plugin/)

## 监控
* [seagull](https://github.com/tobegit3hub/seagull) (Friendly Web UI to monitor docker daemon)
* [dockerana](https://github.com/dockerana/dockerana) (Docker Monitoring with support for Grafana and Graphite)
* [docker-mon](https://github.com/icecrime/docker-mon)(Console-based Docker monitoring)
* [cadvisor](https://github.com/google/cadvisor) (Analyzes resource usage and performance characteristics of running containers)
* 

## 网络
* [weave](https://github.com/zettio/weave)
* [wormhole](https://github.com/vishvananda/wormhole) (A smart proxy to connect docker containers.)
* [flannel](https://github.com/coreos/flannel) (flannel is an etcd backed network fabric for containers)

## 持续集成
* [drone](https://github.com/drone/drone)


## 开发部署
* [tug](https://github.com/nitrous-io/tug) (Docker development workflow)
* [vagga](https://github.com/tailhook/vagga)(Vagga is a tool to create development environments)
* [longshoreman](https://github.com/longshoreman/longshoreman) (Automated deployment with Docker)
* [centurion](https://github.com/newrelic/centurion) (A mass deployment tool for Docker fleets)
* 


## 日志
* [logspout](https://github.com/gliderlabs/logspout)
* [logjam](https://github.com/gocardless/logjam) (a log shipping tool)


## 服务发现
* [skydock](https://github.com/crosbymichael/skydock) (基于DNS)
* [Consul](https://www.consul.io/)
* [registrator](https://github.com/gliderlabs/registrator)(Service registry bridge for Docker with pluggable adapters)
* [etcd](https://github.com/coreos/etcd) (A highly-available key value store for shared configuration and service discovery)
* [docker-grand-ambassador](https://github.com/cpuguy83/docker-grand-ambassador) ( fully dynamic docker link ambassador)
* [confd](https://github.com/kelseyhightower/confd) (Manage local application configuration files using templates and data from etcd or consul)

## 私有仓库
* [docket](https://github.com/netvarun/docket) (Custom docker registry that allows for lightning fast deploys through bittorrent)
* [docker-registry](https://github.com/docker/docker-registry) (Registry server for Docker (hosting/delivering of repositories and images))


## 可视化工具
* [dockerboard](https://github.com/dockerboard/dockerboard) 
* [Kitematic](https://kitematic.com/) (用于MAC)
* [dockerui](https://github.com/crosbymichael/dockerui)
* [docker-registry-web](https://github.com/atc-/docker-registry-web) (A web UI for easy private/local Docker Registry integration)
* [panamax-ui](https://github.com/CenturyLinkLabs/panamax-ui) (The Web GUI for Panamax)
* 

## 存储
* [pfs](http://pachyderm-io.github.io/pfs/#whats-new-in-v02) (A git-like distributed file system for a dockerized world)
* [Docker Volume Manager](https://github.com/cpuguy83/docker-volumes)


## 镜像及Dockerfile
* [dockly](https://github.com/swipely/dockly) (DSL and Gem for building ready-to-launch Docker images)
* [baseimage-docker](https://github.com/phusion/baseimage-docker) (A minimal Ubuntu base image modified for Docker-friendlines)
* [busybox](https://github.com/jpetazzo/docker-busybox) (Busybox for Stackbrew)
* [busybox](https://github.com/progrium/busybox) (Busybox container with glibc+opkg)
* [dockerfile-examples](https://github.com/komljen/dockerfile-examples)
* [passenger-docker](https://github.com/phusion/passenger-docker) (Docker base images for Ruby, Python, Node.js and Meteor web apps)
* [Dockerfile Project](http://dockerfile.github.io/)
* [Dockerfiles](https://github.com/crosbymichael/Dockerfiles)(Collection of Dockerfiles)


## 容器
* [dockize](https://github.com/jwilder/dockerize) (Utility to simplify running applications in docker containers)
* [Supervisor](http://supervisord.org/)
* [CFEngine](http://cfengine.com/)
* [docker-gen](https://github.com/jwilder/docker-gen) (Generate files from docker container meta-data)


## 扩展
* [powerstrip](https://github.com/clusterhq/powerstrip) (A tool for prototyping Docker extensions)




# 博文
## 介绍
* [How to Use Docker on OS X: The Missing Guide](http://viget.com/extend/how-to-use-docker-on-os-x-the-missing-guide)
* [24 random docker tips](http://csaba.palfi.me/random-docker-tips/)
* [A Simple Way to Dockerize Applications](http://jasonwilder.com/blog/2014/10/13/a-simple-way-to-dockerize-applications/)

## Docker技术
### 镜像
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
* 

### 存储
* [Comprehensive Overview of Storage Scalability in Docker](http://developerblog.redhat.com/2014/09/30/overview-storage-scalability-docker/?utm_content=buffer8a955&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)

### Dockerfile
* [6 Dockerfile Tips from the Official Images](http://container-solutions.com/2014/11/6-dockerfile-tips-official-images/)
* [Writing Dockerfile](http://www.techbar.me/writing-dockerfile/)
* [How to Optimize Your Dockerfile](http://blog.tutum.co/2014/10/22/how-to-optimize-your-dockerfile/)
* [Dockerfile Golf (or optimizing the Docker build process)](http://www.davidmkerr.com/2014/08/dockerfile-golf-or-optimizing-docker.html)


### 容器
* [What is the difference between CMD and ENTRYPOINT in a Dockerfile?](http://stackoverflow.com/questions/21553353/what-is-the-difference-between-cmd-and-entrypoint-in-a-dockerfile)
* [Docker and the PID 1 zombie reaping problem](https://blog.phusion.nl/2015/01/20/docker-and-the-pid-1-zombie-reaping-problem/)
* [Data-only container madness](http://container42.com/2014/11/18/data-only-container-madness/)

### 安全
* [WHY YOU DON'T NEED TO RUN SSHD IN YOUR DOCKER CONTAINERS](http://blog.docker.com/2014/06/why-you-dont-need-to-run-sshd-in-docker/)
* [shocker: docker PoC VMM-container breakout](http://stealth.openwall.net/xSports/shocker.c)
* [Containers&Docker: How secure are they?](https://blog.docker.com/2013/08/containers-docker-how-secure-are-they/)
* [Docker and SELinux](http://www.projectatomic.io/docs/docker-and-selinux/)
* [Bringing new security features to Docker](https://opensource.com/business/14/9/security-for-docker)
* [Docker Secure Deployment Guidelines](https://github.com/GDSSecurity/Docker-Secure-Deployment-Guidelines)

### 资源管理
* [Resource management in Docker](https://goldmann.pl/blog/2014/09/11/resource-management-in-docker/) 与systemd有关

### 网络
* [DNS And docker containers](http://wiredcraft.com/blog/dns-and-docker-containers/)

### 监控
* [GATHERING LXC AND DOCKER CONTAINERS METRICS](http://blog.docker.com/2013/10/gathering-lxc-docker-containers-metrics/)
* [nsinit: per-container resource monitoring of Docker containers on RHEL/Fedora](http://www.breakage.org/2014/09/03/nsinit-per-container-resource-monitoring-of-docker-containers-on-rhelfedora/)


### 私有仓库
* [Docker Registry Rest API](http://tuhrig.de/docker-registry-rest-api/)


### API
* [DOCKER FROM A DISTANCE - THE REMOTE API](http://blog.trifork.com/2013/12/24/docker-from-a-distance-the-remote-api/) 
* [KVM and Docker LXC Benchmarking with OpenStack](http://bodenr.blogspot.com/2014/05/kvm-and-docker-lxc-benchmarking-with.html)

### 性能
* [PostgreSQL Performance on Docker](http://www.davidmkerr.com/2014/06/postgresql-performance-on-docker.html)
* [Performance Analysis of Docker on Red Hat Enterprise Linux 7](http://developerblog.redhat.com/2014/08/19/performance-analysis-docker-red-hat-enterprise-linux-7/)


## 思考
* [App Container and Docker](https://coreos.com/blog/app-container-and-docker/)
* [Lets review.. Docker (again)](http://iops.io/blog/docker-hype/)
* [docker is the heroku killer](http://www.brightball.com/devops/docker-is-the-heroku-killer)


## 底层技术
### LXC
* [Exploring LXC Networking](http://containerops.org/2013/11/19/lxc-networking/)

## 相关组件
### compose
* [http://docs.docker.com/compose/](http://docs.docker.com/compose/)

### swarm
* [Docker Containers at Scale (Our Take on Docker Swarm)](http://mesosphere.com/2015/02/26/deploying-with-docker-swarm/)

### Mesosphere
* [Launching a Docker Container on Mesosphere](https://mesosphere.com/docs/tutorials/launch-docker-container-on-mesosphere/) 
## 应用

### Apps
* [Dockerizing a Python Web App](http://blogs.aws.amazon.com/application-management/post/Tx1ZLAHMVBEDCOC/Dockerizing-a-Python-Web-App)
* [Deploying NGINX and NGINX Plus with Docker](http://nginx.com/blog/deploying-nginx-nginx-plus-docker/)
* [Automated Nginx Reverse Proxy for Docker](http://jasonwilder.com/blog/2014/03/25/automated-nginx-reverse-proxy-for-docker/)
* [Transparent Squid in a container](https://github.com/jpetazzo/squid-in-a-can)

### GUI
* [Docker Containers on the Desktop](https://blog.jessfraz.com/posts/docker-containers-on-the-desktop.html)
* [Running GUI apps with Docker](http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/)
* [Docker desktop: Your desktop over ssh running inside of a docker container ](http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/)

### 服务发现
* [Consul Service Discovery with Docker](http://www.davidmkerr.com/2014/08/dockerfile-golf-or-optimizing-docker.html)
* [Understanding Modern Service Discovery with Docker](http://progrium.com/blog/2014/07/29/understanding-modern-service-discovery-with-docker/)
* [Automatic Docker Service Announcement with Registrator](http://progrium.com/blog/2014/09/10/automatic-docker-service-announcement-with-registrator/)


### 开发部署测试
* [Docker: Git for deployment](http://blog.scoutapp.com/articles/2013/08/28/docker-git-for-deployment)
* [Eight Docker Development Patterns](http://www.hokstad.com/docker/patterns)
* [Deploy Java Apps With Docker = Awesome](http://blogs.atlassian.com/2013/06/deploy-java-apps-with-docker-awesome/)
* [Using Docker with Github and Jenkins for repeatable deployments](http://blog.buddycloud.com/post/80771409167/using-docker-with-github-and-jenkins-for)
* [Creating an ASP.NET vNext Docker Container using Mono](https://msopentech.com/blog/2014/11/07/creating-asp-net-vnext-docker-container-using-mono-2/)
* [Move fast and don’t break things! Testing with Jenkins, Ansible and Docker](http://blog.mist.io/post/82383668190/move-fast-and-dont-break-things-testing-with)
* [Docker and Phoenix: How to Make Your Continuous Integration More Awesome](http://ariya.ofilabs.com/2014/12/docker-and-phoenix-how-to-make-your-continuous-integration-more-awesome.html)


### 企业实践
* [Docker at Lyst](http://developers.lyst.com/devops/2014/12/08/docker/)
* [Docker at Shopify: How we built containers that power over 100,000 online shops](http://www.shopify.com/technology/15934308-docker-at-shopify-how-we-built-containers-that-power-over-100-000-online-shops)
* [Intro to Docker ...and how we use it at writeLaTex](http://jdlm.info/ds-docker-demo/)
* [How We Use Docker For Continuous Delivery – Part 1](http://contino.co.uk/use-docker-continuously-deliver-microservices-part-1/)
* 

### 其他平台
* [Docker on Raspberry Pi](https://resin.io/blog/docker-on-raspberry-pi/)


# docker-resources
docker资源汇总

# 目录
* [介绍](#介绍)
  * [书籍](#书籍)
  * [网站](#网站)
  * [开源文档](#开源文档)
  * [资源汇集](#资源汇集)
* [相关项目](#相关项目)
  * [OS](#OS)
  * [竞争者](#竞争者)
  * [管理工具](#管理工具)
  * [Paas平台](#Paas平台)
  * [项目集成](#项目集成)
  * [监控](#监控)
  * [网络](#网络)
  * [持续集成](#持续集成）
  * [开发环境](#开发环境)
  * [日志](#日志)
  * [服务发现](#服务发现)
  * [私有仓库](#私有仓库)
  * [可视化工具](#可视化工具)
  * [存储](#存储)
* [博文](#博文)
  * [Docker技术](#Docker技术)
    * [镜像](#镜像)
    * [存储](#存储)
    * [Dockerfile](#Dockerfile)
    * [容器](#容器)
    * [安全](#安全)
    * [开发部署](#开发部署）
    * [测试](#测试)
    * [资源管理](#资源管理)
    * [网络](#网路)
    * [监控](#监控)
    * [私有仓库](#私有仓库)
    * [API](#API)
    * [性能](#性能）
  * [思考](#思考)
  * [底层技术](#底层技术)
    * [LXC](#LXC)
  * [相关组件](#相关组件)
    * [compose](#compose)
    * [swarm](#swarm)
  * [应用](#应用)
    * [Apps](#Apps)
    * [GUI](#GUI)
    * [企业实践](#企业实践)
    * [其他平台](#其他平台)

# 介绍
## 书籍
* [第一本Docker书](http://book.douban.com/subject/26285268/) (收费，推荐。)
* [Docker —— 从入门到实践](http://yeasy.gitbooks.io/docker_practice/content/) (开源，内容一般，慎入)
* [THE DOCKER BOOK](http://www.dockerbook.com/)

## 网站
### 英文
* [官方文档](https://docs.docker.com/) 
* [Docker项目地址](https://github.com/docker/docker)
* [Dockerhub](https://docs.docker.com/docker-hub/)

### 中文
* [Dockerpool](http://dockerpool.com/) 
* [Docker中文](http://www.docker.org.cn/) 
* [Dockerone](http://dockerone.com/)

## 开源文档
* [Docker中文指南](https://github.com/widuu/chinese_docker)  (中文，质量一般，较老)

## 资源汇集
* [awesome-docker](https://github.com/veggiemonk/awesome-docker) (英文docker资源汇总)

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

## Paas平台
* [flynn](https://github.com/flynn/flynn)
* [deis](http://deis.io/)
* [peas](https://github.com/tombh/peas) (Docker and Ruby based PaaS)
* [dawn](https://github.com/dawn/dawn) (Docker-based PaaS in Ruby)

## 项目集成
* [openstack-docker](https://github.com/docker/openstack-docker) (Nova driver and Glance backend to use Docker inside OpenStack)
* 

## 监控

## 网络
* [weave](https://github.com/zettio/weave)
* [wormhole](https://github.com/vishvananda/wormhole) (A smart proxy to connect docker containers.)

## 持续集成
* [drone](https://github.com/drone/drone)
* 

## 开发环境
* [tug](https://github.com/nitrous-io/tug) (Docker development workflow)
* 

## 日志
* [logspout](https://github.com/gliderlabs/logspout)

## 服务发现
* [skydock](https://github.com/crosbymichael/skydock) (基于DNS)
* [Consul](https://www.consul.io/)

## 私有仓库
* [docket](https://github.com/netvarun/docket)

## 可视化工具
* [dockerboard](https://github.com/dockerboard/dockerboard) 
* [Kitematic](https://kitematic.com/) 用于MAC
* [dockerui](https://github.com/crosbymichael/dockerui)

## 存储
* [pfs](http://pachyderm-io.github.io/pfs/#whats-new-in-v02) (A git-like distributed file system for a dockerized world)

## 镜像


# 博文
## Docker技术
### 镜像
* [Docker Image Insecurity](https://titanous.com/posts/docker-insecurity)
* [Building good docker images](http://jonathan.bergknoff.com/journal/building-good-docker-images)
* [Your docker image might might be broken without you knowing it](http://phusion.github.io/baseimage-docker/)
* [Flat Docker images](http://3ofcoins.net/2013/09/22/flat-docker-images/)
* [Baseimage-docker, fat containers and "treating containers as VMs"](https://blog.phusion.nl/2015/01/20/baseimage-docker-fat-containers-treating-containers-vms/)

### 存储
* [Comprehensive Overview of Storage Scalability in Docker](http://developerblog.redhat.com/2014/09/30/overview-storage-scalability-docker/?utm_content=buffer8a955&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)

### Dockerfile
* [6 Dockerfile Tips from the Official Images](http://container-solutions.com/2014/11/6-dockerfile-tips-official-images/)
* [Writing Dockerfile](http://www.techbar.me/writing-dockerfile/)

### 容器
* [What is the difference between CMD and ENTRYPOINT in a Dockerfile?](http://stackoverflow.com/questions/21553353/what-is-the-difference-between-cmd-and-entrypoint-in-a-dockerfile)
* [Docker and the PID 1 zombie reaping problem](https://blog.phusion.nl/2015/01/20/docker-and-the-pid-1-zombie-reaping-problem/)

### 安全
* [WHY YOU DON'T NEED TO RUN SSHD IN YOUR DOCKER CONTAINERS](http://blog.docker.com/2014/06/why-you-dont-need-to-run-sshd-in-docker/)
* [shocker: docker PoC VMM-container breakout](http://stealth.openwall.net/xSports/shocker.c)
* [Containers&Docker: How secure are they?](https://blog.docker.com/2013/08/containers-docker-how-secure-are-they/)


### 开发部署
* [Docker: Git for deployment](http://blog.scoutapp.com/articles/2013/08/28/docker-git-for-deployment)
* [Eight Docker Development Patterns](http://www.hokstad.com/docker/patterns)
* [Deploy Java Apps With Docker = Awesome](http://blogs.atlassian.com/2013/06/deploy-java-apps-with-docker-awesome/)
* [Using Docker with Github and Jenkins for repeatable deployments](http://blog.buddycloud.com/post/80771409167/using-docker-with-github-and-jenkins-for)
* [Creating an ASP.NET vNext Docker Container using Mono](https://msopentech.com/blog/2014/11/07/creating-asp-net-vnext-docker-container-using-mono-2/)
* 

### 测试
* [Move fast and don’t break things! Testing with Jenkins, Ansible and Docker](http://blog.mist.io/post/82383668190/move-fast-and-dont-break-things-testing-with)

### 资源管理
* [Resource management in Docker](https://goldmann.pl/blog/2014/09/11/resource-management-in-docker/) 与systemd有关

### 网络
* [DNS And docker containers](http://wiredcraft.com/blog/dns-and-docker-containers/)

### 监控
* [GATHERING LXC AND DOCKER CONTAINERS METRICS](http://blog.docker.com/2013/10/gathering-lxc-docker-containers-metrics/)


### 私有仓库
* [Docker Registry Rest API](http://tuhrig.de/docker-registry-rest-api/)
* 

### API
* [DOCKER FROM A DISTANCE - THE REMOTE API](http://blog.trifork.com/2013/12/24/docker-from-a-distance-the-remote-api/) 
* [KVM and Docker LXC Benchmarking with OpenStack](http://bodenr.blogspot.com/2014/05/kvm-and-docker-lxc-benchmarking-with.html)

### 性能
* [PostgreSQL Performance on Docker](http://www.davidmkerr.com/2014/06/postgresql-performance-on-docker.html)


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
* 

### swarm
* [Docker Containers at Scale (Our Take on Docker Swarm)](http://mesosphere.com/2015/02/26/deploying-with-docker-swarm/)

## 应用

### Apps
* [Dockerizing a Python Web App](http://blogs.aws.amazon.com/application-management/post/Tx1ZLAHMVBEDCOC/Dockerizing-a-Python-Web-App)

### GUI
* [Docker Containers on the Desktop](https://blog.jessfraz.com/posts/docker-containers-on-the-desktop.html)
* [Running GUI apps with Docker](http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/)
* [Docker desktop: Your desktop over ssh running inside of a docker container ](http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/)


### 企业实践
* [Docker at Lyst](http://developers.lyst.com/devops/2014/12/08/docker/)
* [Docker at Shopify: How we built containers that power over 100,000 online shops](http://www.shopify.com/technology/15934308-docker-at-shopify-how-we-built-containers-that-power-over-100-000-online-shops)
* [Intro to Docker ...and how we use it at writeLaTex](http://jdlm.info/ds-docker-demo/)
* [How We Use Docker For Continuous Delivery – Part 1](http://contino.co.uk/use-docker-continuously-deliver-microservices-part-1/)
* 

### 其他平台
* [Docker on Raspberry Pi](https://resin.io/blog/docker-on-raspberry-pi/)
* 

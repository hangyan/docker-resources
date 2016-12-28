# Docker Resources All In One
A collection of docker online resources.

中文版本[链接](https://github.com/hangyan/docker-resources/blob/master/README_zh.md)

# Menu
* [Main Resources](#main-resources)
  * [Books](#books)
  * [Websites](#websites)
  * [Documents](#documents)
  * [Archives](#archives)
  * [Community Blogs](#community-blogs)
  * [Personal Blogs](#personal-blogs)
  * [Videos](#videos)
* [Related Projects](#related-projects)
  * [Core](#core)
  * [OS](#os)
  * [Virtual Machine](#virtual-machine)
  * [Competitors](#competitors)
  * [Management Tools](#management-tools)
  * [Paas Platforms](#paas-platforms)
  * [Caas Platforms](#caas-platforms)
  * [Integration Projects](#integration-projects)
  * [Monitoring](#monitoring)
  * [Networking](#networking)
  * [Continuous Integration](#continuous-integration)
  * [Development And Deployment](#development-and-deployment)
  * [Logging](#logging)
  * [Service Discovery](#service-discovery)
  * [Private Registry](#private-registry)
  * [UI Tools](#ui-tools)
  * [Storage](#storage)
  * [Volumes](#volumes)
  * [Security](#security)
  * [Applications](#applications)
  * [Images And Dockerfiles](#images-and-dockerfiles)
  * [Containers](#containers)
  * [Extensions](#extensions)
  * [API Client](#api-client)
  * [Others](#others)
* [Blog Posts](#blog-posts)
  * [General](#general)
  * [Docker](#docker)
    * [About Images](#about-images)
    * [About Storage](#about-storage)
    * [About Volumes](#about-volumes)
    * [Dockerfiles](#dockerfiles)
    * [About Containers](#about-containers)
    * [About Security](#about-security)
    * [Resource Management](#resource-management)
    * [About Networking](#about-networking)
    * [About Monitoring](#about-monitoring)
    * [About Private Registry](#about-private-registry)
    * [API](#api)
    * [Performance](#performance)
    * [Process Management](#process-management)
  * [Think Deeply](#think-deeply)
  * [Rocket](#rocket)
  * [Underlying Techniques](#underlying-techniques)
    * [LXC](#lxc)
    * [Cgroups](#cgroups)
    * [Systemd](#systemd)
    * [Namespaces](#namespaces)
  * [Various Projects](#various-projects)
    * [Compose](#compose)
    * [Swarm](#swarm)
    * [Mesosphere](#mesosphere)
    * [Kubernetes](#kubernetes)
    * [Openstack](#openstack)
    * [Azure](#azure)
    * [Other Projects](#other-projects)
  * [Usage](#usage)
    * [Apps](#apps)
    * [GUI](#gui)
    * [Service Discovery With Docker](#service-discovery-with-docker)
    * [Development And Deployment And Test](#development-and-deployment-and-test)
    * [Production](#production)
    * [Other Platforms](#other-platforms)

# Main Resources
## Books
* [The Docker Book](http://www.dockerbook.com/)
* [Orchestrating Docker](http://www.amazon.com/Orchestrating-Docker-Shrikrishna-Holla/dp/1783984783)
* [Docker in Action](http://www.manning.com/nickoloff/) (Early Access Edition)
* [Docker in Practice](http://manning.com/miell/?a_aid=zwischenzugs&a_bid=e0d48f62) (Early Access Edition)
* [Docker Cookbook](http://dockercookbook.github.io/) by Neependra Khare ([@neependra](https://twitter.com/neependra))
* [Docker Cookbook](http://shop.oreilly.com/product/0636920036791.do) by Sébastien Goasguen ([@sebgoa](https://twitter.com/sebgoa)) (Early Access Edition)
* [Docker Up & Running](http://shop.oreilly.com/product/0636920036142.do)
* [Using Docker](http://shop.oreilly.com/product/0636920035671.do) (Early Access Edition)
* [Docker for Java Developers](https://www.nginx.com/resources/library/docker-for-java-developers/)

## Websites

* [Official Documents](https://docs.docker.com/) 
* [Docker Source Code](https://github.com/docker/docker)
* [Dockerhub](https://docs.docker.com/docker-hub/)
* [Coreos Official Documents](https://coreos.com/docs/)



## Documents
* [Docker Cheat Sheet](https://github.com/wsargent/docker-cheat-sheet#volumes)
* [Docker Guidebook](https://github.com/kencochrane/docker-guidebook)
* [The Docker Ecosystem](https://www.digitalocean.com/community/tutorial_series/the-docker-ecosystem)

## Archives
* [awesome-docker](https://github.com/veggiemonk/awesome-docker) 
* [Docker Weekly Archives](http://blog.docker.com/docker-weekly-archives/)
* [Valuable Docker Links](http://www.nkode.io/2014/08/24/valuable-docker-links.html)
* [Docker Ecosystem](https://www.mindmeister.com/389671722/docker-ecosystem)
* [Digital Ocean Community](https://www.digitalocean.com/community/search?primary_filter=tutorials&query=docker)
* [Docker news](https://medium.com/docker-news)

## Community Blogs
* [Official Blogs](http://blog.docker.com/)
* [Coreos Official Blogs](https://coreos.com/blog/)
* [Century Links Labs](http://www.centurylinklabs.com/category/docker/)
* [SequenceIQ Blog](http://blog.sequenceiq.com/)
* [Tutum Blog](http://blog.tutum.co/)
* [Weave Blog](http://weaveblog.com/)
* [Odd Bits](http://blog.oddbit.com/)
* [Project Atomic](http://www.projectatomic.io/blog/)
* [Container Solutions](http://container-solutions.com/blog/)

## Personal Blogs
* [jpetazzo](http://jpetazzo.github.io/)
* [Jeff Lindsay](http://progrium.com/blog/)
* [Jason Wilder](http://jasonwilder.com/)
* [Michael Crosby](http://crosbymichael.com/)
* [Matt Bajor](http://technolo-g.com/)
* [Scott's Weblog](http://blog.scottlowe.org/2015/02/06/quick-intro-to-consul/)
* [Luis Elizondo](http://www.luiselizondo.net)
* [zwischenzugs](https://zwischenzugs.wordpress.com)
* [Musings of Matt Williams](http://matthewkwilliams.com/)

## Videos
* [Docker Tutorial](https://www.youtube.com/watch?v=bV5vbNK3Uhw&list=PLkA60AVN3hh_6cAz8TUGtkYbJSL2bdZ4h&index=1)
* [Introduction to Docker](https://www.youtube.com/watch?v=Q5POuMHxW-0)
* [Docker channel](https://www.youtube.com/user/dockerrun)
* [Docker 101 Tutorial](https://www.youtube.com/watch?v=VeiUjkiqo9E)
* [Docker at Spotify](https://www.youtube.com/watch?v=pts6F00GFuU)
* [Docker Clustering on Mesos with Marathon](https://www.youtube.com/watch?v=hZNGST2vIds)


# Related Projects

## Core
* [containerd](https://github.com/docker/containerd/)

## OS
* [Coreos](https://coreos.com/) (Linux for Massive Server Deployments)
* [Atomic](http://www.redhat.com/en/files/resources/en-rhel-atomic-host-datasheet-INC0223751.pdf) (A platform optimized for Linux containers) 
* [Rancheio](http://rancher.com/) (Simple, elegant tools for managing Docker in production)
* [Snappy](http://developer.ubuntu.com/en/snappy/) (A new, transactionally updated Ubuntu for clouds and devices)
* [Photon](https://github.com/vmware/photon)
* [ClearLinux](https://clearlinux.org) (The Clear Linux™ Project for Intel® Architecture is a project that is building a Linux OS distribution for various cloud use cases)
* [Mirage OS](https://mirage.io/) (Unikernel)

## Virtual Machine
* [boot2docker](https://github.com/boot2docker/boot2docker) (Lightweight Linux for Docker)
* [dvm](https://github.com/fnichol/dvm) (An on demand Docker virtual machine)

## Competitors
* [rocket](https://github.com/coreos/rocket)  (App Container runtime)
* [dockerlite](https://github.com/docker/dockerlite) (Lightweight virtualization system based on LXC and BTRFS)
* [lmctfy](https://github.com/google/lmctfy) (lmctfy is the open source version of Google’s container stack, which provides Linux application containers.)
* [OpenVZ](https://openvz.org/Main_Page)
* [Hyper](https://www.hyper.sh/) (Hyper = Hypervisor + Kernel + Docker Image)
* [bocker](https://github.com/p8952/bocker) (Docker implemented in around 100 lines of bash)
* [lxd](https://github.com/lxc/lxd) (Daemon based on liblxc offering a REST API to manage containers )

## Management Tools
* [kubernetes](https://github.com/GoogleCloudPlatform/kubernetes) (Container Cluster Manager)
* [shipyard](https://github.com/shipyard/shipyard)   (Composable Docker Management)
* [swarm](https://github.com/docker/swarm) (A Docker-native clustering system)
* [citadel](https://github.com/citadel/citadel) (A toolkit for building a distributed docker cluster)
* [docker-cluster](https://github.com/tsuru/docker-cluster) (Cluster support for Docker, using the remote API) 
* [compose](https://github.com/docker/compose) (Define and run complex applications using Docker)
* [shutit](https://github.com/ianmiell/shutit) (Complex and Dynamic Docker Builds Made Simple)
* [maestro](https://github.com/toscanini/maestro) (Container orchestration for Docker environments)
* [decking](https://github.com/meetfinch/decking) (A Docker helper to create, manage and run clusters of containers)
* [flocker](https://github.com/ClusterHQ/flocker) (Easily manage Docker containers & their data)
* [serf](https://github.com/hashicorp/serf) (Service orchestration and management tool)
* [marathon](https://github.com/mesosphere/marathon) (Deploy and manage containers (including Docker) on top of Apache Mesos at scale)
* [gaudi](https://github.com/marmelab/gaudi) (Gaudi allows to share multi-component applications, based on Docker, Go, and YAML)
* [panamax](http://panamax.io/) (Docker management for humans)
* [clocker](https://github.com/brooklyncentral/clocker) (Brooklyn managed Docker containers)
* [fleet] (https://github.com/coreos/fleet) (A Distributed init System)
* [Meteor](https://github.com/meteorhacks/cluster)(Clustering solution for Meteor with load balancing and service discovery)
* [helios](https://github.com/spotify/helios) (Docker container orchestration platform)
* [maestro-ng](https://github.com/signalfuse/maestro-ng) (Orchestration of Docker-based, multi-host environments)
* [shipper](https://github.com/mailgun/shipper) (Fabric for docker containers)
* [origin](https://github.com/openshift/origin) (OpenShift 3 - build, deploy, and manage your applications with Docker and Kubernetes)
* [autodock](https://github.com/cholcombe973/autodock) (The docker container automation tool.)
* [blockade](https://github.com/dcm-oss/blockade) (Docker-based utility for testing network failures and partitions in distributed applications,[docs](http://blockade.readthedocs.org/))
* [rancher](https://github.com/rancherio/rancher) (A Platform for Operating Docker in Production.[rancher.com](http://rancher.com/))
* [rocker-compose](https://github.com/grammarly/rocker-compose) (Docker composition tool with idempotency features for deploying apps composed of multiple containers.)
* [chronos](https://github.com/mesos/chronos)(Fault tolerant job scheduler for Mesos which handles dependencies and ISO8601 based schedules)

## Paas Platforms
* [flynn](https://github.com/flynn/flynn) (A next generation open source platform as a service)
* [deis](http://deis.io/) (Your PaaS. Your Rules)
* [peas](https://github.com/tombh/peas) (Docker and Ruby based PaaS)
* [dawn](https://github.com/dawn/dawn) (Docker-based PaaS in Ruby)
* [octohost](https://github.com/octohost/octohost)(Simple web focused Dockerfile based PaaS server)
* [dokku](https://github.com/progrium/dokku) (Docker powered mini-Heroku in around 100 lines of Bash)
* [cloudfoundry](https://github.com/cloudfoundry) 
* [paz](https://github.com/yldio/paz) (A pluggable in-house service platform with a PaaS-like workflow, built on Docker, CoreOS, Etcd and Fleet)
* [armada](https://github.com/armadaplatform/armada) (Complete solution for development, deployment, configuration and discovery of microservices)


## Caas Platforms
* [Docker Datacenter](https://www.docker.com/products/docker-datacenter)
* [Alauda.io](http://alauda.io/)

## Integration Projects
* [openstack-docker](https://github.com/docker/openstack-docker) (Nova driver and Glance backend to use Docker inside OpenStack)
* [Jenkins Cloud Plugin for Docker](https://github.com/jenkinsci/docker-plugin/)
* [deimos](https://github.com/mesosphere/deimos) (Mesos containerizer hooks for Docker)
* [garether-docker](https://github.com/garethr/garethr-docker) (Puppet module for managing docker)
* [systemd-docker](https://github.com/ibuildthecloud/systemd-docker) (Wrapper for "docker run" to handle systemd quirks)
* [docker-ansible](https://github.com/cove/docker-ansible) (Ansible module for Docker)

## Monitoring
* [seagull](https://github.com/tobegit3hub/seagull) (Friendly Web UI to monitor docker daemon)
* [dockerana](https://github.com/dockerana/dockerana) (Docker Monitoring with support for Grafana and Graphite)
* [docker-mon](https://github.com/icecrime/docker-mon)(Console-based Docker monitoring)
* [cadvisor](https://github.com/google/cadvisor) (Analyzes resource usage and performance characteristics of running containers)
* [Prometheus](https://github.com/prometheus/prometheus) (The Prometheus  monitoring system and time series database,see the [docker exporter](https://github.com/docker-infra/container_exporter))

## Networking
* [weave](https://github.com/zettio/weave) (The Docker Network)
* [wormhole](https://github.com/vishvananda/wormhole) (A smart proxy to connect docker containers.)
* [flannel](https://github.com/coreos/flannel) (flannel is an etcd backed network fabric for containers)
* [calico-docker](https://github.com/Metaswitch/calico-docker)(Docker version of Project Calico,Calico can provide networking in a Docker environment)
* [libnetwork](https://github.com/docker/libnetwork) (networking for containers)

## Continuous Integration
* [drone](https://github.com/drone/drone) (A Continuous Integration platform built on Docker)


## Development And Deployment
* [tug](https://github.com/nitrous-io/tug) (Docker development workflow)
* [vagga](https://github.com/tailhook/vagga)(Vagga is a tool to create development environments)
* [longshoreman](https://github.com/longshoreman/longshoreman) (Automated deployment with Docker)
* [centurion](https://github.com/newrelic/centurion) (A mass deployment tool for Docker fleets)
* [shutit](https://github.com/ianmiell/shutit) (Complex and Dynamic Docker Builds Made Simple)
* [dockership](https://github.com/mcuadros/dockership) (dead simple docker deploy tool)
* [devstep](https://github.com/fgrehm/devstep) (Development environments powered by Docker and buildpacks)
* [docker-devenv](https://github.com/wsargent/docker-devenv) (Docker based development environment)
* [dexec](https://github.com/docker-exec/dexec) (Command line interface for running code with Docker Exec images)

## Logging
* [logspout](https://github.com/gliderlabs/logspout) (Log routing for Docker container logs)
* [logjam](https://github.com/gocardless/logjam) (a log shipping tool)


## Service Discovery
* [skydock](https://github.com/crosbymichael/skydock) (based on DNS)
* [Consul](https://www.consul.io/) (Consul is a tool for service discovery, monitoring and configuration)
* [registrator](https://github.com/gliderlabs/registrator)(Service registry bridge for Docker with pluggable adapters)
* [etcd](https://github.com/coreos/etcd) (A highly-available key value store for shared configuration and service discovery)
* [docker-grand-ambassador](https://github.com/cpuguy83/docker-grand-ambassador) ( fully dynamic docker link ambassador)
* [confd](https://github.com/kelseyhightower/confd) (Manage local application configuration files using templates and data from etcd or consul)
* [ambassadord](https://github.com/progrium/ambassadord) (Magic Docker ambassador)
* [logcabin](https://github.com/logcabin/logcabin) (LogCabin is a distributed storage system built on Raft that provides a small amount of highly replicated, consistent storage)

## Private Registry
* [docket](https://github.com/netvarun/docket) (Custom docker registry that allows for lightning fast deploys through bittorrent)
* [docker-registry](https://github.com/docker/docker-registry) (Registry server for Docker (hosting/delivering of repositories and images))
* [wharf](https://github.com/dockercn/wharf)(ContainerOps Open Source Platform)
* [distribution](https://github.com/docker/distribution) (The Docker toolset to pack, ship, store, and deliver content)
* [dogestry] (https://github.com/blake-education/dogestry) (simple docker image storage on s3)
* [docker-private-registry](https://github.com/shipyard/docker-private-registry) (Private Docker Registry)
* [speedy](https://github.com/jcloudpub/speedy) (a distributed docker image storage)

## UI Tools
* [dockerboard](https://github.com/dockerboard/dockerboard)  (Simple dashboards, visualizations, managements for your dockers)
* [Kitematic](https://kitematic.com/) (Now part of the Docker Toolbox. Available for Mac OS X 10.8+ and Windows 7+ (64-bit) )
* [dockerui](https://github.com/crosbymichael/dockerui) (A web interface for docker)
* [docker-registry-web](https://github.com/atc-/docker-registry-web) (A web UI for easy private/local Docker Registry integration)
* [Portus](https://github.com/SUSE/Portus) (Authorization service and frontend for Docker registry v2)
* [panamax-ui](https://github.com/CenturyLinkLabs/panamax-ui) (The Web GUI for Panamax)
* [seagull](https://github.com/tobegit3hub/seagull) (Friendly Web UI to monitor docker daemon)
* [docker-swarm-visualizer](https://github.com/ManoMarks/docker-swarm-visualizer)(A visualizer for Docker Swarm using the Docker Remote API, Node.JS, and D3)
* [portainer](http://portainer.io/) ( Simple management ui for docker )

## Storage
* [pfs](http://pachyderm-io.github.io/pfs/#whats-new-in-v02) (A git-like distributed file system for a dockerized world)


## Volumes
* [docker-volumes](https://github.com/cpuguy83/docker-volumes) (Docker Volume Manager)

## Security
* [subuser](https://github.com/subuser-security/subuser) (Run programs in linux with selectively restricted permissions)
* [TUF](http://theupdateframework.com/) (Like the S in HTTPS, a plug-and-play library for securing a software updater)
* [container-compliance](https://github.com/OpenSCAP/container-compliance)(Assessing compliance of a container)

## Applications
* [ferry](https://github.com/cirruspath/ferry) (define, run, and deploy big data applications on AWS, OpenStack, and your local machine using Docker,[ferry.opencore.io](http://ferry.opencore.io/))
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
* [dockercraft](https://github.com/docker/dockercraft) (Docker + Minecraft = Dockercraft)

## Images And Dockerfiles
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
* [Wordpress+nginx](https://github.com/eugeneware/docker-wordpress-nginx) (A
  Dockerfile that installs the latest wordpress, nginx and php-fpm.another
  wordpress [image](https://github.com/jbfink/docker-wordpress)) / another one [wordpress](https://github.com/dz0ny/docker-wpdev)
* [Nignx-Proxy](https://github.com/jwilder/nginx-proxy) (Automated nginx proxy for Docker containers using docker-gen)
* [docker-squash](https://github.com/jwilder/docker-squash) (Squash docker images to make them smaller)
* [Mysql](https://github.com/tutumcloud/tutum-docker-mysql) (Docker image to run an out-of-the-box MySQL server)
* [CentOS-Dockerfiles](https://github.com/CentOS/CentOS-Dockerfiles) (Dockerfiles for various common implementations)
* [Redmine](https://github.com/sameersbn/docker-redmine) (Dockerized redmine app server)
* [Spark](https://github.com/amplab/docker-scripts) (Dockerfiles and scripts for Spark and Shark Docker images)
* [docker-grafana-graphite](https://github.com/kamon-io/docker-grafana-graphite) (Docker image with StatsD, Graphite, Grafana and a Kamon Dashboard)
* [Elasticsearch](https://github.com/dockerfile/elasticsearch) (ElasticSearch Dockerfile for trusted automated Docker builds)
* [docker-alpine](https://github.com/gliderlabs/docker-alpine) (Docker image based on Alpine Linux will help you win at minimalism)
* [Hadoop](https://github.com/sequenceiq/hadoop-docker) (Hadoop docker image)
* [R](https://github.com/rocker-org/rocker) (R configurations for Docker)
* [ASP.NET](https://github.com/aspnet/aspnet-docker) (Docker image for ASP.NET 5.)
* [nmpjs](https://github.com/terinjokes/docker-npmjs) (Docker image for a private npmjs repository)
* [Jenkins](https://github.com/aespinosa/docker-jenkins) (Builds a Docker image for Jenkins)
* [Postgres](https://github.com/docker-library/postgres) (Docker Official Image packaging for Postgres)
* [Logstash](https://github.com/pblittle/docker-logstash) (Docker image for Logstash 1.4 )
* [Harbor](https://github.com/vmware/harbor) (An enterprise-class container registry server based on Docker Distribution)

## Containers
* [dockize](https://github.com/jwilder/dockerize) (Utility to simplify running applications in docker containers)
* [Supervisor](http://supervisord.org/) (A Process Control System)
* [CFEngine](http://cfengine.com/) (Process management)
* [docker-gen](https://github.com/jwilder/docker-gen) (Generate files from docker container meta-data)
* [tini](https://github.com/krallin/tini) (A tiny but valid `init` for containers)
* [S6](http://skarnet.org/software/s6/) (s6 is a small suite of programs for UNIX, designed to allow process supervision)

## Extensions
* [powerstrip](https://github.com/clusterhq/powerstrip) (A tool for prototyping Docker extensions)

## API Client
* [docker-py](https://github.com/docker/docker-py) (**Python**)
* [docker-api](https://github.com/swipely/docker-api) (**Ruby**)
* [dockernode](https://github.com/apocas/dockerode) (**Node.js**)
* [go-dockerclient](https://github.com/fsouza/go-dockerclient) (**Golang**)
* [docker-php](https://github.com/stage1/docker-php) (**PHP**)
* [dockerclient](https://github.com/samalba/dockerclient) (**Golang**)
* [docker-java](https://github.com/kpelykh/docker-java) (**Java**)

## Others
* [dockersh](https://github.com/Yelp/dockersh) (A shell which places users into individual docker containers)
* [buildstep](https://github.com/progrium/buildstep) (Buildstep uses Docker and Buildpacks to build applications like Heroku)
* [dind](https://github.com/jpetazzo/dind)(Docker in Docker)
* [building](https://github.com/CenturyLinkLabs/building) (Build a Docker container for any app using Heroku Buildpacks)
* [torrent-docker](https://github.com/mafintosh/torrent-docker) (realtime boot of remote docker images using bittorrent)
* [docker-backup](https://github.com/docker-infra/docker-backup) (Tool for backing up docker volume / data containers)
* [Docker Support in IntelliJ IDEA 14.1](http://blog.jetbrains.com/idea/2015/03/docker-support-in-intellij-idea-14-1/)
* [dockerception](https://github.com/jamiemccrindle/dockerception) (Docker building dockers - keeping them small)
* [docker-gc](https://github.com/spotify/docker-gc) (Docker garbage collection of containers and images)
* [habitus](https://github.com/cloud66/habitus)(A Build Flow Tool for Docker)

# Blog Posts
## General
* [The Frontend Developer's Guide to Docker](http://www.bryanbraun.com/2014/07/15/the-frontend-developers-guide-to-docker)
* [Docker and Go: why did we decide to write Docker in Go?](http://www.slideshare.net/jpetazzo/docker-and-go-why-did-we-decide-to-write-docker-in-go) ( pdf slide)
* [How to Use Docker on OS X: The Missing Guide](http://viget.com/extend/how-to-use-docker-on-os-x-the-missing-guide)
* [24 random docker tips](http://csaba.palfi.me/random-docker-tips/)
* [The 5 Most Important Things I’ve Learned From Using Docker](http://blog.tutum.co/2014/10/28/the-5-most-important-things-ive-learned-from-using-docker/)
* [A Simple Way to Dockerize Applications](http://jasonwilder.com/blog/2014/10/13/a-simple-way-to-dockerize-applications/)
* [Docker orchestration](http://chrisbarra.me/posts/docker-orchestration.html)
* [Docker's rise from sleeper to open source king](http://www.cnbc.com/id/102422954)
* [Faster Builds with Container-Based Infrastructure and Docker](http://blog.travis-ci.com/2014-12-17-faster-builds-with-container-based-infrastructure/)
* [Run ARM binaries in your Docker Container using Boot2Docker…](http://neophob.com/2014/10/run-arm-binaries-in-your-docker-container-using-boot2docker/)
* [How to Use Docker on Windows](http://blog.tutum.co/2014/11/05/how-to-use-docker-on-windows/)
* [Docker on OS X with VMWare Fusion](http://ewen.mcneill.gen.nz/blog/entry/2014-09-20-docker-on-osx-with-vmware-fusion/)

## Docker
### About Images
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

### About Storage
* [Comprehensive Overview of Storage Scalability in Docker](http://developerblog.redhat.com/2014/09/30/overview-storage-scalability-docker/?utm_content=buffer8a955&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)
* [Resizing Docker containers with the Device Mapper plugin](http://jpetazzo.github.io/2014/01/29/docker-device-mapper-resize/)
* [Where are Docker images stored?](http://blog.thoward37.me/articles/where-are-docker-images-stored/)
* [Persistent Distributed Filesystems in Docker without NFS or Gluster](http://www.centurylinklabs.com/persistent-distributed-filesystems-in-docker-without-nfs-or-gluster/)
* [Deep dive into Docker storage drivers](http://jpetazzo.github.io/assets/2015-03-03-not-so-deep-dive-into-docker-storage-drivers.html#1)


### About Volumes
* [Understanding Volumes in Docker](http://container-solutions.com/2014/12/understanding-volumes-docker/)
* [Powerstrip-flocker: Portable volumes using just the Docker CLI](https://clusterhq.com/blog/powerstrip-flocker-portable-volumes-using-just-docker-cli/)


### Dockerfiles
* [6 Dockerfile Tips from the Official Images](http://container-solutions.com/2014/11/6-dockerfile-tips-official-images/)
* [Writing Dockerfile](http://www.techbar.me/writing-dockerfile/)
* [How to Optimize Your Dockerfile](http://blog.tutum.co/2014/10/22/how-to-optimize-your-dockerfile/)
* [Dockerfile Golf (or optimizing the Docker build process)](http://www.davidmkerr.com/2014/08/dockerfile-golf-or-optimizing-docker.html)
* [Dockerfile Best Practices](http://crosbymichael.com/dockerfile-best-practices.html)



### About Containers
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

### About Security
* [Why you don't need to run sshd in your docker containers](http://blog.docker.com/2014/06/why-you-dont-need-to-run-sshd-in-docker/)
* [shocker: docker PoC VMM-container breakout](http://stealth.openwall.net/xSports/shocker.c)
* [Containers&Docker: How secure are they?](https://blog.docker.com/2013/08/containers-docker-how-secure-are-they/)
* [Docker and SELinux](http://www.projectatomic.io/docs/docker-and-selinux/)
* [Bringing new security features to Docker](https://opensource.com/business/14/9/security-for-docker)
* [Docker Secure Deployment Guidelines](https://github.com/GDSSecurity/Docker-Secure-Deployment-Guidelines)
* [Docker Container Breakout Proof-Of-Concept Exploit](http://outofmemory.cn/wr/?u=http%3A%2F%2Fblog.docker.com%2F2014%2F06%2Fdocker-container-breakout-proof-of-concept-exploit%2F)
* [The dangers of UFW + Docker](http://blog.viktorpetersson.com/post/101707677489/the-dangers-of-ufw-docker)
* [Tuning Docker with the newest security enhancements](https://opensource.com/business/15/3/docker-security-tuning)


### Resource Management
* [Resource management in Docker](https://goldmann.pl/blog/2014/09/11/resource-management-in-docker/) 

### About Networking
* [Advanced networking](https://docs.docker.com/articles/networking/)
* [DNS And docker containers](http://wiredcraft.com/blog/dns-and-docker-containers/)
* [Coupling Docker and Open vSwitch](http://fbevmware.blogspot.com/2013/12/coupling-docker-and-open-vswitch.html)
* [Connecting Docker containers on multiple hosts](https://goldmann.pl/blog/2014/01/21/connecting-docker-containers-on-multiple-hosts/)
* [Muti-host Docker Network](http://wiredcraft.com/blog/multi-host-docker-network/)
* [Life and Docker networking](http://weaveblog.com/2014/11/13/life-and-docker-networking/)
* [Docker intercontainer networking explained](http://blog.sequenceiq.com/blog/2014/08/12/docker-networking/)
* [SDN, Docker and the Real Changes Ahead](http://thenewstack.io/sdn-docker-real-changes-ahead/)
* [Four ways to connect a docker container to a local network](http://blog.oddbit.com/2014/08/11/four-ways-to-connect-a-docker/)
* [Docker intercontainer networking explained](http://blog.sequenceiq.com/blog/2014/08/12/docker-networking/)


### About Monitoring
* [Gathering lxc and docker containers metrics](http://blog.docker.com/2013/10/gathering-lxc-docker-containers-metrics/)
* [nsinit: per-container resource monitoring of Docker containers on RHEL/Fedora](http://www.breakage.org/2014/09/03/nsinit-per-container-resource-monitoring-of-docker-containers-on-rhelfedora/)
* [Runtime Metrics](https://docs.docker.com/articles/runmetrics/)
* [Monitor Docker Containers with Prometheus](http://5pi.de/2015/01/26/monitor-docker-containers-with-prometheus/)



### About Private Registry
* [Docker Registry Rest API](http://tuhrig.de/docker-registry-rest-api/)


### API
* [Docker from a distance - the remote API](http://blog.trifork.com/2013/12/24/docker-from-a-distance-the-remote-api/) 
* [KVM and Docker LXC Benchmarking with OpenStack](http://bodenr.blogspot.com/2014/05/kvm-and-docker-lxc-benchmarking-with.html)

### Performance
* [PostgreSQL Performance on Docker](http://www.davidmkerr.com/2014/06/postgresql-performance-on-docker.html)
* [Performance Analysis of Docker on Red Hat Enterprise Linux 7](http://developerblog.redhat.com/2014/08/19/performance-analysis-docker-red-hat-enterprise-linux-7/)
* [Preview of Docker Benchmarking at Flux7](http://blog.flux7.com/blogs/docker/preview-of-docker-benchmarking-at-flux7)
* [Getting Started with Performance Analysis of Docker](http://www.breakage.org/2014/06/06/getting-started-with-performance-analysis-of-docker/)
* [Docker network performances](http://blog.loof.fr/2014/10/docker-network-performances.html)
* [Docker Containers: Smaller is not always better](http://matthewkwilliams.com/index.php/2015/04/19/docker-containers-smaller-is-not-always-better/)


### Process Management
* [Running systemd within a Docker Container](http://developerblog.redhat.com/2014/05/05/running-systemd-within-docker-container/)

## Think Deeply

* [Lets review.. Docker (again)](http://iops.io/blog/docker-hype/)
* [docker is the heroku killer](http://www.brightball.com/devops/docker-is-the-heroku-killer)
* [boycott docker](http://www.boycottdocker.org/)
* [Docker isn't so bad](http://grahamc.com/blog/docker-isnt-so-bad/)
* [Is docker ready for production?](https://t37.net/is-docker-ready-for-production-feedbacks-of-a-2-weeks-hands-on.html?)
* [After Docker:Unikernels and Immutable Infrastructure](https://medium.com/@darrenrush/after-docker-unikernels-and-immutable-infrastructure-93d5a91c849e)
* [Docker’s Killer Feature](https://www.joyent.com/blog/dockers-killer-feature)
* [Linux Containers: Parallels, LXC, OpenVZ, Docker and More](http://aucouranton.com/2014/06/13/linux-containers-parallels-lxc-openvz-docker-and-more/)
* [dockerizability is better than dockerized](https://medium.com/@behruz/dockerizability-is-better-than-dockerized-3c08b9dbd84c)
* [Ignore the Hype: 5 Docker Misconceptions Java Developers Should Consider](http://blog.takipi.com/ignore-the-hype-5-docker-misconceptions-java-developers-should-consider/)
* [Challenges With Randomness In Multi-tenant Linux Container Platforms](http://blog.pivotal.io/cloud-foundry-pivotal/features/challenges-with-randomness-in-multi-tenant-linux-container-platforms)
* [Docker in Production: A History of Failure](https://thehftguy.wordpress.com/2016/11/01/docker-in-production-an-history-of-failure/)


## Rocket
* [App Container and Docker](https://coreos.com/blog/app-container-and-docker/)
* [App Container Specification](https://github.com/appc/spec/blob/master/SPEC.md)
* [Why Docker and Coreos'split was predictable](http://danielcompton.net/2014/12/02/modular-integrated-docker-coreos)
* [Of Containers, Dockers, Rockets, and Daemons](http://3ofcoins.net/2014/12/06/of-containers-dockers-rockets-and-daemons/)
* [Why CoreOS just fired a Rocket at Docker](https://gigaom.com/2014/12/02/why-coreos-just-fired-a-rocket-at-docker/)
* [Rocket vs Docker and The Myth of the “Simple, Lightweight Enterprise Platform](http://blog.xebialabs.com/2014/12/05/rocket-vs-docker-myth-simple-lightweight-enterprise-platform/)
* [What is Rocket and How It’s Different Than Docker](http://www.centurylinklabs.com/interviews/what-is-rocket-and-how-its-different-than-docker/)


## Underlying Techniques
### LXC
* [Exploring LXC Networking](http://containerops.org/2013/11/19/lxc-networking/)
* [Linux Containers](https://wiki.archlinux.org/index.php/Linux_Containers) (from archwiki)

### Cgroups
* [cgroups](https://www.kernel.org/doc/Documentation/cgroups/cgroups.txt) (from kernel.org)
* [Managing system resources on Red Hat Enterprise Linux 6](https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/6/html-single/Resource_Management_Guide/index.html)
* [Cgroups](https://wiki.archlinux.org/index.php/cgroups) (from archwiki)


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

## Various Projects
### Compose
* [Docker Compose](http://docs.docker.com/compose/)
* [Announcing Docker Compose
](https://blog.docker.com/2015/02/announcing-docker-compose/)


### Swarm
* [Docker Containers at Scale (Our Take on Docker Swarm)](http://mesosphere.com/2015/02/26/deploying-with-docker-swarm/)
* [Getting Started with docker swarm](http://www.blackfinsecurity.com/getting-started-with-docker-swarm/)
* [Scaling docker with swarm](http://blog.docker.com/2015/02/scaling-docker-with-swarm/)
* [Intro to Docker Swarm: Part 1 - Overview](http://technolo-g.com/intro-to-docker-swarm-pt1-overview/) / [Part 2 - Configuration Options and Requirements](http://technolo-g.com/intro-to-docker-swarm-pt2-config-options-requirements/) / [Part 3 - Example Swarm SOA](http://technolo-g.com/intro-to-docker-swarm-pt3-example-architechture/) / [Part 4 - Demo](http://technolo-g.com/intro-to-docker-swarm-pt4-demo/)
* [Creating SSL/TLS Certificates for Docker and Docker Swarm](http://technolo-g.com/generate-ssl-for-docker-swarm/)
* [Running a Small Docker Swarm Cluster](http://blog.scottlowe.org/2015/03/06/running-own-docker-swarm-cluster/)
* [Running a Distributed Docker Swarm on AWS](https://www.linkedin.com/pulse/running-distributed-docker-swarm-aws-jay-johnson-6113375835559841792)  (Mar 9, 2016)
* [Toward a Production-Ready Docker Swarm Cluster with Consul](https://medium.com/on-docker/toward-a-production-ready-docker-swarm-cluster-with-consul-9ecd36533bb8#.sltccot40) (Mar 2, 2016)

### Mesosphere
* [Launching a Docker Container on Mesosphere](https://mesosphere.com/docs/tutorials/launch-docker-container-on-mesosphere/) 
* [Managing Docker Clusters Using Mesos and Marathon](http://beingasysadmin.wordpress.com/2014/06/27/managing-docker-clusters-using-mesos-and-marathon/)
* [Docker on Mesos](https://mesosphere.com/2013/09/26/docker-on-mesos/)
* [Running Docker Containers on Marathon](https://mesosphere.github.io/marathon/docs/native-docker.html)
* [Mesos + Docker Tutorial: How to Build Your Own Framework](http://codefutures.com/mesos-docker-tutorial-how-to-build-your-own-framework/)
* [Continuous Delivery with Docker on Mesos in less than a minute – Part 1](http://container-solutions.com/2015/03/continuous-delivery-with-docker-on-mesos-in-less-than-a-minute/) / [part2](http://container-solutions.com/2015/03/continuous-delivery-with-docker-on-mesos-in-less-than-a-minute-part-2/)
* [ArangoDB on Apache Mesos using Marathon and Docker](https://github.com/arangodb/Cookbook/blob/master/recipes/UsingArangoDBMesosphere.md)
* [TOWARDS DOCKER IN PRODUCTION WITH APACHE MESOS](http://www.ivoverberk.nl/towards-docker-in-production-with-apache-mesos/)

### Kubernetes
* [Deploying Kubernetes on CoreOS with Fleet and Flannel](https://github.com/kelseyhightower/kubernetes-fleet-tutorial)
* [Running Kubernetes Example on CoreOS, Part 1](https://coreos.com/blog/running-kubernetes-example-on-CoreOS-part-1/)
* [How To Install and Configure Kubernetes on top of a CoreOS Cluster](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-kubernetes-on-top-of-a-coreos-cluster)
* [Corekube: Running Kubernetes on CoreOS via OpenStack](https://developer.rackspace.com/blog/running-coreos-and-kubernetes/)
* [Play With Kubernetes Quickly Using Docker](https://zwischenzugs.wordpress.com/2015/04/06/play-with-kubernetes-quickly-using-docker/)

### Openstack
* [docker](https://wiki.openstack.org/wiki/Docker)
* [What is the future of the private cloud world, Mesos or OpenStack?](http://www.quora.com/What-is-the-future-of-the-private-cloud-world-Mesos-or-OpenStack?from=timeline&isappinstalled=0)

### Azure
* [Docker and Microsoft: Integrating Docker with Windows Server and Microsoft Azure](http://weblogs.asp.net/scottgu/docker-and-microsoft-integrating-docker-with-windows-server-and-microsoft-azure)

### Other Projects
* [Chef, Puppet, Heat, Juju, Docker, etc](https://docwhat.org/chef-puppet-heat-juju-docker-etc/)
* [Powerstrip: prototype Docker extensions today](https://clusterhq.com/blog/powerstrip-prototype-docker-extensions-today/?)
* [Docker extensions: the new Docker plugins model](https://clusterhq.com/blog/docker-extensions/)
* [Docker Without Containers: Introducing Pullcontainer --docker and CVFS](http://blog.terminal.com/docker-without-containers-pulldocker/)
* [Process Management with CFEngine](https://docs.docker.com/articles/cfengine_process_management/) (CFEngine)
* [Introducing flannel: An etcd backed overlay network for containers](https://coreos.com/blog/introducing-rudder/) (flannel)
* [Tiny docker operating system](https://blog.docker.com/2015/03/tiny-docker-operating-systems/) (Boot2Docker,RancherOS)
* [Deploying Docker applications on YARN via Slider](http://www.slideshare.net/hortonworks/docker-on-slider-45493303) (slide)(YARN)

## Usage

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

### Service Discovery With Docker
* [Service Discovery Overview](http://www.simplicityitself.com/learning/getting-started-microservices/service-discovery-overview/)
* [Consul Service Discovery with Docker](http://www.davidmkerr.com/2014/08/dockerfile-golf-or-optimizing-docker.html)
* [Understanding Modern Service Discovery with Docker](http://progrium.com/blog/2014/07/29/understanding-modern-service-discovery-with-docker/)
* [Automatic Docker Service Announcement with Registrator](http://progrium.com/blog/2014/09/10/automatic-docker-service-announcement-with-registrator/)
* [Docker Service Discovery Using Etcd and Haproxy](http://jasonwilder.com/blog/2014/07/15/docker-service-discovery/)
* [Simulating service discovery in a development context with Docker and etcd](http://talwai.github.io/#/blog/post/discovery)

### Development And Deployment And Test
* [Docker: Git for deployment](http://blog.scoutapp.com/articles/2013/08/28/docker-git-for-deployment)
* [Eight Docker Development Patterns](http://www.hokstad.com/docker/patterns)
* [Deploy Java Apps With Docker = Awesome](http://blogs.atlassian.com/2013/06/deploy-java-apps-with-docker-awesome/)
* [Docker for Java Developers: How to sandbox your app in a clean environment](http://zeroturnaround.com/rebellabs/docker-for-java-developers-how-to-sandbox-your-app-in-a-clean-environment/)
* [Using Docker with Github and Jenkins for repeatable deployments](http://blog.buddycloud.com/post/80771409167/using-docker-with-github-and-jenkins-for)
* [Creating an ASP.NET vNext Docker Container using Mono](https://msopentech.com/blog/2014/11/07/creating-asp-net-vnext-docker-container-using-mono-2/)
* [Move fast and don’t break things! Testing with Jenkins, Ansible and Docker](http://blog.mist.io/post/82383668190/move-fast-and-dont-break-things-testing-with)
* [Docker and Phoenix: How to Make Your Continuous Integration More Awesome](http://ariya.ofilabs.com/2014/12/docker-and-phoenix-how-to-make-your-continuous-integration-more-awesome.html)
* [Docker in Action - Fitter, Happier, More Productive](https://realpython.com/blog/python/docker-in-action-fitter-happier-more-productive/)
* [Docker in Action - Development to Delivery ](https://blog.rainforestqa.com/2014-11-19-docker-in-action-from-deployment-to-delivery-part-1-local-docker-setup/) / [part2](https://blog.rainforestqa.com/2014-12-08-docker-in-action-from-deployment-to-delivery-part-2-continuous-integration) / [part3](https://blog.rainforestqa.com/2015-01-15-docker-in-action-from-deployment-to-delivery-part-3-continuous-delivery)
* [ASP.NET 5 development on OS X with Docker](http://open.bekk.no/aspnet5-development-on-osx-with-docker)
* [The decline of Java application servers when using docker containers](https://medium.com/@jstrachan/the-decline-of-java-application-servers-when-using-docker-containers-edbe032e1f30)

### Production
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

### Other Platforms
* [Docker on Raspberry Pi](https://resin.io/blog/docker-on-raspberry-pi/)
* [The IoT Singularity: Docker for Internet of Things Devices](http://blogs.intel.com/evangelists/2015/01/28/iot-singularity-docker-internet-things-devices/)
* [Heavily ARMed after major upgrade: Raspberry Pi with Docker 1.5.0](http://blog.hypriot.com/heavily-armed-after-major-upgrade-raspberry-pi-with-docker-1-dot-5-0)
* [Getting Docker to run on Power8](https://blog.jtlebi.fr/2014/10/28/getting-docker-to-run-on-power8/)
* [Swarming Raspberry Pi – Part 1](http://matthewkwilliams.com/index.php/2015/03/21/swarming-raspberry-pi-part-1/)

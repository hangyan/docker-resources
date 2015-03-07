# docker-resources
A collection of docker online resources.

# 目录
* [Main Resources](#main-resources)
  * [Books](#books)
  * [Websites](#websites)
  * [Documents](#documents)
  * [Archives](#archives)
  * [Personal Blogs](#personal-blogs)
* [Related Projects](#related-projects)
  * [OS](#os)
  * [Competitors](#competitors)
  * [Management Tools](#management-tools)
  * [Paas Platforms](#paas-platfroms)
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
  * [Images And Dockerfiles](#images-and-dockerfiles)
  * [Containers](#containers)
  * [Extensions](#extensions)
* [Blog Posts](#blog-posts)
  * [Introduction](#introduction)
  * [Docker](#docker)
    * [Images](#images)
    * [Storage](#storage)
    * [Dockerfiles](#dockerfiles)
    * [Containers](#containers)
    * [Security](#security)
    * [Resource Management](#resource-management)
    * [Networking](#networking)
    * [Monitoring](#monitoring)
    * [Private Registry](#private-registry)
    * [API](#api)
    * [Performance](#performance)
  * [Think Deeply](#think-deeply)
  * [Underlying Techniques](#underlying-techniques)
    * [LXC](#lxc)
    * [cgroups](#cgroups)
  * [Related Projects](#related-projects)
    * [compose](#compose)
    * [swarm](#swarm)
    * [mesosphere](#mesosphere)
    * [kubernetes](#kubernetes)
    * [openstack](#openstack)
    * [Azure](#azure)
  * [Usage](#usage)
    * [Apps](#apps)
    * [GUI](#gui)
    * [Service Discovery](#service-discovery)
    * [Development And Deployment And Test](#development-and-deployment-and-test)
    * [Production](#production)
    * [Other Platfroms](#other-platfroms)

# Main Resources
## Books
* [THE Docker Book](http://www.dockerbook.com/)

## Websites

* [Official Documents](https://docs.docker.com/) 
* [Docker Source Code](https://github.com/docker/docker)
* [Official Blogs](http://blog.docker.com/)
* [Dockerhub](https://docs.docker.com/docker-hub/)
* [Century Links Labs](http://www.centurylinklabs.com/category/docker/)
* [Coreos Official Documents](https://coreos.com/docs/)
* [Coreos Official Blogs](https://coreos.com/blog/)


## Documents
* [Docker Cheat Sheet](https://github.com/wsargent/docker-cheat-sheet#volumes)

## Archives
* [awesome-docker](https://github.com/veggiemonk/awesome-docker) 
* [Docker Weekly Archives](http://blog.docker.com/docker-weekly-archives/)
* [Valuable Docker Links](http://www.nkode.io/2014/08/24/valuable-docker-links.html)
* [Docker Ecosystem](https://www.mindmeister.com/389671722/docker-ecosystem)
* [Digital Ocean Community](https://www.digitalocean.com/community/search?primary_filter=tutorials&query=docker)


## Personal Blogs
* [jpetazzo](http://jpetazzo.github.io/)
* [Jeff Lindsay](http://progrium.com/blog/)
* [Jason Wilder](http://jasonwilder.com/)
* [Michael Crosby](http://crosbymichael.com/)


# Related Projects
## OS
* [coreos](https://coreos.com/) (Linux for Massive Server Deployments)
* [RHEL Atomic Host](http://www.redhat.com/en/files/resources/en-rhel-atomic-host-datasheet-INC0223751.pdf) (A platform optimized for Linux containers) 
* [rancheio](http://rancher.com/) (Simple, elegant tools for managing Docker in production)
* [snappy](http://developer.ubuntu.com/en/snappy/) (A new, transactionally updated Ubuntu for clouds and devices)

## Competitors
* [rocket](https://github.com/coreos/rocket)  (App Container runtime)

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


## Paas Platfroms
* [flynn](https://github.com/flynn/flynn) (A next generation open source platform as a service)
* [deis](http://deis.io/) (Your PaaS. Your Rules)
* [peas](https://github.com/tombh/peas) (Docker and Ruby based PaaS)
* [dawn](https://github.com/dawn/dawn) (Docker-based PaaS in Ruby)
* [octohost](https://github.com/octohost/octohost)(Simple web focused Dockerfile based PaaS server)
* [dokku](https://github.com/progrium/dokku) (Docker powered mini-Heroku in around 100 lines of Bash)
* [cloudfoundry](https://github.com/cloudfoundry) 

## Integration Projects
* [openstack-docker](https://github.com/docker/openstack-docker) (Nova driver and Glance backend to use Docker inside OpenStack)
* [Jenkins Cloud Plugin for Docker](https://github.com/jenkinsci/docker-plugin/)

## Monitoring
* [seagull](https://github.com/tobegit3hub/seagull) (Friendly Web UI to monitor docker daemon)
* [dockerana](https://github.com/dockerana/dockerana) (Docker Monitoring with support for Grafana and Graphite)
* [docker-mon](https://github.com/icecrime/docker-mon)(Console-based Docker monitoring)
* [cadvisor](https://github.com/google/cadvisor) (Analyzes resource usage and performance characteristics of running containers)


## Networking
* [weave](https://github.com/zettio/weave) (The Docker Network)
* [wormhole](https://github.com/vishvananda/wormhole) (A smart proxy to connect docker containers.)
* [flannel](https://github.com/coreos/flannel) (flannel is an etcd backed network fabric for containers)

## Continuous Integration
* [drone](https://github.com/drone/drone) (A Continuous Integration platform built on Docker)


## Development And Deployment
* [tug](https://github.com/nitrous-io/tug) (Docker development workflow)
* [vagga](https://github.com/tailhook/vagga)(Vagga is a tool to create development environments)
* [longshoreman](https://github.com/longshoreman/longshoreman) (Automated deployment with Docker)
* [centurion](https://github.com/newrelic/centurion) (A mass deployment tool for Docker fleets)
* 


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

## Private Registry
* [docket](https://github.com/netvarun/docket) (Custom docker registry that allows for lightning fast deploys through bittorrent)
* [docker-registry](https://github.com/docker/docker-registry) (Registry server for Docker (hosting/delivering of repositories and images))
* [wharf](https://github.com/dockercn/wharf)(ContainerOps Open Source Platform)


## UI Tools
* [dockerboard](https://github.com/dockerboard/dockerboard)  (Simple dashboards, visualizations, managements for your dockers)
* [Kitematic](https://kitematic.com/) (for MAC OSX)
* [dockerui](https://github.com/crosbymichael/dockerui) (A web interface for docker)
* [docker-registry-web](https://github.com/atc-/docker-registry-web) (A web UI for easy private/local Docker Registry integration)
* [panamax-ui](https://github.com/CenturyLinkLabs/panamax-ui) (The Web GUI for Panamax)
* 

## Storage
* [pfs](http://pachyderm-io.github.io/pfs/#whats-new-in-v02) (A git-like distributed file system for a dockerized world)
* [docker-volumes](https://github.com/cpuguy83/docker-volumes) (Docker Volume Manager)


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


## Containers
* [dockize](https://github.com/jwilder/dockerize) (Utility to simplify running applications in docker containers)
* [Supervisor](http://supervisord.org/) (A Process Control System)
* [CFEngine](http://cfengine.com/) 
* [docker-gen](https://github.com/jwilder/docker-gen) (Generate files from docker container meta-data)


## Extensions
* [powerstrip](https://github.com/clusterhq/powerstrip) (A tool for prototyping Docker extensions)




# Blog Posts
## Introduction
* [How to Use Docker on OS X: The Missing Guide](http://viget.com/extend/how-to-use-docker-on-os-x-the-missing-guide)
* [24 random docker tips](http://csaba.palfi.me/random-docker-tips/)
* [A Simple Way to Dockerize Applications](http://jasonwilder.com/blog/2014/10/13/a-simple-way-to-dockerize-applications/)

## Docker
### Images
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


### Storage
* [Comprehensive Overview of Storage Scalability in Docker](http://developerblog.redhat.com/2014/09/30/overview-storage-scalability-docker/?utm_content=buffer8a955&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer)
* [Resizing Docker containers with the Device Mapper plugin](http://jpetazzo.github.io/2014/01/29/docker-device-mapper-resize/)
* [Where are Docker images stored?](http://blog.thoward37.me/articles/where-are-docker-images-stored/)
* [Understanding Volumes in Docker](http://container-solutions.com/2014/12/understanding-volumes-docker/)

### Dockerfiles
* [6 Dockerfile Tips from the Official Images](http://container-solutions.com/2014/11/6-dockerfile-tips-official-images/)
* [Writing Dockerfile](http://www.techbar.me/writing-dockerfile/)
* [How to Optimize Your Dockerfile](http://blog.tutum.co/2014/10/22/how-to-optimize-your-dockerfile/)
* [Dockerfile Golf (or optimizing the Docker build process)](http://www.davidmkerr.com/2014/08/dockerfile-golf-or-optimizing-docker.html)
* [Dockerfile Best Practices](http://crosbymichael.com/dockerfile-best-practices.html)
* 


### Containers
* [What is the difference between CMD and ENTRYPOINT in a Dockerfile?](http://stackoverflow.com/questions/21553353/what-is-the-difference-between-cmd-and-entrypoint-in-a-dockerfile)
* [Docker and the PID 1 zombie reaping problem](https://blog.phusion.nl/2015/01/20/docker-and-the-pid-1-zombie-reaping-problem/)
* [Data-only container madness](http://container42.com/2014/11/18/data-only-container-madness/)

### Security
* [Why you don't need to run sshd in your docker containers](http://blog.docker.com/2014/06/why-you-dont-need-to-run-sshd-in-docker/)
* [shocker: docker PoC VMM-container breakout](http://stealth.openwall.net/xSports/shocker.c)
* [Containers&Docker: How secure are they?](https://blog.docker.com/2013/08/containers-docker-how-secure-are-they/)
* [Docker and SELinux](http://www.projectatomic.io/docs/docker-and-selinux/)
* [Bringing new security features to Docker](https://opensource.com/business/14/9/security-for-docker)
* [Docker Secure Deployment Guidelines](https://github.com/GDSSecurity/Docker-Secure-Deployment-Guidelines)
* [Docker Container Breakout Proof-Of-Concept Exploit](http://outofmemory.cn/wr/?u=http%3A%2F%2Fblog.docker.com%2F2014%2F06%2Fdocker-container-breakout-proof-of-concept-exploit%2F)

### Resource Management
* [Resource management in Docker](https://goldmann.pl/blog/2014/09/11/resource-management-in-docker/) 

### Networking
* [Advanced networking](https://docs.docker.com/articles/networking/)
* [DNS And docker containers](http://wiredcraft.com/blog/dns-and-docker-containers/)
* [Coupling Docker and Open vSwitch](http://fbevmware.blogspot.com/2013/12/coupling-docker-and-open-vswitch.html)
* [Connecting Docker containers on multiple hosts](https://goldmann.pl/blog/2014/01/21/connecting-docker-containers-on-multiple-hosts/)


### Monitoring
* [Gathering lxc and docker containers metrics](http://blog.docker.com/2013/10/gathering-lxc-docker-containers-metrics/)
* [nsinit: per-container resource monitoring of Docker containers on RHEL/Fedora](http://www.breakage.org/2014/09/03/nsinit-per-container-resource-monitoring-of-docker-containers-on-rhelfedora/)
* [Runtime Metrics](https://docs.docker.com/articles/runmetrics/)



### Private Registry
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


## Think Deeply
* [App Container and Docker](https://coreos.com/blog/app-container-and-docker/)
* [Lets review.. Docker (again)](http://iops.io/blog/docker-hype/)
* [docker is the heroku killer](http://www.brightball.com/devops/docker-is-the-heroku-killer)


## Underlying Techniques
### LXC
* [Exploring LXC Networking](http://containerops.org/2013/11/19/lxc-networking/)
* [Linux Containers](https://wiki.archlinux.org/index.php/Linux_Containers)

### cgroups
* [cgroups](https://www.kernel.org/doc/Documentation/cgroups/cgroups.txt) 
* [Managing system resources on Red Hat Enterprise Linux 6](https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/6/html-single/Resource_Management_Guide/index.html)
* [Cgroups](https://wiki.archlinux.org/index.php/cgroups) 


## Related Projects
### compose
* [Docker Compose](http://docs.docker.com/compose/)

### swarm
* [Docker Containers at Scale (Our Take on Docker Swarm)](http://mesosphere.com/2015/02/26/deploying-with-docker-swarm/)
* [Getting Started with docker swarm](http://www.blackfinsecurity.com/getting-started-with-docker-swarm/)


### mesosphere
* [Launching a Docker Container on Mesosphere](https://mesosphere.com/docs/tutorials/launch-docker-container-on-mesosphere/) 
* [Managing Docker Clusters Using Mesos and Marathon](http://beingasysadmin.wordpress.com/2014/06/27/managing-docker-clusters-using-mesos-and-marathon/)
* [Docker on Mesos](https://mesosphere.com/2013/09/26/docker-on-mesos/)
* [Running Docker Containers on Marathon](https://mesosphere.github.io/marathon/docs/native-docker.html)
* [Mesos + Docker Tutorial: How to Build Your Own Framework](http://codefutures.com/mesos-docker-tutorial-how-to-build-your-own-framework/)

### kubernetes
* [Deploying Kubernetes on CoreOS with Fleet and Flannel](https://github.com/kelseyhightower/kubernetes-fleet-tutorial)
* [Running Kubernetes Example on CoreOS, Part 1](https://coreos.com/blog/running-kubernetes-example-on-CoreOS-part-1/)
* [How To Install and Configure Kubernetes on top of a CoreOS Cluster](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-kubernetes-on-top-of-a-coreos-cluster)
* [Corekube: Running Kubernetes on CoreOS via OpenStack](https://developer.rackspace.com/blog/running-coreos-and-kubernetes/)


### openstack
* [docker](https://wiki.openstack.org/wiki/Docker)

### Azure
* [Docker and Microsoft: Integrating Docker with Windows Server and Microsoft Azure](http://weblogs.asp.net/scottgu/docker-and-microsoft-integrating-docker-with-windows-server-and-microsoft-azure)

## Usage

### Apps
* [Dockerizing a Python Web App](http://blogs.aws.amazon.com/application-management/post/Tx1ZLAHMVBEDCOC/Dockerizing-a-Python-Web-App)
* [Deploying NGINX and NGINX Plus with Docker](http://nginx.com/blog/deploying-nginx-nginx-plus-docker/)
* [Automated Nginx Reverse Proxy for Docker](http://jasonwilder.com/blog/2014/03/25/automated-nginx-reverse-proxy-for-docker/)
* [Transparent Squid in a container](https://github.com/jpetazzo/squid-in-a-can)
* [Deploying and migrating a multi-node ElasticSearch-Logstash-Kibana cluster using Docker](https://clusterhq.com/blog/deploying-multi-node-elasticsearch-logstash-kibana-cluster-using-docker/)


### GUI
* [Docker Containers on the Desktop](https://blog.jessfraz.com/posts/docker-containers-on-the-desktop.html)
* [Running GUI apps with Docker](http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/)
* [Docker desktop: Your desktop over ssh running inside of a docker container ](http://fabiorehm.com/blog/2014/09/11/running-gui-apps-with-docker/)

### Service Discovery
* [Consul Service Discovery with Docker](http://www.davidmkerr.com/2014/08/dockerfile-golf-or-optimizing-docker.html)
* [Understanding Modern Service Discovery with Docker](http://progrium.com/blog/2014/07/29/understanding-modern-service-discovery-with-docker/)
* [Automatic Docker Service Announcement with Registrator](http://progrium.com/blog/2014/09/10/automatic-docker-service-announcement-with-registrator/)
* [Docker Service Discovery Using Etcd and Haproxy](http://jasonwilder.com/blog/2014/07/15/docker-service-discovery/)


### Development And Deployment And Test
* [Docker: Git for deployment](http://blog.scoutapp.com/articles/2013/08/28/docker-git-for-deployment)
* [Eight Docker Development Patterns](http://www.hokstad.com/docker/patterns)
* [Deploy Java Apps With Docker = Awesome](http://blogs.atlassian.com/2013/06/deploy-java-apps-with-docker-awesome/)
* [Using Docker with Github and Jenkins for repeatable deployments](http://blog.buddycloud.com/post/80771409167/using-docker-with-github-and-jenkins-for)
* [Creating an ASP.NET vNext Docker Container using Mono](https://msopentech.com/blog/2014/11/07/creating-asp-net-vnext-docker-container-using-mono-2/)
* [Move fast and don’t break things! Testing with Jenkins, Ansible and Docker](http://blog.mist.io/post/82383668190/move-fast-and-dont-break-things-testing-with)
* [Docker and Phoenix: How to Make Your Continuous Integration More Awesome](http://ariya.ofilabs.com/2014/12/docker-and-phoenix-how-to-make-your-continuous-integration-more-awesome.html)


### Production
* [Docker at Lyst](http://developers.lyst.com/devops/2014/12/08/docker/)
* [Docker at Shopify: How we built containers that power over 100,000 online shops](http://www.shopify.com/technology/15934308-docker-at-shopify-how-we-built-containers-that-power-over-100-000-online-shops)
* [Intro to Docker ...and how we use it at writeLaTex](http://jdlm.info/ds-docker-demo/)
* [How We Use Docker For Continuous Delivery – Part 1](http://contino.co.uk/use-docker-continuously-deliver-microservices-part-1/)



### Other Platfroms
* [Docker on Raspberry Pi](https://resin.io/blog/docker-on-raspberry-pi/)


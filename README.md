# awesome-rancher

A curated list of awesome Rancher resources.

If you see a link that isn't a good fit, you can fix it by submitting a pull request to help improve the list. Likewise, if you'd like to add or fix something, click the [README.md](README.md) file to edit and submit a pull request.  Thank you!

## What is Rancher?

> Rancher is an open source software platform that enables organizations to run containers in production. With Rancher, organizations no longer have to build a container services platform from scratch using a distinct set of open source technologies. Rancher supplies the entire software stack needed to manage containers in production.

# Menu

* [Getting started](#getting-started)
* [Resources](#resources)
* [Videos](#videos)
* [Blog posts](#blog-posts)
* [Tools](#tools)
  * [Community projects](#community-projects)
    * [Terraform](#terraform)
  * [Third party](#third-party)
* [Twitter accounts to follow](#twitter-accounts-to-follow)
* [Connect with Rancher](#connect-with-rancher)
* [Contributing](#contributing)

## Getting started

* [Rancher OS docs](http://docs.rancher.com/os/)
* [Rancher docs](http://docs.rancher.com/rancher)
* [Try Rancher](https://try.rancher.com)

## Resources

* [Installing Rancher Server](https://docs.rancher.com/rancher/installing-rancher/installing-server/)
* [Upgrading Rancher Server](https://docs.rancher.com/rancher/latest/en/upgrading/)
* [Environments](https://docs.rancher.com/rancher/v1.5/en/environments/)
* [Hosts](http://docs.rancher.com/rancher/v1.5/en/hosts/)
* [Registries](https://docs.rancher.com/rancher/v1.5/en/environments/registries/)
* [Working with Cattle](http://docs.rancher.com/rancher/v1.5/en/cattle/stacks/)
* [Working with Kubernetes](http://docs.rancher.com/rancher/v1.5/en/kubernetes/)
* [Working with Mesos](http://docs.rancher.com/rancher/v1.5/en/mesos/)
* [Using the catalog](http://docs.rancher.com/rancher/latest/en/catalog/)
* [API Documentation](http://docs.rancher.com/rancher/latest/en/api/)
* [Project Plan](https://github.com/rancher/rancher/wiki/Rancher-Project-Plan)
* [Rancher monitoring with Prometheus](https://github.com/infinityworksltd/Guide_Rancher_Monitoring)

## Videos

* [March 2016 Meetup](https://www.youtube.com/watch?v=hwhxXwT6zlw) - Delivering Containers-as- a-Service with Rancher 1.0
* [April 2016 Meetup](https://www.youtube.com/watch?v=ZovLwCvb2Is) - Tips, Tricks Tools to Running Containers like a Pro
* [May 2016 Online Meetup](https://www.youtube.com/watch?v=sS3gO5h88M4) - Running Docker and Rancher Locally on Dev Machines
* [June 2016 Online Meetup](https://www.youtube.com/watch?v=P9wtpJD88Os) - Introducing Apache Mesos Environments in Rancher
* [July 2016 Online Meetup](https://www.youtube.com/watch?v=6vtY_4vNvpE) - Pipeline Automation with the New Rancher CLI
* [August 2016 Online Meetup](https://www.youtube.com/watch?v=ppY9cqTvBVE) - Managing HA Kubernetes Clusters
* [September 2016 Online Meetup](https://www.youtube.com/watch?v=GiqOO8N8Ooo) - NextGen Container Storage and Networking
* [October 2016 Online Meetup](https://www.youtube.com/watch?v=XiC6Dy38HnA) - The Great Container Monitoring Bake Off
* [December 2016 Online Meetup](https://www.youtube.com/watch?v=2AE6Z2LXq-I) - Deep Dive and Demo of Rancher 1 2
* [January 2017 Online Meetup](https://www.youtube.com/watch?v=EHeYJCPJgcU) - Getting Started with Windows Containers in Rancher
* [February 2017 Online Meetup](https://www.youtube.com/watch?v=EjvzXC8qwWg&t=4349s) - More Tips and Tricks for Running Containers Like a Pro
* [Monthly training videos](https://www.youtube.com/watch?v=FyiSQzD0Iak&list=PLfAoTEAPazb4fQQwOxY3uXsO_UBK3fEPG)

### Blog posts

* [Rancher blog](http://rancher.com/blog/)
* [DEPLOYING RANCHER HA IN PRODUCTION WITH AWS, TERRAFORM, AND RANCHEROS](https://thisendout.com/2016/12/10/update-deploying-rancher-in-production-aws-terraform-rancheros/)
* [Creating a highly available container orchestration cluster on AWS](https://www.tastycidr.net/rancher-creating-a-highly-available-container-orchestration-cluster-on-ec2/)
* [Configure a Rancher HAProxy health check](https://thepracticalsysadmin.com/configure-a-rancher-haproxy-health-check/)
* [Bootstrap servers to a Rancher environment](https://thepracticalsysadmin.com/bootstrap-servers-to-a-rancher-environment/)
* [Container Clustering with Rancher Server (Part 5) – Automating the deployment of AWS infrastructure and Rancher with Terraform](https://skeltonthatcher.com/blog/container-clustering-rancher-server-part-5-automating-deployment-aws-infrastructure-rancher-terraform/)

## Tools

* [Rancher](https://github.com/rancher/rancher)
* [Rancher CLI](https://github.com/rancher/cli) - The Rancher Command Line Interface (CLI)is a unified tool to manage your Rancher server
* [Rancher Compose](https://github.com/rancher/rancher-compose) - Docker compose compatible client to deploy to Rancher
* [Rancher catalog](https://github.com/rancher/rancher-catalog) - The catalog provides templates created and maintained by Rancher
* [Rancher community catalog](https://github.com/rancher/community-catalog) - The catalog provides templates created and maintained by the community
* [Convoy](https://github.com/rancher/convoy) - A Docker volume plugin, managing persistent container volumes
* [Cattle](https://github.com/rancher/cattle) - Cattle is the orchestration engine that powers Rancher

### Community projects

* [Rancher client](https://github.com/aboutdotme/rancher-client) - A Rancher API client for containerized deployments and management
* [Rancher reaper](https://github.com/ampedandwired/rancher-reaper) - A Service to automatically delete hosts from Rancher if they have been terminated in AWS
* [Rancher alarms](https://github.com/ndelitski/rancher-alarms) - Send notifications when something goes wrong in rancher
* [Rancher cron](https://github.com/SocialEngine/rancher-cron) - A service that can start containers on a defined schedule
* [Rancher wrangler](https://github.com/bscott/rancher-wrangler) - Wrangler is a Web Interface to see detailed Information about Rancher Servers
* [ChaosRancher](https://github.com/bscott/chaosrancher) - ChaosRancher periodically kills random services in your Rancher Stack/Cluster.
* [Giddyup](https://github.com/cloudnautique/giddyup) - Giddyup is a tool to that helps get services started in a Rancher compose stack
* [Cowpoke](https://github.com/LeanKit-Labs/cowpoke) - A service to handle configurable Rancher service upgrade patterns
* [Gaucho](https://github.com/etlweather/gaucho) - A Python CLI tool for Rancher's API
* [Rancher Let's Encrypt](https://github.com/janeczku/rancher-letsencrypt) - Rancher service that obtains and manages free SSL certificates from the Let's Encrypt CA
* [Rancher Vagrant](https://github.com/nextrevision/rancher-vagrant) - Extensible and automated local Rancher environments using Vagrant
* [Rancher Status Page](https://github.com/Demandbase/rancher-status-page) - Simple status page for Rancher stacks and services

#### Terraform

* [Terraform Rancher HA](https://github.com/nextrevision/terraform-rancher-ha-example) - Terraform files for deploying a Rancher HA cluster in AWS
* [Terraform AWS Rancher HA](https://github.com/chrisurwin/terraform-aws-rancher-ha) - Terraform module for standing up an AWS Rancher HA instance
* [Terraform Rancher](https://github.com/cloudnautique/terraform-rancher) - Templates for building and configuring Rancher management and compute stacks
* [Terraform Rancher DigitalOcean](https://github.com/lunagt/rancher-terraform-digitalocean) - Terraform module for a Rancher server on Digitalocean.
* [Rancher server single node HA and multi-AZ Rancher hosts in AWS](https://github.com/SkeltonThatcher/aws-terraform-rancher-single-node-ha) - Terraform scripts to deploy Rancher server single node HA and multi-AZ Rancher hosts in AWS

#### Third party

* [SpotInst](https://spotinst.com) - Manage AWS and GCE Spot Instances Groups with Rancher Integration for automatic removal of infrastructure

## Twitter accounts to follow

* [@CloudNautique](https://twitter.com/CloudNautique)
* [@ibuildthecloud](https://twitter.com/ibuildthecloud)
* [@vincentfiduccia](https://twitter.com/vincentfiduccia)
* [@smw355](https://twitter.com/smw355)
* [@deniseschannon](https://twitter.com/deniseschannon)
* [@Lemonjet](https://twitter.com/Lemonjet)
* [@GuerillaNerd](https://twitter.com/GuerillaNerd)
* [@leodotcloud](https://twitter.com/leodotcloud)
* [@shengliang](https://twitter.com/shengliang)
* [@utter_babbage](https://twitter.com/utter_babbage)
* [@joshwget](https://twitter.com/joshwget)
* [@SvenDowideit](https://twitter.com/SvenDowideit)
* [@davegetzler](https://twitter.com/davegetzler)

## Connect with Rancher

* [Events](http://rancher.com/events/)
* [Rancher forums](https://forums.rancher.com/)
* [Twitter](https://twitter.com/Rancher_Labs)
* [Slack](https://slack.rancher.io/)
* [IRC](http://webchat.freenode.net/?channels=rancher)
* [Youtube](https://www.youtube.com/channel/UCh5Xtp82q8wjijP8npkVTBA)
* [Online training](https://attendee.gotowebinar.com/rt/2905734731496917249)

## Contributing

* [Contributing](http://docs.rancher.com/rancher/contributing/)
* [Cowpoke](https://github.com/rancher/rancher/wiki/Cowpoke-1:-Getting-Started-with-Rancher) - Get started developing
* [Rancher documentation repo](https://github.com/rancher/rancher.github.io)

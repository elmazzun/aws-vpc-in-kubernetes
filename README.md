# AWS VPC in Kubernetes

This repository is an attempt to create the equivalent of an AWS VPC through the 
resources of a Kubernetes cluster and, where this does not reach, add other 
resources and management logic through Service Mesh and other frameworks.

Much of this project will initially be done in this document, where I will try 
to map AWS resources into the equivalent Kubernetes resources.

**I am not going to map every AWS resource to Kubernetes**: AWS services such 
as CloudWatch, Lambda and others are outside the scope of this exercise; all 
mapped resources are tracked in [Content](#content) section.

# Why?

I was studying for an AWS certification and wondered if there were any easily 
usable online labs; after a search that lasted a good five minutes, I gave up 
and thought I would create something of my own.

In this way I will do an in-depth study of both AWS and Kubernetes, where 
in-depth knowledge of both will be necessary in order to create a consistent 
resource mapping between the two.

I created this repository instead of writing an article on some blog because I 
was thinking of implementing what is described here with a minimum of code; 
instead of being a purely mental exercise, it would be intriguing if this 
became a local lab where anybody could experiment with AWS features in a free 
and safe way...we'll see how much I want to devote to this project.

# Content

* [Why?](#why)
* [Resource mapping between AWS and Kubernetes](#resource-mapping-between-aws-and-kubernetes)
  * [VPC](#vpc)
  * [Availability Zone](#availability-zone)
  * [Internet Gateway](#internet-gateway)
  * [Subnet](#subnet)
  * [NAT Gateway](#nat-gateway)
  * [Route Table](#route-table)
  * [Elastic Load Balancer (ELB)](#elastic-load-balancer-elb)
  * [Identity Access and Management](#identity-access-and-management)
* [Creation and Visualization](#creation-and-visualization)
* [Disclaimer](#disclaimer)
* [Contributions](#contributions)

# Resource mapping between AWS and Kubernetes

## VPC

The equivalent would be a **Kubernetes Cluster**, which should offer the same 
degree of resource isolation as a PVC.

## Availability Zone

## Internet Gateway

The equivalent would be an **Ingress Controller**, which should be able to 
handle ingress/egress traffic.

## Subnet

## NAT Gateway

## Route Table

## Elastic Load Balancer (ELB)

## Identity Access and Management

# Disclaimer

This project is purely for educational purposes and is designed on a non-profit 
basis.

# Contributions

Any contribution will be welcome ❤️.

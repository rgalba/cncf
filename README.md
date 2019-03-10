# Cloud native computing foundation

- Overview
- Motivation
- Background
- Projects
- Landscape
- Demonstration

## Overview

Cloud native is a term used to describe container-based environments.

Cloud-native technologies are used to develop applications built with services packaged in containers, deployed as microservices and managed on elastic infrastructure through agile DevOps processes and continuous delivery workflows.

## CNCF Motivation

>Sustaining and Integrating Open Source Technologies
>`The Cloud Native Computing Foundation` builds sustainable ecosystems and fosters a community around a constellation of high-quality projects that orchestrate containers as part of a microservices architecture.

>CNCF serves as the vendor-neutral home for many of the fastest-growing projects on GitHub, including Kubernetes, Prometheus and Envoy, fostering collaboration between the industry’s top developers, end users, and vendors.

## What is CNCF?

> CNCF is an open source software foundation dedicated to making cloud native computing universal and sustainable.

Cloud native computing uses an open source software stack to deploy applications as microservices, packaging each part into its own container, and dynamically orchestrating those containers to optimize resource utilization.

Cloud native technologies enable software developers to build great products faster.

## Projects

Maturity Levels

![maturity level](https://www.cncf.io/wp-content/uploads/2018/12/graphic-chasm-3-02.svg)

CNCF projects have a maturity level of (compared to the Chasm diagram):

- `sandbox`: the Innovators
- `incubating`: Early Adopters
- `graduated`: Early Majority


The maturity level is a signal by CNCF as to what sorts of enterprises should be adopting different projects.

Projects increase their maturity by demonstrating their sustainability to CNCF’s Technical Oversight Committee: that they have adoption, a healthy rate of changes, committers from multiple organizations, have adopted the CNCF Code of Conduct, and have achieved and maintained the Core Infrastructure Initiative Best Practices Badge.

## Landscape

[Interactive landspace:](https://landscape.cncf.io)

#### Cloud native trail map

![trail map](https://raw.githubusercontent.com/cncf/trailmap/master/CNCF_TrailMap_latest.png)

#### CNCF Serverless Landscape


![serverless landscape](https://landscape.cncf.io/images/serverless.png)

### Stack

Kubernetes (orchestration)
Prometheus (monitoring)
Envoy (service proxy)
Core DNS (service discovery)
CNI (networking API)
Helm (package management)
Rook (storage containerized)

## Demonstration

Use helm in a minikube cluster.
Install redis and the guestbook app.
Try to use Prometheus together?
It would be possible to use hyperledger?



references
- https://www.cncf.io/
- https://landscape.cncf.io
- https://en.wikipedia.org/wiki/Linux_Foundation#Cloud_Native_Computing_Foundation



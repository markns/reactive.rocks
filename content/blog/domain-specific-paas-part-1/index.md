---
title: How to build a Domain Specific PaaS with Kubernetes - Part 1
date: "2020-03-01T22:12:03.284Z"
description: "How to build a Domain Specific PaaS with Kubernetes"
---

Way back in early 2017, Brendan Burns, one of the co-founders of Kubernetes, published a blog article describing how Kubernetes will form [the foundation for next generation PaaS](https://kubernetes.io/blog/2017/02/caas-the-foundation-for-next-gen-paas/). 

His idea was this: Kubernetes has simplified the development of a PaaS to such an extent that a whole new class of industry specific and even niche platforms has become viable. Whereas previously it would take a team of highly skilled distributed systems engineers to build a PaaS, now an individual developer with expertise in a specific domain can develop a bespoke platform heavily customized for their industry vertical.

Finance 
IoT https://blog.bosch-si.com/bosch-iot-suite/why-the-iot-needs-kubernetes/
Bioinformatics https://codeocean.com/

I have spent most of the last five years working on systems such as these, culminating in the development of a PaaS 

Catering to business users who have a little Python ... 

since most of the services that were traditionally provided by PaaS platforms were now fulfilled by container orchestration platforms such as Kubernetes, it has become "easy" to build a custom PaaS. Instead of requiring a large team of experts in distributed systems engineering, building a platform broad enough ,       

https://www.thoughtworks.com/radar/platforms/domain-specific-paas



If you're reading this article, I'm assuming that you are reasonably familiar with Kubernetes.... operator control loop. 

Brendan burns comment - 
Why is this an interesting idea?
Gridarrow idea - background in HFT, links to Reddit posts. Why did the company not succeed? 
Company acquired

Other ideas for domain specific paas:
- finance integration
- science integration
- internet of things

Include a codebase
Many different choices in building a system like this. We'll discuss the alternatives.

Kubernetes operators
Custom Resource Definitions (earlier experiments with Gitea)
Coding environment
Security & resource management
Docker build inside the cluster
Code generation
User identity & access management (auth0 -> keycloak)
Networking (GCP Endpoints, k8s native, Istio)
GCP (vs on prem self hosted)
Monitoring
Onboarding
Helm deployment

Marketing
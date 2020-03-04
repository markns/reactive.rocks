---
title: How to build a Domain Specific PaaS with Kubernetes - Part 1
date: "2020-03-01T22:12:03.284Z"
description: "How to build a Domain Specific PaaS with Kubernetes"
---

Way back in early 2017, Brendan Burns, one of the co-creators of Kubernetes, published a blog article describing how Kubernetes will form the [foundation for the next generation of PaaS](https://kubernetes.io/blog/2017/02/caas-the-foundation-for-next-gen-paas/). 

His idea was this: Kubernetes has simplified the development of a PaaS to such an extent that a whole new class of industry specific and even niche platforms have become viable. Whereas previously it would have taken a team of highly skilled distributed systems engineers to build a PaaS, now it's possible for an individual developer with expertise in a specific domain to develop a bespoke platform, tailor-made for their industry vertical.

> Indeed, specialized platforms are now available in many high-tech sectors. The engineering/IoT community have a plethora of options, from independent services such as [Ubidots](https://ubidots.com/), as well as the big cloud providers. In science and research, [Code Ocean](https://codeocean.com/) have a PaaS that enables collaboration and reproducibility of results. In financial services, Finastra's [FusionFabric.cloud](https://www.fusionfabric.cloud/) platform gives developers access to a wide range of open APIs and a marketplace upon which to monetize their apps.

I have spent most of the last five years working on systems such as these in the finance sector, culminating in the development of a PaaS that uses Python to [send real time data to Microsoft Excel](https://www.youtube.com/watch?v=is_2RVOOEME). Extremely niche admittedly, but don't underestimate the continued dominance of Excel in the financial world. To get some traders I've worked with to stop using it, you'd have to prise it from their cold, dead hands. But that's another story entirely.

I'm going to show you how to build an MVP version of these PaaS

Let's say you work for a company that has some analysts who know a little Python, . They want to mash-up (hands up if you remember [those days](https://mashable.com/2009/10/08/top-mashups/?europe=true)! 🙋‍♂️) data from various internal sources, and provide it to business users to be consumed in clients such as Tableau or QlikView (or sure, even Excel).   

-----------------

Flask function 

db


response json
tableau, Qlik etc as clients



Catering to business users who have a little Python ... 


https://www.thoughtworks.com/radar/platforms/domain-specific-paas



If you're reading this article, I'm assuming that you are reasonably familiar with Kubernetes.... operator control loop. 

Brendan burns comment - 
Why is this an interesting idea?
Gridarrow idea - background in HFT, links to Reddit posts. Why did the company not succeed? 
Company acquired

Include a codebase
Many different choices in building a system like this. We'll discuss the alternatives.

Kubernetes operators
Custom Resource Definitions (earlier experiments with Gitea)
Coding environment
Security & resource management
Docker build inside the cluster. Kaniko. https://github.com/tektoncd/pipeline?
Code generation
User identity & access management (auth0 -> keycloak)
Networking (GCP Endpoints, k8s native, Istio)
GCP (vs on prem self hosted)
Monitoring
Onboarding
Helm deployment

Marketing
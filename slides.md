---
title-prefix: Six Feet Up
pagetitle: Mastering the Zen of Dev Experience
author: Calvin Hendryx-Parker, CTO, Six Feet Up
author-meta:
    - Calvin Hendryx-Parker
date: PyOhio 2024
date-meta: 2024
keywords:
    - Programming
    - Kubernetes
    - Python
---

# Mastering the Zen of Dev Experience {.r-fit-text data-background-image="images/Chris Linnett Unsplash.jpg"}
### Kubernetes and the Art of Simplicity
#### Calvin Hendryx-Parker, CTO
#### Six Feet Up

![](images/PyOhio%20Repo%20QR%20Code.png)

::: notes
Example Notes
:::

# The Cat

![](images/mcintosh.png)

# The Dog

![](images/mooshu.png)

# Check it out 🚀

<https://github.com/sixfeetup/scaf>

![Scaf Github Repository](images/qrcode_github.com.png)

# Ideal Developer Experience {.r-fit-text .semi-filtered data-background-image="images/Chuttersnap Unsplash.jpg"}
* Set up in a few minutes (`git clone && tilt up`)
* Enough resources (RAM, CPU, disk) to develop and run the application
* Containerized (all developers run exactly the same stack)
* Continues integration and deployment for a quick feedback loop
* Automatic preview environment for PRs
* Use the same tools to debug Dev, QA, and Production environments

# "Scratch Your Own Itch" {.r-fit-text .semi-filtered data-background-image="images/Erwan Hesry Unsplash.jpg"}
* Dev laptops can be underpowered (and couldn't run large software stacks)
* The dev environment is not set up with remote development in mind
* Docker permission issues
* Little support for developing inside containers 
* Difficulty debugging in the QA environment

# Kubernetes to the Rescue? {.r-fit-text .semi-filtered data-background-image="images/Frank McKenna Unsplash.jpg"}


# Kubernetes is Declarative {.r-fit-text .semi-filtered data-background-image="images/Jeffrey Blum Unsplash.jpg"}

* As a building plan does for construction, it requires you to describe the desired state in what is known as a manifest.
* You are the architect, and Kubernetes is the builder.
* No manual commands are required for deployment.
* It does more! Like the maintenance man on your new home, it actively maintains the state.

# Let's Peek at some YAML

# Kubernetes Standardizes Deployment {.r-fit-text .semi-filtered data-background-image="images/Kurt Cotoaga Unsplash.jpg"}

* Use the same tools to deploy to all environments
* Application developers and DevOps engineers speak a common language
* Easily switch from local to remote dev environment

# Quick Kubernetes Primer

# Nodes/Services/Deployments/Pods {.r-fit-text}
![](images/k8s-node-service-deployment.png)

# Contexts and Clusters
![](images/k8s-contexts.png)

# Namespaces Are One Honking Great Idea {.r-fit-text}
![](images/k8s-namespaces.png)

# Kubernetes vs Docker-Compose {.r-fit-text .semi-filtered data-background-image="images/Mika Baumeister Unsplash.jpg"}

# Kubernetes Developer Workflow {.r-fit-text .semi-filtered data-background-image="images/Nathan Cima from Unsplash.jpg"}

## Live Demo 🤞

# Resources {.semi-filtered data-background-image="images/Venti Views Unsplash.jpg"}

* <https://github.com/sixfeetup/scaf>
* <https://github.com/sixfeetup/2024_PyOhio_MasteringtheZenofDevExperience>

## Find Me 😍

#### <calvin@sixfeetup.com>

🐘 [`@calvinhp@fosstodon.org`](https://fosstodon.org/@calvinhp)  
🐦 [`@calvinhp`](https://twitter.com/calvinhp)
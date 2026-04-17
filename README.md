  ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Kubernetes](https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) ![GCP](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white) ![Ansible](https://img.shields.io/badge/ansible-%231A1918.svg?style=for-the-badge&logo=ansible&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)


# Road Map DevOps Engineer 

## Motivation:

The motivation for this repository is create a generic Road Map for anyone aspiring to be a DevOps Engineer. While, I don't aim this repository to be exhaustive and one-stop shop for all things DevOps, I would like to see this as more of a navigator for people aspiring to become DevOps Engineers. 

  > ⚠️ Don't be overwhelmed by the no of topics. If you're a beginner pay attention to Essentials and then learn advanced topics.



<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [Road Map DevOps Engineer](#road-map-devops-engineer)
  - [Motivation:](#motivation)
  - [What is DevOps?](#what-is-devops)
  - [What does a DevOps Engineer Do?](#what-does-a-devops-engineer-do)
  - [The basics:](#the-basics)
  - [Linux](#linuxlinuxmd)
  - [Software Development Lifecycle (SDLC)](#software-development-lifecycle-sdlc)
  - [Version Control and Source Code Management ~Essential~](#version-control-and-source-code-management-essential)
  - [Networking](#networkingnetworkingmd)
  - [Cloud Computing](#cloud-computingcloudcomputingmd)
  - [Containers & Kubernetes](#containers--kubernetes)
  - [Continuous Integration & Continuous Deployment [CI-CD]](#continuous-integration--continuous-deployment-ci-cd)
  - [Continuous Testing](#continuous-testing)
  - [Security Scanning](#security-scanning)
  - [Observability](#observability)
  - [Resources & References](#resources--references)

<!-- /code_chunk_output -->

## What is DevOps?

DevOps is a set of practices, processes and tools that aims to remove the silos between development and operations for faster and quality software delivery. The idea is to apply Software development principles to the IT Operations as well. Theoretically, Devops is a culture that the entire software engineering team adopts, however, in practice DevOps is seen as a job role that is responsible to handle non-development part of the Software Development lifecycle. These responsibilities include Infrastructure deployments, CI-CD, backup and restores, automating administrative and repititve tasks, monitoring and alerting. 

Read also Site Reliability Engineering

## What does a DevOps Engineer Do?

The roles and responsibilities of a DevOps Engineer are quite diverse and vary from organization to organization. In large organizations the responsibilities vary even from one business unit to the other. As said earlier, a DevOps engineer typically handles all non development related work. 

To put it bluntly a DevOps Engineer has to manage computers and install software that runs the software developed by the software engineering teams. This includes: 

- Infrastructure Management:
   Provisioning, Maintainance (upgrades and patching) and decommissioning and preferably doing it through Infrastructure As Code (IAC)

- Containerization:
    Containerizing applications (creating Dockerfiles and optimizing) and deploying to a Container orchestration platform such as Kubernetes/Dockerswarm or contianer instance service. 

- CI-CD:
    Designing, building and maintaining continuous Integration and continuous delivery workflows and also any automation using the orchestration tools such as Jenkins, GitHub Actions, Gitlab CI etc.

- Toil Reduction:
    Toil is any sort of repetitive activity that needs to be done. One of the responsibilities of a DevOps Engineer is to automate these tasks and reduce toil. This could include archival of old logs or maintaining backups of database or files.

- Administration:
    Backup & restore, patching, disaster recovery, compliance (ISO 27001, SOC2 certifications etc)

- Observability:
    Setting up and configuring Monitors & Alerts, being on on-call roster, Incident Management and root cause analysis.

- Security: 
    Integrating Security scanning tools such as Veracode, X-Ray to ensure there are no vulnerabilities in the code or infrastructure configuration. 


## The basics:
 
Once you read what a devops engineer does, understand that if you want to become a DevOps engineer you have to be good with computers and how to manage infrastructure and software deployments in a smart and a repeatable way. 
One way to differentiate - classic Operations/Sys Admin roles and DevOps Engineers is how much of the work you do it in a smart way - meaning automated and repeatable way with less scope for errors.
This means one should be really good with command line interface (CLI)-  particularly, Linux because most software applications and automations (CI-CD for instance) are run on Linux operating systems.

No matter, what kind of organization you work for and what their tech stak is, You will have to write code. You don't have to be a developer while it doesn't hurt to be a good programmer to become a DevOps Engineer but you don't have to be one. 
You should understnad the fundamentals of programming such as conditionals, loops, functions, variables and environment variables and exit codes etc. 
You should also know concepts around networking, storage and Operating systems. Since, you as a DevOps Engineer are going to handle code and building the code and deploying you need to understand the basics of programming languages for instance complied vs interpreted, package managers and dependency management.
Remember smart work - since you deal with a large number of tools and when you interact with them - they sometimes return a large amount of data and you need to find a way to better parse and get meaningful data from it hence you need to be smart with command line tools such as cut, grep, sed, awk and other tools. 
Smart, automated and repeatable ways - you need to learn as many tools as possible to do it this way.


## [Linux](./Linux.md)

## Software Development Lifecycle (SDLC) 

## Version Control and Source Code Management ~Essential~

## [Networking](./Networking.md)

  
## [Cloud Computing](./CloudComputing.md)


## Containers & Kubernetes

## Continuous Integration & Continuous Deployment [CI-CD]

## Continuous Testing

## Security Scanning



## Resources & References

- [Linux Upskill Sub Reddit](https://www.reddit.com/r/linuxupskillchallenge/)
- [DevOps Roadmap](https://roadmap.sh/devops)
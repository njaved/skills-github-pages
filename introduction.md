---
layout: page
title: Introduction
permalink: /Introduction/
---

The Modernized NBS 7 system is built to provide a straightforward transition from classic NBS Version 6 systems. It integrates seamlessly, layering on improved interfaces and functions, with the with classic systems that 
have already been deployed. Users will see a composite of the new features from NBS 7 Modernized and old features from classic NBS 6.  

## Purpose
The purpose of this document is to help an NBS system administrator deploy the NBS 7 infrastructure and microservices in an AWS environment. It will provide the information needed to set up the required environment, as well as convey a common understanding of the initial install.

## Runtime Environment Support
NBS 7 supports AWS and Azure as runtime options. The underlying system itself has been developed using a cloud-agnostic approach. This guide targets the AWS runtime. For more information on Azure, please contact NBSSupport@cdc.gov. Future versions of this guide will cover other cloud runtime environments that support Kubernetes such as Google Cloud Platform and Azure.

## Intended Audience
This guide is intended to be used to install NBS 7, a complex cloud-native application. It assumes familiarity with cloud technologies and tools: knowledge of your cloud service provider (e.g. AWS), runtime environment (e.g. Kubernetes), experience running Terraform and Helm., and experience debugging routine systems and infrastructure problems. You will need administrator-level access to your runtime environment, and access to a local system with a set of installed prerequisites. Please see the Prerequisites and Dependencies section below.  

![High level Infrastructure](/skills-github-pages/Untitled%20Diagram.drawio.png)


![alt text](https://github.com/njaved/skills-github-pages/blob/main/Untitled%20Diagram.drawio.png "High level Infrastructure")

<p align="center">
  <img src="https://github.com/njaved/skills-github-pages/blob/main/Untitled%20Diagram.drawio.png">
</p>

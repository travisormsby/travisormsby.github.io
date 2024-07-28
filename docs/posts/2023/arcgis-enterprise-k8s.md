---
draft: false 
date: 2023-08-01
categories:
  - ArcGIS Enterprise
  - Kubernetes
  - Teaching
---

# Deploying ArcGIS Enterprise on Kubernetes

I am the technical lead and primary instructor for this course. I am also responsible for implementing all course updates.

:simple-arcgis:
:simple-kubernetes:
:fontawesome-solid-graduation-cap:

[:octicons-arrow-right-24: See project](https://www.esri.com/training/catalog/64e5146ae0631b28f19674c5/deploying-arcgis-enterprise-on-kubernetes/){:target="_blank"}

<!-- more -->

This course originated with my colleage Tom Shippee, but I took control of it in 2022. This project is the most technically complex course offered by Esri, and managing course updates through new versions of ArcGIS Enterprise has been a challenge. More than any other work that I've done, this course demonstrates the benefit of building a network of contacts across an organization. I would not have been able to keep this course running if I had not cultivated relationships with members of the Product Management and Development teams. They have provided key support when we encountered technical challenges.

Managing this course also required getting buy-in from several levels of management to migrate the underlying infrastructure. To ease the original course development cycle, Enterprise was deployed on a series of local virtual machines. This pattern is not supported for ArcGIS Enterprise on Kubernetes, which limited our ability to have students work in an environment that would reflect their production environment. I was able to demonstrate the business case to management, and led the migration to a supported environment in Azure Kubernetes Service.
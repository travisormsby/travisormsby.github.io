---
draft: false 
date: 2023-10-01
categories:
  - ArcGIS Enterprise
  - ArcGIS Online
  - GitHub Actions
  - Teaching
  - YAML
---

# OK, but like, what's a web service really?

Workshop taught for the Minnesota GIS/LIS Consortium demystifying the way GIS services are implemented in ArcGIS Online and ArcGIS Enterprise.

:simple-arcgis:
:fontawesome-brands-github: 
:fontawesome-solid-graduation-cap:
:simple-yaml:

[:octicons-arrow-right-24: See project](https://projects.travisormsby.com/web-service){:target="_blank"}

[:octicons-arrow-right-24: Explore repository](https://github.com/travisormsby/web-service){:target="_blank"}

<!-- more -->

It used to be that GIS practioners accessed data by connecting to local storage or maybe to database servers running on their network. But the job has changed, and modern GIS is Web GIS. But a lot of people aren't exactly sure what it means to deliver GIS capabilities as web services. For a long time, that included me, and I struggled to understand the terminology in the Esri stack for creating web services.

This workshop grew out of my own frustrations trying to differentiate between things like map services and feature services. 

The site itself is created using mkdocs Material theme, with pages written in markdown and site configuration done in YAML. A GitHub Action publishes the site to a custom domain hosted by CloudFlare.
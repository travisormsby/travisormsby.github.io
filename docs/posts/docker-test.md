---
draft: false 
date: 2023-01-01
categories:
  - Docker
---

# Docker test container

Forked from a dead open source project to maintain a viable Docker test image capable of reporting its own container ID in a web app. This is more useful than the default Docker hello-world image for demonstrating the effect of multiple containers created from the same image.

:fontawesome-brands-docker:

[:octicons-arrow-right-24: See project](https://hub.docker.com/r/esritraining1/hello-world){:target="_blank"}

[:octicons-arrow-right-24: Explore repository](https://github.com/travisormsby/hello-world-container){:target="_blank"}

<!-- more -->

This container image was needed for Esri's training class on deploying ArcGIS Enterprise on Kubernetes. We needed a way to show students that a page was being served by a particular container when multiple containers were running. One thing I love about this project is that the underlying web application is written in an ancient version of PHP. I don't know anything about PHP, and that version won't be installed on any machine where the app needs to run. But by containerizing it, I can piggyback on somebody else's work and serve up a working app in any environment. 
---
draft: false 
date: 2020-05-01
categories:
  - CSS
  - Cartography
  - GitHub Actions
  - HTML
  - JavaScript
  - Jupyter Notebooks
  - Python
---


# Map coloring book

Explore Minnesota Census data as an interactive coloring book. U-Spatial Mapping Prize Honorable Mention: Most Provocative/Transformative.

:fontawesome-brands-css3:
:fontawesome-regular-map:
:fontawesome-brands-github:
:fontawesome-brands-html5:
:fontawesome-brands-js:
:simple-jupyter:
:fontawesome-brands-python:

[:octicons-arrow-right-24: See project](https://projects.travisormsby.com/map-coloring-book){:target="_blank"}

[:octicons-arrow-right-24: Explore repository](https://github.com/travisormsby/map-coloring-book){:target="_blank"}

<!-- more -->

During the early part of the COVID pandemic, adult coloring books suddenly became popular. For many people, it was a way to focus on something non-horrible while the rest of the world seemed to be falling apart. Some of these were color-by-number apps where you would choose a color and the app would highlight all the areas that should be that color. 

That seemed like a model that would be interesting to use to explore data on a choropleth map. Pick the color of a class break, then see all the regions that belong to that class. 

From this project, I learned that if you're manually manipulating svg, you're probably doing it wrong.

I used to manually FTP updates to this app to the hosting server. Like several other projects, I have configured a GitHub Action to automatically publish any changes to a custom domain hosted by CloudFlare.
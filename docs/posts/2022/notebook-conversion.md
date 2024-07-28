---
draft: false 
date: 2022-02-01
categories:
  - Bash
  - Docker
  - GitHub Actions 
---

# Jupyter Notebook Conversion

This GitHub Action allows you to add a step to a workflow that automatically converts all Jupyter Notebooks in a repository into static HTML.

:material-bash:
:fontawesome-brands-docker:
:fontawesome-brands-github: 

[:octicons-arrow-right-24: Explore repository](https://github.com/travisormsby/convert-notebooks){:target="_blank"}  

<!-- more -->

It can be hard to figure out how to share Jupyter Notebooks with people. You can convert the notebooks to HTML, but you have to re-export every time you make a change to the notebook. I had a project with a dozen notebooks, and continuously exporting them started to feel suspiciously like work. Frankly, it offended me that I was spending time manually exporting notebooks to HTML. 

So I wrote a custom GitHub Action to do it for me. 

This project is a good example of the motivational power of laziness. One of the things I've discovered about myself is how hard I'll work in order to avoid work. And I think that's a good thing. 
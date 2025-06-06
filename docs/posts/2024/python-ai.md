---
draft: false 
date: 2024-06-16
categories:
  - GitHub Actions
  - Python
  - Teaching
  - YAML
---

# Use AI Models To Write Python Code, Even Though They Are Bad At It 

Workshop taught for the Minnesota GIS/LIS Consortium outlining how to make effective use of generative AI to write Python code.

:fontawesome-brands-github: 
:fontawesome-brands-python:
:fontawesome-solid-graduation-cap:
:simple-yaml:

[:octicons-arrow-right-24: See project](https://projects.travisormsby.com/python-ai-assistants){:target="_blank"}

[:octicons-arrow-right-24: Explore repository](https://github.com/travisormsby/python-ai-assistants){:target="_blank"}

<!-- more -->

State-of-the-art LLM interfaces like ChatGPT or GitHub Copilot are both incredibly cool, and really frustrating to use. They occupy the uncanny valley where their output is good enough to be interesting, but bad enough to be useless. They can churn out plausible-looking code, but you have to actually know something about that code in order to correctly evaluate it. Non-experts struggle with being able to perform that evaluation because the skills you need to evaluate code are largely the same skills you need to create that code in the first place. 

Even so, generative AI tools are coming. They will likely be integrated into a variety of products. I don't think LLMs are fundamentally a scam the way that cryptocurrency is. There are genuine reasons to think generative AI can add value to human work, like the fact that the models can remember much more than a single person does. 

I'm concerned about people using these models when they don't really know how. Those people are going to make mistakes, with potentially disaterous consequences, and there will be a huge temptation to try to avoid accountability by pinning the mistake on the AI model. This workshop is me trying to stop that from happening.

The site itself is created using mkdocs Material theme, with pages written in markdown and site configuration done in YAML. A GitHub Action publishes the site to a custom domain hosted by CloudFlare.
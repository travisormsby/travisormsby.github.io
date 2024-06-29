---
draft: false 
date: 2024-01-01
categories:
  - CSS
  - HTML
  - Python
  - Teaching
---

# Python feature quiz

Web app to test recognition of fundamental Python patterns. Written in Python compiled to WASM running directly in the browser. No backend required.

:fontawesome-brands-html5:
:fontawesome-brands-css3:
:fontawesome-brands-python:
:fontawesome-solid-graduation-cap:

[:octicons-arrow-right-24: See project](https://projects.travisormsby.com/feature_quiz){:target="_blank"}

[:octicons-arrow-right-24: Explore repository](https://github.com/travisormsby/feature_quiz){:target="_blank"}

<!-- more -->

This project has two interesting aspects: the creation of the Python script and the deployment of the app. The script was originally written as a command-line program to support a training on using AI assistants to write Python code. So naturally, I heavily relied on GitHub Copilot to generate a significant amount of the code, using the strategies I teach in that workshop. 

For the web app creation, I've done enough projects with custom JavaScript that I think I've earned the right to say that I hate JavaScript. I'm proud of those projects, but there's a reason I don't list JavaScript as a skill on my resume. I never want to write it again.

But I love Python. So I was excited to see the [Pyodide](https://pyodide.org/en/stable/) and [PyScript](https://pyscript.net/) projects that let you write Python that runs client-side in the browser. I like writing it better than JavaScript, but it is much slower to load the code. There's still more DOM manipulation that I would like to do, but I'll be keeping my eye on these projects and hopeful that I can more easily write browser apps with Python in the future.
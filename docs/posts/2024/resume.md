---
draft: false 
date: 2024-06-01
categories:
  - CSS
  - GitHub Actions
  - HTML
  - JavaScript
---

# Resume

My resume is a web app with some interactivity provided by CSS and a little bit of JavaScript. Updates to the resume trigger a GitHub Action to publish the resume to GitHub Pages and a CloudFlare worker that publishes the resume to a custom domain CloudFlare page.

:fontawesome-brands-css3:
:fontawesome-brands-github: 
:fontawesome-brands-html5:
:fontawesome-brands-js:

[:octicons-arrow-right-24: See project](https://travisormsby.com){:target="_blank"}

[:octicons-arrow-right-24: Explore repository](https://github.com/travisormsby/cloud-resume){:target="_blank"}

<!-- more -->

This resume is part of my attempt to complete the [Cloud Resume Challenge](https://cloudresumechallenge.dev/docs/the-challenge/) using no paid resources other than registering a custom domain. Originally hosted in a storage blob in Oracle Cloud Infrastructure, I migrated this project to CloudFlare to take advantage of automatic publishing to a custom domain.

One big lesson for me from creating this resume is that it requires far more custom CSS and HTML than I care to create. Even though I started with a template created by somebody else, customizing it to my liking was time consuming. I would not recommend the same strategy for other people. It would probably have been better to create something with easier to configure tools and integrated hosting, like WordPress. The only disadvantage to that strategy is the increased money cost for hosting. But I definitely spend more than $50/year worth of my time doing it the hard way, so the money cost is probably a lower opportunity cost.
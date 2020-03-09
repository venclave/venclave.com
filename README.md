venclave.com
============

This is the repository that builds the static website for [venclave.com](https://venclave.com/) using [hugo](https://gohugo.io/).

Current build status:
[![Netlify Status](https://api.netlify.com/api/v1/badges/620e02cd-7598-4e31-9f82-afde33c232b4/deploy-status)](https://app.netlify.com/sites/naughty-roentgen-93834e/deploys)

CI / CD
-------
The pipeline runs on a free instance of [Netlify](https://www.netlify.com/), since this supports setting security headers compared to Github Pages.

Building
--------
`hugo server` to run locally, `hugo --gc --minify` to build minified output to `generated/`.

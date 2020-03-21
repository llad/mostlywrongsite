---
title: Website Setup
description: How I setup this website.
date: 2020-03-21
tags:
  - Development
layout: layouts/post.njk
---
Wanted a website to publish stuff and experiment.

Goals:
* Simple
* Javascript focused
* Can experiment with multiple technologies and frameworks
* Something I can grow
* Develop almost anywhere, including iPad

Landed on:
* [DigitalOcean](https:/digitalocean.com) - Development environment and maybe for running experiments.
* [Eleventy](https://11ty.dev) - Static site generator that sounded cool.
* [Netifly](https://netifly.com) - Static site web host.

## Initial Setup
1. Created a DigitalOcean account and created a Node.js Quick Start Droplet.
2. Configured my iPad to work with the Droplet. I use Code Editor and Prompt by Panic.
2. Messed around with [Eleventy tutorials](https://www.11ty.dev/docs/getting-started/). 
3. Started with [Eleventy Base Blog](https://github.com/11ty/eleventy-base-blog) and the [Netifly builder](https://app.netlify.com/start/deploy?repository=https://github.com/11ty/eleventy-base-blog) for it.
4. Cloned my new github repository of the base blog.
5. Setup Netifly to handle DNS of the domain name I bought last month.


## Site Development
* Edit all files through SFTP connection through Code Editor
* Use the Code Editor terminal to run the serve command, which runs Eleventy on any saved changes and serves a test version of the site.
``` text/2-3
npx @11ty/eleventy --serve
```
* Publish using git push
``` text/2-3
git push origin master
```

## Notes
* Save github password:
``` text/2-3
git config --global credential.helper cache
```




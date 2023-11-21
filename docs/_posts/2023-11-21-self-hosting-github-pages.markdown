---
layout: post
title:  "Self Hosting on Github Pages with Jekyll"
date:   2023-11-21 15:27:41 -0600
categories: jekyll
---
I found myself wanting to create a blog to record the steps along 
the way as I set up more self hosted services. There are various options with the most common being wordpress. 
Being at my parents home for Thanksgiving this week I wanted to get started with something I could start 
with hosting on the cloud as I don't have access to my home server setup. Also I'm cheap so I didn't want to pay for hosting. 
Github pages seemed like a great option 
combined with the static site generator Jekyll. 
It works quite well once you get it set up, the development/deploy process goes something like this: 


1. update one of the markdown files defining a post or homepage
2. run `bundle exec jekyll serve --livereload` to build and serve the site at `localhost:4000`
3. commit and push changes to github 


and thats its.

I'll link the setup guides I used here for those who would like to try the setup themselves. 
There were a few small snags in setup around getting the ruby to install properly 
(locking the right openssl version for example). But after googling through a few issues it was up and running
within 1 hr. 


- [Jekyll quickstart](https://jekyllrb.com/docs/) 
- [Github Pages Guide](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll)
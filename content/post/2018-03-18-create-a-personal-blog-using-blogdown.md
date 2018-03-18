---
title: Create a Personal blog Using Blogdown
author: Alex Mwangi
date: '2018-03-18'
slug: create-a-personal-blog-using-blogdown
categories:
  - R
tags:
  - R Markdown
---

Install Hugo using blogdown from Rstudio
blogdown::install_hugo()
Install Hugo using blogdown from a local directory
blogdown:::install_hugo_bin("path/to/hugo.exe")
Links
https://alison.rbind.io/post/up-and-running-with-blogdown/
Create new site
library(blogdown)
new_site(theme = "road2stat/hugo-tanka", theme_example = TRUE)

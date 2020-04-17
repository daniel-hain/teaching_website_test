---
date: "2020-04-17T21:48:51-07:00"
title: About
---

This is a "hello world" example website for the [**blogdown**](https://github.com/rstudio/blogdown) package. The theme was forked from [@jrutheiser/hugo-lithium-theme](https://github.com/jrutheiser/hugo-lithium-theme) and modified by [Yihui Xie](https://github.com/yihui/hugo-lithium).

This website can be found [here](https://daniels-test-website.netlify.app/), and the corresponding github repository [here](https://github.com/daniel-hain/teaching_website_test/tree/master/content/post). I tried to set up an easy process to get a hosted github page set up. Here what I learned so far. First, in connection with RStudio and github, it's rather easy.

Lets go through the workflow:

1. Set up a blogdown project infrastructure, which is described [here](https://bookdown.org/yihui/blogdown/)
2. Set up a new github repository (no readme), and link the git to the Rtudio. This involves some Shell, and is nicely described [here](https://jennybc.github.io/2014-05-12-ubc/ubc-r/session2.4_github.html).
3. Generally, how to do all the git stuff in Rstudio, check [here](https://aberdeenstudygroup.github.io/studyGroup/lessons/SG-T1-GitHubVersionControl/VersionControl/)


* Netlify: Then it pretty much up where you want to host it. You can put it on netlify, which is easy when everything is on github and you have an account there.

* GitHubPages: Another alternative is to host it via github pages. This seems easy and appropriate for your personal website or smll course websites without too much infrastructure.
  * The general infrastructure is decribed [here](https://bookdown.org/yihui/blogdown/github-pages.html)
  * Generally, GitHubPages is only supposed to work with Jekill to build sites, but it turns out most Hugo tenplates work just fine. A nice description how to get started can be found [here](https://www.r-bloggers.com/starting-a-rmarkdown-blog-with-bookdown-hugo-github/)
  * In case you just want to render a website ()such as a revealjs presentation, its even easier as described [here](https://annaken.github.io/hosting-revealjs-presentation-github-pages/)
  
  Have fun!










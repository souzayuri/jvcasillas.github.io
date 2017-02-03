---
title: "Knitr bootstrap"
date: "2014-05-27"
output:
  html_document:
    theme: readable
    highlight: textmate
    include:
      before_body: ../../site_libs/includes/before_body.html
      in_header: ../../site_libs/includes/in_header.html
      after_body: ../../site_libs/includes/after_body.html
    css: ../../site_libs/assets/css/style.css
---

Knitr bootstrap makes generating standalone reports extremely easy and the output looks really neat. Check out the example [here][here]. To recreate this you need to download the preview release of [R Studio][R Studio], and set up the front matter as follows:

```
---
output:
  knitrBootstrap::bootstrap_document:
    title: ""
    theme: default
    highlight: sunburst
    theme.chooser: TRUE
    highlight.chooser: TRUE
---
```

[here]: /posts/assets/knitr_bootstrap/knitr_bootstrap.html
[R Studio]: http://rmarkdown.rstudio.com/index.html
---
title: "{{ replace .Name "-" " " | title }}"
description: "Desc Text."
date: {{ .Date }}
draft: true
# weight: 1
# aliases: ["/first"]
tags: ["blog"]
author: ["Fraser"]
showToc: true
TocOpen: false
# canonicalURL: "https://canonical.url/to/page"
# disableHLJS: true # to disable highlightjs
hideSummary: false
# searchHidden: true
# hiddenInHomeList: true
cover:
    image: "example.jpg" # image path/url
    alt: "example" # alt text
    caption: "An Example" # display caption under cover
    relative: true # when using page bundles set this to true
    hidden: false # only hide on current single page
---
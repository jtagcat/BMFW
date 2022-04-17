---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
tags: []
draft: true

navbar: true
titleAsH1: true # ^ title from above (front matter) will also be rendered
# site-level overrides:
#readingTime: false # '8 minute read'
#titleAnchors: false # set custom title IDs with: ## Level 2 {#foo-bar}
---

---
title: "{{ replace .Name "-" " " | title }}"
author: "{{ .Site.Params.Author }}"
draft: false
menu:
  main:
    identifier: "{{ replace .Name "-" " " | title }}"
    weight: 0 
    parent: ""
---

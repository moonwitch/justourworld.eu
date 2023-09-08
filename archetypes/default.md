---
title: {{ .TranslationBaseName | replaceRE "^([[:digit:]]+-){3}" "" | replaceRE "-" " " | title }}
categories:
  - post
tags:
  - 
date: "{{ now.Format "2006-01-02" }}"
lastmod: "{{ now.Format "2006-01-02" }}"
lang: nl
comments: true
draft: false
---

---
title: "{{ replaceRE `^\d+-` "" .File.ContentBaseName | humanize | title }}"
description: ""
date: {{ .Date }}
draft: true
# toc: false      # hide "On this page"
# justify: true   # justified paragraphs
# references:     # or drop a .bib file next to this post and \cite{key}
#   - key: smith2024
#     author: Smith, Jane
#     title: A Paper
#     year: 2024
#     url: https://example.org
---


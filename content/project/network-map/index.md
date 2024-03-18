---
title: Network-Map
summary: Creates a simple network and live-map.
tags:
  - Python
  - Fun
date: '2024-02-01T00:00:00Z'


image:
  caption: Example of Gephi resulting graph
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Source code
    url: https://github.com/nollive/network-map-py
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

This simple Python project generates nodes & links in order to create a network, based on data in json files. This script is applied to friendships between roommates in different shared apartments in Nantes. Given a json file with the coordinates of theses flats, it can also build a live map showing these links spatially.
It can also export the resulting graph in a .gexf file for further analysis in Gephi.

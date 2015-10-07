---
layout: page
title: Thesis works
tagline: Fault Tolerant Systems Research Group
---

# Bachelor's thesis works

{% assign bsc = site.data.bsc.thesis_works %}
{% for bsc_thesis in bsc_theses %}* {{ bsc_thesis.author }}: [{{ bsc_thesis.title }}](bsc/{{ bsc_thesis.filename }}), konzulensek: {{ bsc_thesis.advisors }}
{% endfor %}

# Master's thesis works


---
layout: page
tagline: Fault Tolerant Systems Research Group
---

# Bachelor's thesis works

{% assign bsc_thesis_works = site.data.bsc.thesis_works %}
{% for bsc_thesis in bsc_thesis_works %}* {{ bsc_thesis.author }}: [{{ bsc_thesis.title }}](bsc/{{ bsc_thesis.filename }}.pdf), konzulensek: {{ bsc_thesis.advisors }}
{% endfor %}

# Master's thesis works

{% assign msc_thesis_works = site.data.msc.thesis_works %}
{% for msc_thesis in msc_thesis_works %}* {{ msc_thesis.author }}: [{{ msc_thesis.title }}](msc/{{ msc_thesis.filename }}.pdf), konzulensek: {{ msc_thesis.advisors }}
{% endfor %}

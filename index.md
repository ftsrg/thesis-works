---
layout: page
tagline: Fault Tolerant Systems Research Group
---

# Bachelor's thesis works

{% for file in site.static_files %}{% if file.path contains "/bsc/" && file.extname == ".pdf" %}
* [{{ file.path }}]({{ site.baseurl }}{{ file.path }}){% endif %}{% endfor %}

# Master's thesis works

{% for file in site.static_files %}{% if file.path contains "/msc/" && file.extname == ".pdf" %}
* [{{ file.path }}]({{ site.baseurl }}{{ file.path }}){% endif %}{% endfor %}

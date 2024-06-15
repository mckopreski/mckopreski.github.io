---
layout: default
title: Research
---

I am interested in geometric group theory and low dimensional
topology.  In particular, I am working on describing the geometric
and topological structure of the mapping class groups of infinite
type surfaces and other Polish groups.

## Papers and preprints 

{% for item in site.data.publications %}
1. _<u>{{ item.title }}</u>_.
{{ item.cite }} {% if item.coauthors %}(with {{ item.coauthors }}){% endif %} 
{% if item.pdf %}[preprint]({{
item.pdf }}).{% endif %}
{% endfor %}

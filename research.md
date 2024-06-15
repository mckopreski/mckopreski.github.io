---
layout: default
title: Research
---

I am interested in geometric group theory and low dimensional
topology.  In particular, I am working on describing the geometric
and topological properties of the mapping class groups of infinite
type surfaces and other Polish groups.

## Publications

{% for item in site.data.publications %}
1 "{{ item.title }}." {{ item.cite }} {% if item.coauthors %}_(Joint work
with {{ item.coauthors }})_{% endif %} {% if item.pdf %}[preprint]({{
item.pdf }})
{% endfor %}

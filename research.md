---
layout: default
title: Research
---

I am interested in geometric group theory and low dimensional
topology.  My current research aims to describe the geometric
and topological structure of the mapping class groups of infinite
type surfaces and other Polish groups.

## Papers and preprints 

{% for item in site.data.publications %}
1. _<u>{{ item.title }}</u>_. {{ item.cite }}{% if item.coauthors %} (with {{ item.coauthors }}){% endif %}{% if item.arxiv %} [[arXiv]](https://arxiv.org/abs/{{ item.arxiv }}){% endif %}{% if item.pdf %} [[pdf]]({{ item.pdf }}){% endif %}
{% endfor %}

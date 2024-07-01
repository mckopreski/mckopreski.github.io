---
layout: default
title: Teaching
---

### University of Utah

{% for item in site.data.teaching-utah %}
* {{ item.courseno }}: {{ item.name }} _({{ item.role }}, {{ item.term }})_
{% endfor %}

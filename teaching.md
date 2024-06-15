---
layout: default
---

### University of Utah

{% for item in site.data.teaching-utah %}
* {{ item.courseno }}: {{ item.name }} ({{ item.term | uppercase }})
  {{ item.role }}
{% endfor %}

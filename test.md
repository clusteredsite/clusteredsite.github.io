---
layout: null
---

Testing the server serving this.

{% if site.github %}
This is on GitHub
{% else %}
This site is on GitLab
{% endif %}

***

GL: {{ site.git.last_commit.long_sha }}

GH: {{ site.github.build_revision }}

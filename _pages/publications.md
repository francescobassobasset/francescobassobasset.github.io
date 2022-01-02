---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Find the latest version of the publication list on [Scholar](https://scholar.google.com/citations?user=0_u_-3oAAAAJ&hl=it&oi=ao) or [Scopus](https://www.scopus.com/authid/detail.uri?authorId=57192257192).
<meta http-equiv='Content-Type' content='text/html; charset=utf-8' /> 
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  You can also find my articles on <u><a href="{{ site.author.googlescholar }}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<h2 class="archive__subtitle">Manuscripts in Preparation</h2>
{% assign pubs = site.publications | where: "pubtype", "manuscript" | reverse %}
{% for post in pubs %}
  {% include archive-single.html %}
{% endfor %}

<h2 class="archive__subtitle">Reports</h2>
{% assign pubs = site.publications | where: "pubtype", "report" | reverse %}
{% for post in pubs %}
  {% include archive-single.html %}
{% endfor %}

<h2 class="archive__subtitle">Theses</h2>
{% assign pubs = site.publications | where: "pubtype", "thesis" | reverse %}
{% for post in pubs %}
  {% include archive-single.html %}
{% endfor %}

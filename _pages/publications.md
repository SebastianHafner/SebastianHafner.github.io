---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on my<u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

##Journal publications


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

##Conference proceedings:

##Preprings:
---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Writing Samples
{% for post in site.publications reversed %}
  {% if post.papertype == "writing_sample" %}
<p style="line-height: 1;">
<span class="archive__subtitle" style="font-size: small;">{{ post.month }} {{ post.year }}</span><br>
<a class="post-link" href="{{ post.permalink }}">{{ post.title }}</a><br>
<span style="font-style: italic;">{{ post.venue }}</span>
</p>
  {% endif %}
{% endfor %}
---
layout: default
title: Home
---

<h3>Pages</h3>
<p>
{% for post in site.posts %}
{{ post.date | date_to_string }} <a href="/{{ site.github.project_title" }}{{ post.url }}">{{ post.title }}</a><br>
{% endfor %}
</p>

<p>
Github: <br>
{{site.github}}
</p>

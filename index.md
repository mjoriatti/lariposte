---
---

{% for post in site.posts %}
<div>

<div>
<h1>{{ post.title }}</h1>
<p><time>{{ post.date | date_to_string }}</time></p>
</div>

<div>
{{ post.excerpt }}
</div>

<div>
  <a href='lariposte/{{ post.url }}'>lire l'article 2...</a>
</div>

</div>
{% endfor %}

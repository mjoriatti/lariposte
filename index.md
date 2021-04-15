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
  <a href='{{post.url}}'>lire l'article...</a>
</div>

</div>
{% endfor %}

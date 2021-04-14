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

<div markdown="1">
[lire l'article...]({{ post.url }})
</div>

</div>
{% endfor %}

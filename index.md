---
---

{% for post in site.posts %}

<article class="post">

<header class="post-header">
<h1 class="post-title"><a href='{{ site.baseurl }}{{post.url}}'>{{ post.title }}</a></h1>
<p><time>{{ post.date | date_to_string }}</time></p>
</header>

<section class="post-excerpt">
{{ post.excerpt }}
</section>

</article>

{% endfor %}

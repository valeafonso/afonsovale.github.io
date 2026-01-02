---
layout: default
---

# Hi, I’m Afonso 👋

I write about software engineering, experiments, and what I’m learning.

<div class="callouts">
  <p><strong>Start here:</strong> <a href="{{ '/about/' | relative_url }}">About</a> · <a href="{{ '/projects/' | relative_url }}">Projects</a> · <a href="{{ '/uses/' | relative_url }}">Uses</a> · <a href="{{ '/subscribe/' | relative_url }}">Subscribe</a></p>
</div>

## Latest posts

<ul class="postlist">
  {% for post in site.posts limit:5 %}
    <li class="postlist__item">
      <a class="postlist__title" href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <div class="postlist__meta">{{ post.date | date: "%b %-d, %Y" }}</div>
      <div class="postlist__excerpt">{{ post.excerpt }}</div>
    </li>
  {% endfor %}
</ul>

<p><a href="{{ '/blog/' | relative_url }}">→ All posts</a></p>



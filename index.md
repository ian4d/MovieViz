---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

BLAGH!

POST LOOP BEGIN
{% for post in site.posts %}
  <h2>{{ post.title }}</h2>
  {{ post.content }}
{% endfor %}
POST LOOP END
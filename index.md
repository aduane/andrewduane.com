---
layout: default
title: Hey There!
---

My name is Andrew. I'm a software engineer that has worked in the healthcare
industry since 2011, first dental, then oncology. I really enjoy programming in
ruby, but I'd love to start branching out more. Working in a space that helps
others has been incredibly fulfilling, and I'm not sure I could work anywhere
that isn't directly helping people or bringing them joy.

When I'm not programming, I'm thinking about a greener future with electric
cars, getting better at bowling, and keeping my childhood alive by modding
retro game systems for use with modern TVs.

_Andrew lives in the Seattle area with his wife, Alecia, and their cat,
Stella._

{% for post in site.posts limit:1 %}
### Latest Post: {{post.date | date: '%B %d, %Y' }} – [{{post.title}}]({{post.url}})
{% endfor %}

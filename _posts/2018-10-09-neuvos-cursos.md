---
title: "Neuvos Cursos!"
categories:
  - News
tags:
  - cursos
  - news
---

{% capture fig_img %}
[![Foo](/assets/images/posts/cursos.jpg)](/courses/)
{% endcapture %}

{% capture fig_caption %}
Nuevos cursos en Happy House English School Argés!!
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>{{ fig_caption | markdownify | remove: "<p>" | remove: "</p>" }}</figcaption>
</figure>

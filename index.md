---
title: Welcome to my website
feature_image: "https://picsum.photos/1300/400?image=989"
feature_text: |
  ## Hello world
---

{% for post in paginator.posts %}
  {% capture currentdate %}{{post.date | date: "%A, %B %d, %Y"}}{% endcapture %}
  {% if currentdate != thedate %}
    <h2>{{ currentdate }}</h2>
    {% capture thedate %}{{currentdate}}{% endcapture %}
{% endif %}

---
layout: index
title: snake
permalink: /snake/
---
the short introduction of the snake head

After the the Old Summer Palace was looted and burned by the British and French troops in 1860, the snake head remained overseas, also unaccounted for, and its current whereabouts unknown.

{% for snake in site.snake %}

<img src="{{ snake.image-url }}" width = 256>
<p>{{ snake.title }} by {{ snake.creator }}</p>
<p><a href="{{ snake.license-url }}">{{ snake.license }}</a></p>

{% endfor %}
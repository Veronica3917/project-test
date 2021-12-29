---
layout: index
title: Goat
permalink: /goat/
---
the short introduction of the goat head

After the the Old Summer Palace was looted and burned by the British and French troops in 1860, the goat head remained overseas, also unaccounted for, and its current whereabouts unknown.

{% for goat in site.goat %}

<img src="{{ goat.image-url }}" width = 256>
<p>{{ goat.title }} by {{ goat.creator }}</p>
<p><a href="{{ goat.license-url }}">{{ goat.license }}</a></p>

{% endfor %}
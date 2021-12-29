---
layout: index
title: Dragon
permalink: /dragon/
---
the short introduction of the dragon head

After the Old Summer Palace was looted and burned by the British and French troops in 1860, the Dragon's Head remained overseas. The dragon's head was originally part of a water clock fountain in front of Haiyantang in the Building of the the Old Summer Palace.
According to a report by Shenzhen TV in March 2009, Wang Du, a Chinese collector from Taiwan, said in an interview that the unaccounted-for dragon head was in Taiwan. Wang Du said that the dragon head was in good condition in the 1980s. It was worth four or five million Taiwanese dollars at the time. The collector had planned to have the dragon head show up for auction, but because of the furore that befell the rat and rabbit heads, the collector does not expect to have the dragon head and other unaccounted-for animal heads show up anytime soon.
On the afternoon of 17 December 2018, French time, a dragon head, suspected to be one of the 12 animal heads of the Old Summer Palace zodiac, appeared at a small auction in Paris, and was eventually purchased by a Chinese buyer for RMB 24 million.

{% for dragon in site.dragon %}

<img src="{{ dragon.image-url }}" width = 256>
<p>{{ dragon.title }} by {{ dragon.creator }}</p>
<p><a href="{{ dragon.license-url }}">{{ dragon.license }}</a></p>

{% endfor %}
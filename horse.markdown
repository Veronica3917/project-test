---
layout: index
title: Horse
permalink: /horse/
---
the short introduction of the horse head

After the the Old Summer Palace was looted and burned by the British and French troops in 1860, the horse's head remained overseas, eventually being auctioned by Sotheby's in 2007.
Made in the twenty-fourth year of the Qianlong reign of the Qing dynasty, the head of the Horse of the Year is one of the most unique of the twelve animal heads of the Chinese zodiac, with its cloud-like shape and curly hair on the top of its head suggesting that it is a typical European-style prince on a white horse. Perhaps the Italian designer Lang Shining expressed his overwhelming envy of the amorous emperor with his 3,000 beauties in this work. Even more coincidentally the twelve Chinese zodiac signs also represent these twelve animal hours, of which the horse represents exactly the noon hour, so that when the horse's head sprays water, all the animals spray together.
In October 2007, Stanley Ho bought back the bronze statue of the horse's head at a huge cost of HK$69.1 million.
On 13 November 2019, the Ministry of Culture and Tourism and the State Administration of Cultural Heritage held a donation ceremony for the bronze statue of the Horse's Head at the Old Summer Palace in the National Museum of China. The State Administration of Cultural Heritage, by consensus with Mr Stanley Ho, allocated the Horse Head to the collection of the Old Summer Palace Administration in Beijing, returning it to its original home.  
On 1 December 2020, the bronze statue of the Horse's Head was officially returned to the Old Summer Palace , the first important cultural relic lost overseas to return to the Old Summer Palace.

{% for horse in site.horse %}

<img src="{{ horse.image-url }}" width = 256>
<p>{{ horse.title }} by {{ horse.creator }}</p>
<p><a href="{{ horse.license-url }}">{{ horse.license }}</a></p>

{% endfor %}
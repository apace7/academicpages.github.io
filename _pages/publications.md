---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Refereed Journal Publications
------

1. **Pace, Andrew B.**, Martinez, G. D., Kaplinghat, M., Muñoz, R. R., 2014, MNRAS, 442, 1718; *Evidence for substructure in Ursa Minor dwarf spheroidal galaxy using a Bayesian object detection method* [ADS](http://adsabs.harvard.edu/abs/2014MNRAS.442.1718P)

1. Fillingham, Sean P., Cooper, Michael C., **Pace, Andrew B.**, Boylan-Kolchin, Michael, Bullock, James S., Garrison-Kimmel, Shea, Wheeler, Coral, 2016, MNRAS, 463, 1916; *Under pressure: quenching star formation in low-mass satellite galaxies via stripping* [ADS](http://adsabs.harvard.edu/abs/2016MNRAS.463.1916F)


For the full list of academic publications, see my [CV](link) and [publication](link) list or check out my [ADS](link), [Spires](link), [Google Scholar](link) profile.



Submitted
------

1.



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

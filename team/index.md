---
title: Team
---

# <i class="fas fa-users"></i>Team

## Stajich Lab Members

{% capture html %}
{% include team-list.html role="pi" %}
{% include team-list.html role="postdoc" %}
{% include team-list.html role="phd" %}
{% include team-list.html role="undergraduates" %}
{% endcapture %}

{% include centerer.html html=html %}

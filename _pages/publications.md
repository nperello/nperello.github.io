---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
*Equal contribution, ^Equal advising

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---
layout: archive
title: "Non-Archival Publications"
permalink: /publicationsnon/
author_profile: true
---
{% include base_path %}
{% for post in site.publicationsnon reversed %}
  {% include archive-single.html %}
{% endfor %}
---
layout: archive
title: "Publications"
permalink: publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}



* Ph.D in statistics at the University of Alberta, supervised by [Professor Yaozhong Hu](https://sites.ualberta.ca/~yaozhong/).

* MS in mathematics at Kansas University, supervised by [Professor Yaozhong Hu](https://sites.ualberta.ca/~yaozhong/).

* BS in statistics at Huazhong University of Science and Technology.

---
permalink: /
title: "ML-Perspectives"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Technical Blog to discuss topics in Machine Learning Theory. 


 {% include base_path %} {% capture written_year %}'None'{% endcapture %} {% for post in site.posts %} {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %} {% if year != written_year %} {% capture written_year %}{{ year }}{% endcapture %} {% endif %} {% include archive-single.html %} {% endfor %}
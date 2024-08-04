---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Tong, L., Xu, K., Hu, J., Ferrarotti, F., & Schewe, K. D. (2023, May). Exploration of Reflective ASMs for Security. In International Conference on Rigorous State-Based Methods (pp. 185-192). Cham: Springer Nature Switzerland.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

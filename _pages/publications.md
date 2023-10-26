---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

R. Ma, L. Lam, B.A. Spiegel, A. Ganeshan, R. Patel, B. Abbatematteo, D. Paulius, S. Tellex, G. Konidaris, “Skill Generalization With Verbs” in _International Conference for Intelligent Robots and Systems (IROS) 2023_, Accepted. <u><a href="https://cs.brown.edu/~gdk/pubs/skillgen_verbs.pdf">Paper Link</a>.</u>

R. Ma, L. Lam, B.A. Spiegel, A. Ganeshan, R. Patel, B. Abbatematteo, D. Paulius, S. Tellex, G. Konidaris, “Skill Generalization With Verbs” in _International Conference for Intelligent Robots and Systems (IROS) 2023_, Accepted.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

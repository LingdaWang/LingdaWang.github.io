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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
[**Joltik:  Enabling Energy-Efficient ”Future-Proof” Analytics on Low-Power Wide-Area Networks**](https://dl.acm.org/doi/10.1145/3372224.3419204) <br>
**Mingran Yang**, Junbo Zhang, Akshay Gadre, Zaoxing Liu, Swarun Kumar, and Vyas Sekar <br>
In *Proceedings of the 26th ACM Annual International Conference on Mobile Computing and Networking (MobiCom)*, 2020 <br>
[\[Paper PDF\]](https://dl.acm.org/doi/pdf/10.1145/3372224.3419204)  /  [\[Elevator Pitch\]](https://www.youtube.com/watch?v=quMCp-M51CU&feature=youtu.be)  /  [\[Full Presentation\]](https://www.youtube.com/watch?v=a0bANzQmqhc&feature=youtu.be)  /  [\[Code\]](https://github.com/Joltik-project/Joltik)  /  [\[Slides\]](/files/Joltik/joltik_full_presentation.pdf) <br>

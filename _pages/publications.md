---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<span style="color: rosybrown">Copyright: The copyright of the papers below is owned by the respective publishers. Personal use of the electronic versions here provided is permitted. However, permission to reprint/republish this material for advertising or promotional purposes or for creating new collective works for resale or redistribution to servers or lists, or to reuse any copyrighted component of this work in other works must be obtained from the publishers.</span>
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

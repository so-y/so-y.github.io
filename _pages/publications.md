---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

<p style="margin-bottom: -10px; padding-bottom: 0; color: #888888"><i><b><span style="color: #992017">Red</span></b> titles indicate published or accepted papers.<br>
<b><span style="color: #888888">Grey</span></b> titles indicate pre-prints.</i></p>

{% for post in site.publications reversed %}
{% include archive-single.html %}
{% endfor %}

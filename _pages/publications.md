---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
You can also find my articles on <a href="https://scholar.google.com/citations?user=zL10IUEAAAAJ&hl=en">my Google Scholar profile</a>

{% include base_path %}

<div><h2> 2022 </h2></div>
<hr style="border-color:black;">
{% for post in site.publications reversed %}
  {% if post.year == 2022 %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<div><h2> 2021 </h2></div>
<hr style="border-color:black;">
{% for post in site.publications reversed %}
  {% if post.year == 2021 %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<div><h2> 2020 </h2></div>
<hr style="border-color:black;">
{% for post in site.publications reversed %}
  {% if post.year == 2020 %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<div><h2> 2019 </h2></div>
<hr style="border-color:black;">
{% for post in site.publications reversed %}
  {% if post.year == 2019 %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

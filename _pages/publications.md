---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
header:
  overlay_image: /assets/images/ocean1.jpg
  overlay_filter: 0.7 # same as adding an opacity of 0.5 to a black background
---

You can also find my articles on <u><a href="https://scholar.google.com/citations?hl=en&user=JcMg2gMAAAAJ">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

## More about some of my papers:
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

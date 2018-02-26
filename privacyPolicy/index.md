---
layout: default
title: Privacy Policies
subtitle: Privacy Policy for my Apps developed
permalink: /privacyPolicy/
---
<div align="center"><h1>Privacy Policy pages</h1></div>
<ul>
  {% for page in site.pages %}
    {% if page.layout == "privacyPolicy" and page.dir == "/privacyPolicy/" %}
    <li>
        <a href="{{ page.url | prepend: site.baseurl }}">{{ page.subtitle | escape }}</a>
        <blockquote> {{page.description}}</blockquote>
    </li>
    {% endif %}
  {% endfor %}
</ul>

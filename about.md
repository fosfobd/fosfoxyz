---
layout: page
title: About
permalink: /about/
---

This is a space to talk about our favorite videogames, trending ones, upcoming releases, and anything we might be playing in our spare time.

Collaborators:
<ul>
{% for member in site.data.collabs %}
  <li>
    <h4>{{ member.name }}</h4>
    <p>
      <strong>Nicknames:</strong>
      {% for nick in member.nicknames %}
        <span>{{ nick }}{% if forloop.last == false %},{% endif %}</span>
      {% endfor %}
    </p>
    <p>{{ member.description }}</p>
    <p>
      <strong>Favorite Old-School Games:</strong>
      {% for game in member.favorites.old-school %}
        <span>{{ game }}{% if forloop.last == false %},{% endif %}</span>
      {% endfor %}
    </p>
  </li>
{% endfor %}
</ul>

<!-- You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/) -->

<!-- You can find the source code for Minima at GitHub:
[jekyll][jekyll-organization] /
[minima](https://github.com/jekyll/minima)

You can find the source code for Jekyll at GitHub:
[jekyll][jekyll-organization] /
[jekyll](https://github.com/jekyll/jekyll)


[jekyll-organization]: https://github.com/jekyll -->


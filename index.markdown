---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<p>See all sache:</p>
<ul>
{% for category in site.categories %}
<li><a href="{{ site.url }}/jekyll/category/{{ category | first | url_encode }}/index.html">{{ category | first }}</a></li>
{% endfor %}
</ul>



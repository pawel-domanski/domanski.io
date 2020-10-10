---
layout: trzypoziomy
title: Moje Trzy Poziomy - Cele
permalink: /trzypoziomy
comments: false
image: assets/images/trzypoziomy_banner.png
imageshadow: true
---
{% for book in site.data.books %}
{% if book.read == true %}
* [{{book.author}}, {{book.title}}]({{ book.title | datapage_url: 'all-books' }})
{% endif %}
{% endfor %}
---
layout: portfolio
title: Personal Identity Guide
excerpt: Designing my personal identity guide
category: portfolio
src: /assets/images/logo.svg
img_style: 'width: 150px;'
---

{% for i in (1..13) %}
{% if i < 10 %}
    {% capture num %}0{{ i }}{% endcapture %}
{% else %}
    {% capture num %}{{ i }}{% endcapture %}
{% endif %}
{% capture url %}/assets/others/toughspirit-blog-files/portfolio/umsi/SI520/personal-identity/final-project-personal-identity-guide_Page_{{ num }}.png{% endcapture %}
{% if i > 1 %}<hr class='line'>{% endif %}
<a href="{{ url }}" target='_blank' class="no-decoration">
    <img src="{{ url }}">
</a>
{% endfor %}

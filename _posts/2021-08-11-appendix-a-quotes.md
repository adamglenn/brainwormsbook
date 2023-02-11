---
title: "Appenix A: Quotes"
author: Tao He
date: 2021-08-10
category: Jekyll
layout: post
published: false
---

{% assign category = "the-fruits-of-labor" %}

The Fruits of Labor
-------------

<ul>
  {% for pundit in site.data.quotes %}

    {% for quote in pundit.quotes %}

      {% for relatedTopic in quote.related-topics %}

        {% for topic in relatedTopic.topic %}
          {% if topic == category %}
            <li>
              <p>{{ quote.quote }}</p>
              <p>{{ pundit.name }}, <em>{{ quote.title }}{{ quote.journal }}</em>{% if quote.url %}<a href="{{ quote.url }}">Link</a>{% endif %}</p>
            </li>
          {% endif %}
        {% endfor %}

      {% endfor %}

    {% endfor %}

  {% endfor %}
</ul>

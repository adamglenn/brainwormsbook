---
title: Selected Bibliography
author: Tao He
date: 2021-08-10
category: Jekyll
layout: post
---

{% assign categoryArray = "the-american-right,economics,fascism,globalization,immigration,policy-solutions,political-philosophy,propaganda,racial-inequality,rising-inequality,us-foreign-policy,us-history,us-labor-history" | split: ',' %}

The American Right
-------------

<ul>
  {% for books in site.data.books %}

    {% for bookCategories in books.category %}

      {% if bookCategories == 'the-american-right' %}

        <li>
          <strong>{{ books.title }}</strong><br>
          {{ books.author }}
        </li>

      {% endif %}

    {% endfor %}

  {% endfor %}
</ul>

Economics
-------------

<ul>
  {% for books in site.data.books %}

    {% for bookCategories in books.category %}

      {% if bookCategories == 'economics' %}

        <li>
          <strong>{{ books.title }}</strong><br>
          {{ books.author }}
        </li>

      {% endif %}

    {% endfor %}

  {% endfor %}
</ul>

Fascism
-------------

<ul>
  {% for books in site.data.books %}

    {% for bookCategories in books.category %}

      {% if bookCategories == 'fascism' %}

        <li>
          <strong>{{ books.title }}</strong><br>
          {{ books.author }}
        </li>

      {% endif %}

    {% endfor %}

  {% endfor %}
</ul>

Globalization
-------------

<ul>
  {% for books in site.data.books %}

    {% for bookCategories in books.category %}

      {% if bookCategories == 'globalization' %}

        <li>
          <strong>{{ books.title }}</strong><br>
          {{ books.author }}
        </li>

      {% endif %}

    {% endfor %}

  {% endfor %}
</ul>

Immigration
-------------

<ul>
  {% for books in site.data.books %}

    {% for bookCategories in books.category %}

      {% if bookCategories == 'immigration' %}

        <li>
          <strong>{{ books.title }}</strong><br>
          {{ books.author }}
        </li>

      {% endif %}

    {% endfor %}

  {% endfor %}
</ul>

Policy Solutions
-------------

<ul>
  {% for books in site.data.books %}

    {% for bookCategories in books.category %}

      {% if bookCategories == 'policy-solutions' %}

        <li>
          <strong>{{ books.title }}</strong><br>
          {{ books.author }}
        </li>

      {% endif %}

    {% endfor %}

  {% endfor %}
</ul>

Political Philosophy
-------------

<ul>
  {% for books in site.data.books %}

    {% for bookCategories in books.category %}

      {% if bookCategories == 'political-philosophy' %}

        <li>
          <strong>{{ books.title }}</strong><br>
          {{ books.author }}
        </li>

      {% endif %}

    {% endfor %}

  {% endfor %}
</ul>

Propaganda
-------------

<ul>
  {% for books in site.data.books %}

    {% for bookCategories in books.category %}

      {% if bookCategories == 'propaganda' %}

        <li>
          <strong>{{ books.title }}</strong><br>
          {{ books.author }}
        </li>

      {% endif %}

    {% endfor %}

  {% endfor %}
</ul>

Racial Inequality
-------------

<ul>
  {% for books in site.data.books %}

    {% for bookCategories in books.category %}

      {% if bookCategories == 'racial-inequality' %}

        <li>
          <strong>{{ books.title }}</strong><br>
          {{ books.author }}
        </li>

      {% endif %}

    {% endfor %}

  {% endfor %}
</ul>

Rising Inequality
-------------

<ul>
  {% for books in site.data.books %}

    {% for bookCategories in books.category %}

      {% if bookCategories == 'rising-inequality' %}

        <li>
          <strong>{{ books.title }}</strong><br>
          {{ books.author }}
        </li>

      {% endif %}

    {% endfor %}

  {% endfor %}
</ul>

U.S. Foreign Policy
-------------

<ul>
  {% for books in site.data.books %}

    {% for bookCategories in books.category %}

      {% if bookCategories == 'us-foreign-policy' %}

        <li>
          <strong>{{ books.title }}</strong><br>
          {{ books.author }}
        </li>

      {% endif %}

    {% endfor %}

  {% endfor %}
</ul>

U.S. History
-------------

<ul>
  {% for books in site.data.books %}

    {% for bookCategories in books.category %}

      {% if bookCategories == 'us-history' %}

        <li>
          <strong>{{ books.title }}</strong><br>
          {{ books.author }}
        </li>

      {% endif %}

    {% endfor %}

  {% endfor %}
</ul>

U.S. Labor History
-------------

<ul>
  {% for books in site.data.books %}

    {% for bookCategories in books.category %}

      {% if bookCategories == 'us-labor-history' %}

        <li>
          <strong>{{ books.title }}</strong><br>
          {{ books.author }}
        </li>

      {% endif %}

    {% endfor %}

  {% endfor %}
</ul>

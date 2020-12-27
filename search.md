---
title: Search
layout: search
---

<form action="search" method="get">
    <input type="text" id="search-box" name="query" placeholder="Search Imagej">
    <input type="submit" value="search" onclick="displaySearchResults();">
</form>

<ul id="search-results" class="search"></ul>

<script>
    window.store = {
        {% for page in site.pages %}{% if page.category contains "admin" %}{% continue %}{% endif %}{% if page.title == "YOUR-POST-TITLE" %}{% continue %}{% endif %}
            "{{ page.url | slugify }}": {
                "title": "{{ page.title | xml_escape }}",
                "author": "{{ page.author | xml_escape }}",
                "category": "{{ page.category | xml_escape }}",
                "description": {{ page.description | strip_html | strip_newlines | jsonify }},
                "url": "{{ page.url | xml_escape }}"
            }
            {% unless forloop.last %}, {% endunless %}
        {% endfor %}
    };
</script>
{% include search-scripts %}

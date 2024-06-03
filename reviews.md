---
layout: default
title: "Reflections on Media"
permalink: /reviews/
---

# Reflections on Media

Some of my amateur reviews of movies / books. Added here at a time of boosted self confidence, might disappear soon as I start finding them embarrasing again.
{% assign reviews = site.reviews | sort: "date" | reverse   %}
{% for review in reviews %}
- **{{ review.date | date: "%B %d, %Y" }}**: [{{ review.title }}]({{ review.url }})
{% endfor %}
---
layout: page
title: Calendar
description: Listing of course modules and topics.
---


# Calendar

Below you'll find a calendar of topics. 

Note that linked materials for each topic are for class preparation. Please review these materials before class. (I am not afraid of awkward silences :)).

Feel free to bulk download all readings [here](https://github.com/kalexandriabond/cog_neuro_methods/tree/main/assets/readings/).

{% for module in site.modules %}
{{ module }}
{% endfor %}

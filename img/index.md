---
layout: default
---
{% for image in site.img %}
     {% if image.extname == 'jpg' %}
         <img src="{{ file.url }}" alt="" />
     {% endif %}
{% endfor %}
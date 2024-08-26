---
layout: page
permalink: /gallery
---
  
# Gallery

Welcome to our gallery! Here are some of our favorite images.

{% for image in site.data.images %}
![{{ image.description }}]({{ site.baseurl }}/assets/image/{{ image.filename }})
{% endfor %}
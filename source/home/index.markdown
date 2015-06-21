---
layout: page
#title: "Home"
#date: 2015-06-21 15:27
comments: true
sharing: false
footer: true
keywords: "Osteopaths Ringwood, Osteopaths Mitcham, Osteopaths Bayswater, Osteopaths Croydon"
carousel:
  - image: images/sliders1.jpg
  - image: images/sliders21.jpg
  - image: images/sliders31.jpg
  - image: images/sliders41.jpg
---
<div class="flexslider">
  <ul class="slides">
      {% for slides in page.carousel %}
      <li>
        <img center src="{{ slides.image }}" />
      </li>
      {% endfor %}
  </ul>
</div>




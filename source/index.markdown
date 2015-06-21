---
layout: page
#title: "Home"
#date: 2015-06-21 15:27
comments: true
sharing: false
footer: true
keywords: "Osteopaths Ringwood, Osteopaths Mitcham, Osteopaths Bayswater, Osteopaths Croydon"
carousel:
  - image: /images/sliders1.jpg
  - image: /images/sliders21.jpg
  - image: /images/sliders31.jpg
  - image: /images/sliders41.jpg
---
##Got Pain? Get Relief.
<!--
{% img center /images/were_the_best4-315x377.jpg %}
-->
<div class="center flexslider">
  <ul class="center slides">
      {% for slides in page.carousel %}
      <li>
        <img center src="{{ slides.image }}" />
      </li>
      {% endfor %}
  </ul>
</div>

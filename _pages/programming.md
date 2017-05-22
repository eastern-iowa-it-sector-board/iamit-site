---
layout: collection
title: Programming
icon: cog-mind.svg
hero-color: purple
video: DidWRWd-jds
permalink: /programming/
---
<section class="db center measure f4">
<p>All the programs, apps, and websites on your computer or your phone work by giving your computer (or phone) instructions about what to do and show based on what you click or type. People in programming/ development jobs use different kinds of software languages (like Spanish or French, but with funny names like Java and Ruby) to write the instructions (or scripts) that these apps and websites follow to make your computer or phone act how you want them to. They also make sure that the instructions written by other people are working like they are supposed to.</p>

<p>People in these jobs are often creative, good at solving problems, and can give good instructions.</p>
</section>
   <div class="cf pa2">
  {% assign info = 'programming' %}
  {% for info in site.programming %}
    {% include info-loop.html %}
{% endfor %}
 </div>
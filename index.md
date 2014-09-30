---
layout: default
title: TheHammar.com
description: Graphic Design by Mark Hammar
---
<div class="row"> 
  <div class="small-12 column">
    {% capture opener %}
{% include_relative front-page/opener.md %}
    {% endcapture %}
    {{ opener | markdownify }}
  </div>
</div>
<div class="row"> 
  <div class="small-12 medium-6 column">
    {% capture content %}
{% include_relative front-page/content.md %}
    {% endcapture %}
    {{ content | markdownify }}
  </div>
  <div class="small-12 medium-6 column">
    {% capture closer %}
{% include_relative front-page/closer.md %}
    {% endcapture %}
    {{ closer | markdownify }}
  </div>
</div>

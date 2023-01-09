---
layout: posts
permalink: /blog/
excerpt: "Slagbold blog er for os der gerne vil blive klogere på frisbeesporten, discgolf og ultimate."
title: Slagbolds blog
seo_title: "Blog om ketsjerspil og slagboldspil | Slagbold"
classes: wide
author_profile: true
gallery:
  - url: https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=78472
    rel: sponsored nofollow noopener
    image_path: https://www.partner-ads.com/dk/visbanner.php?partnerid=28187&bannerid=78472
    alt: Badmintonshoppen.dk
  - url: https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=79690
    rel: sponsored nofollow noopener
    image_path: https://www.padelshoppen.com/wp-content/uploads/2022/03/Padelshoppen-300-%C3%97-250.jpg
    alt: Padel Specialist
  - url: https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=98527
    rel: sponsored nofollow noopener
    image_path: /assets/images/ad/cuera-padel.jpg
    alt: Cuera Padel
---

{% assign site_posts = site.posts | sort: "last_modified_at" | reverse %}

{% if site_posts.size > 0 %}
<h2>Seneste opdateringer på Slagbolds blog</h2>
<div class="feature__wrapper">
  {% for post in site_posts limit:16 %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
{% endif %}

{% include gallery %}
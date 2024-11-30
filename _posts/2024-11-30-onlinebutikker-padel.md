---
layout: single
permalink: /padel/
title: &title "Alt om Padel"
excerpt: "Padel er en sjov og spændende sport, der involverer at spille på tværs af et net i et bur. Her dykker vi ned i alle detaljerne."
header:
  overlay_image: https://images.unsplash.com/photo-1526888935184-a82d2a4b7e67?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&h=630&w=1200&q=10
  caption: *title
author_profile: true
faq:
  - question: Hvad er forskellen på tennis og padel tennis?
    answer: I padel spiller I ofte fire sammen i en double. Du kan godt spille padel som single på særlige baner. I padel er der glasvægge rundt om banen, som giver rebounds, og derfor får du sikkert mere flow i spillet. Samtidig er det lidt lettere at slå og kontrollere bolden med et padelbat sammenlignet med en tennisketsjer.
  - question: Kan alle spille padel?
    answer: Ja. Alle kan spille padel. Padel kræver ikke store tekniske eller fysiske færdigheder for at få en god oplevelse af spillet. Det er meget lettere at lære end tennis, badminton og squash. Samtidig kan du blive ved med at lære nye ting, så det er også sjovt, når du bliver rigtig dygtig til at spille.
breadcrumbs: true
toc: false
gallery:
  - url: https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=87287
    rel: sponsored nofollow noopener
    image_path: https://www.partner-ads.com/dk/visbanner.php?partnerid=28187&bannerid=87287
    alt: Padel Specialist
    name: Padel Specialist
  - url: https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=79690
    rel: sponsored nofollow noopener
    image_path: https://www.padelshoppen.com/wp-content/uploads/2022/03/Padelshoppen-300-%C3%97-250.jpg
    alt: Padelshoppen
    name: Padelshoppen
  - url: https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=103340
    rel: sponsored nofollow noopener
    alt: Padellife
    name: Padellife
  - name: Padelrack
    url: https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=101434
    alt: Padelrack
---

{{ page.excerpt }}

{% include gallery %}

{% assign site_posts = site.posts | where: "category", "Padel" | where_exp: "post", "post.url != page.url" | sort: "date" %}

{% if site_posts.size > 0 %}
<div class="feature__wrapper">

## Artikler om padel
  {% for post in site_posts %}
    {% include archive-single.html type="grid" show_excerpt="false" %}
  {% endfor %}

</div>
{% endif %}

## Ofte stillede spørgsmål

{% include faq.html %}

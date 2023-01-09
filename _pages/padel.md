---
layout: single
permalink: /padel/
title: &title "Alt om Padel"
excerpt: "Padel er en sjov og spændende sport, der involverer at spille på tværs af et net i et bur. Her dykker vi ned i alle detaljerne."
header:
  overlay_image: https://images.unsplash.com/photo-1526888935184-a82d2a4b7e67?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&h=630&w=1200&q=10
  caption: *title
author_profile: true
toc: true
faq:
  - question: Hvad vil det sige at have en god kondition?
    answer: Du er i god kondition, når konditallet er tilstrækkelig højt. Din kondition varierer med alderen og for mænd og kvinder. Du kan kigge i vores [tabeller over kondital](/kondital/), hvis du gerne vil have vurderet dit.
  - question: Hvad er dårlig kondition?
    answer: Hvis konditallet er lavt ifølge de gængse [normer for kondital](/kondital/), så siger man, at du er i dårlig kondition. Konditionen afhænger især af alderen.
breadcrumbs: true
toc: false
gallery:
  - url: https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=87287
    rel: sponsored nofollow noopener
    image_path: https://www.partner-ads.com/dk/visbanner.php?partnerid=28187&bannerid=87287
    alt: Padel Specialist
  - url: https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=79690
    rel: sponsored nofollow noopener
    image_path: https://www.padelshoppen.com/wp-content/uploads/2022/03/Padelshoppen-300-%C3%97-250.jpg
    alt: Padel Specialist
  - url: https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=98527
    rel: sponsored nofollow noopener
    image_path: /assets/images/ad/cuera-padel.jpg
    alt: Cuera Padel
  - url: https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=97449
    rel: sponsored nofollow noopener
    image_path: /assets/images/ad/tempo-padel.jpg
    alt: Tempo Padel
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


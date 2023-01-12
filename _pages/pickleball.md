---
excerpt: Du kan bruge en pickleball til mange sjove aktiviteter. Her kommer
  mange forskellige forslag til, hvordan du kan spille pickleball.
last_modified_at: 2023-01-12T09:09:35+01:00
toc: false
layout: single
title: Pickleball
permalink: /pickleball/
header:
  overlay_image: https://images.unsplash.com/photo-1659318006095-4d44845f3a1b?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&h=630&w=1200&q=10
  caption: Pickleball
breadcrumbs: true
gallery:
  - url: https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=78472
    rel: sponsored nofollow noopener
    image_path: https://www.partner-ads.com/dk/visbanner.php?partnerid=28187&bannerid=78472
    alt: Badmintonshoppen.dk
    title: Badmintonshoppen.dk
  - url: https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=79690
    rel: sponsored nofollow noopener
    image_path: https://www.padelshoppen.com/wp-content/uploads/2022/03/Padelshoppen-300-%C3%97-250.jpg
    alt: Padel Specialist
    title: Padel Specialist
  - url: https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=98527
    rel: sponsored nofollow noopener
    image_path: /assets/images/ad/cuera-padel.jpg
    alt: Cuera Padel
    title: Cuera Padel
author_profile: true
faq:
  - question: Hvad betyder Pickleball?
    answer: Pickleball er en blanding mellem badminton, bordtennis og tennis. Der
      spilles på en badmintonbane med en pickleball plasticbold og et
      pickleballbat, som er noget større end et bordtennisbat. Nettet er i
      tennishøjde. Det kan spilles både indendørs og udendørs og som single og
      double.
  - question: Er Pickleball det samme som Padel?
    answer: Pickleball blev opfundet i USA i 1965. Du bruger et picklebat (også
      kaldet en padel), der er en mellemting mellem et bordtennis- og et
      padelbat. Bolden minder om bolden fra floorball og giver et langsommere
      opspring og derfor længere dueller.
---

{% include gallery %}

{% assign site_posts = site.posts | where: "category", "Pickleball" | where_exp: "post", "post.url != page.url" | sort: "date" %}

{% if site_posts.size > 0 %}
## Artikler om pickleball

<div class="feature__wrapper">
  {% for post in site_posts %}
    {% include archive-single.html type="grid" show_excerpt="false" %}
  {% endfor %}
</div>
{% endif %}

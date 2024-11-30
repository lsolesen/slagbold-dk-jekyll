---
excerpt: Badminton er en hurtig og spændende holdsport, hvor du spiller på tværs
  af et net med en ketsjer.
last_modified_at: 2023-01-12T09:03:54+01:00
toc: false
layout: single
title: Alt om badminton
permalink: /badminton/
header:
  overlay_image: https://images.unsplash.com/photo-1613918431703-aa50889e3be9?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&h=630&w=1200&q=10
  caption: Alt om badminton
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
  - url: https://www.partner-ads.com/dk/klikbanner.php?partnerid=28187&bannerid=111416
    rel: sponsored nofollow noopener
    image_path: https://www.partner-ads.com/dk/visbanner.php?partnerid=28187&bannerid=111411
    alt: Racketlife
    title: Racketlife
author_profile: true
faq:
  - question: Hvilket land stammer badminton fra?
    answer: Badminton stammer helt tilbage fra det gamle Grækenland. Badminton blev
      først udbredt i Østen, men britiske soldater tog sporten til
      Storbritannien i 1860'erne. Spillet fik sit navn efter at være blevet
      spillet på godset Badminton i Gloucestershire i England. Det
      internationale badmintonforbund blev stiftet i 1934, men først i 1992, ved
      legene i Barcelona, kom sporten på det olympiske program.
  - question: Hvorfor hedder det badminton?
    answer: Badminton blev spillet på et gods i Gloucestershire i det sydvestlige
      England til et selskab afholdt af hertugen af Beaufort i 1871. Godset hed
      Badminton, og derefter kom spillet til at hedde badminton.
---

{% include gallery %}

{% assign site_posts = site.posts | where: "category", "Badminton" | where_exp: "post", "post.url != page.url" | sort: "date" %}

{% if site_posts.size > 0 %}
## Artikler om badminton

<div class="feature__wrapper">
  {% for post in site_posts %}
    {% include archive-single.html type="grid" show_excerpt="false" %}
  {% endfor %}
</div>
{% endif %}

---
layout: home
title: CS 4641
nav_exclude: true
seo:
  type: Course
  name: Just the Class
---

# {{ site.tagline }}
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

- Location: Clough Commons 144 (Lectures will also be broadcast and recorded using BlueJeans [https://primetime.bluejeans.com/a2m/live-event/dcwjksqr](https://primetime.bluejeans.com/a2m/live-event/dcwjksqr))
- Please carefully read through the course details and FAQ linked to the left.
- A tentative plan for the schedule (topics, deadlines, etc.) is available [here](https://docs.google.com/spreadsheets/d/1aqDI8Fpne6ZLCV2V0V-E7ybMNKcpVzqLJJHoO3Pj5Wg/edit?usp=sharing)
- [Piazza](https://piazza.com/class/krjfpfjr3es38i)
- [Gradescope](https://www.gradescope.com/courses/281746)

{% for module in site.modules %}
{{ module }}
{% endfor %}

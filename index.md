---
layout: home
title: Home
nav_order: 0
description: >-
    Course website for MEC ENG 103 Spring 2026
---
<!-- <div class="parallax-window" data-parallax="scroll" data-image-src="/assets/background.png" data-speed="0.1">/div> -->
# ME 103 | Experimentation and Measurements
{: .mb-2 }
Spring 2024 | Instructor: Professor George Anwar
{: .mb-0 .fs-6 .text-grey-dk-200 }

<hr>

{% if site.announcements %}
{{ site.announcements.last }}
<a href="{{ site.baseurl }}/announcements" class="btn btn-outline fs-3">
  All Announcements
</a>
{% endif %}

# Course Calendar

#### All lecture videos can be found on bCourses.

{% for module in site.modules %}
{{ module }}
{% endfor %}

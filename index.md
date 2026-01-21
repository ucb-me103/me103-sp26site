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
## Spring 2026

<div class="instructor-card">
  <img src="{{ site.baseurl }}assets/staff_pics/george_anwar.jpg"
       alt="Professor George Anwar"
       class="instructor-photo"/>

  <div class="instructor-info">
    <p class="name"><strong>George Anwar</strong></p>
    <p class="email">ganwar@</p>
    <p class="role">Professor</p>
    <p class="pronouns">he/him</p>
  </div>
</div>

<!-- Instructor: Professor George Anwar
{: .mb-0 .fs-6 .text-grey-dk-200 } -->

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

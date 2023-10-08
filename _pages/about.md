---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>
<!-- <br> -->

{% include_relative include/intro.md %}

<!-- # News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->


{% include_relative include/pub.md %}
{% include_relative include/experience.md %}
{% include_relative include/award.md %}
{% include_relative include/service.md %}

<div style="display:inline-block; margin: 0 auto;">
  <script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=968f9b&w=253&t=n&d=LNDyveCbdQ7qI6V8UUwCmKVGKchQrNhLyKybxjZFctc&co=fcfcfc&cmn=51c451&cmo=f286ef&ct=0f0e0e'></script>
</div>







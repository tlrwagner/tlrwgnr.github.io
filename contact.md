---
layout: page
title: Contact Me
permalink: /contact/
---
{% include social_media_icons.html %}

Here are some different ways you can contact me.

<!-- GitHub: -->
<!-- {% include icon-github.html username="tlrwgnr" %}
LinkedIn: [Joshua T Wagner](https://www.linkedin.com/in/jtwagner/)<br>
Email: [{{ site.email }}](mailto:{{ site.email }}) -->

{% if site.github_username %}
  <li>
    <a href="https://github.com/{{ site.github_username }}">
      <i class="fa fa-github"></i> GitHub
    </a>
  </li>
{% endif %}
{% if site.linkedin_username %}
  <li>
    <a href="https://linkedin.com/in/{{ site.linkedin_username }}">
      <i class="fa fa-linkedin"></i> LinkedIn
    </a>
  </li>
{% endif %}
{% if site.twitter_username %}
  <li>
    <a href="https://twitter.com/{{ site.twitter_username }}">
      <i class="fa fa-twitter"></i> Twitter
    </a>
  </li>
{% endif %}
{% if site.google_plus_username %}
  <li>
    <a href="https://plus.google.com/{{ site.google_plus_username }}">
      <i class="fa fa-google-plus"></i> Google+
    </a>
  </li>
{% endif %}
{% if site.facebook_username %}
  <li>
    <a href="https://www.facebook.com/{{ site.facebook_username }}">
      <i class="fa fa-facebook"></i> Facebook
    </a>
  </li>
{% endif %}
<!-- Dribble portion -->
{% if site.dribbble_username %}
  <li>
  <a href="https://dribbble.com/{{ site.dribbble_username }}" class="icon">
      <i class="fa fa-dribbble"></i> Dribbble
    </a>
  </li>
{% endif %}

---
layout: page
title: "Contact"
description: "Have questions? I have answers (maybe)."
image: "/assets/img/contact.jpg"
permalink: /contact/
---

If you have any questions, comments, or would just like to say hello in general, please don't hesitate to <span class="svg-icon icon-envelope-o svg-baseline" aria-hidden="true"><svg><use xlink:href="/assets/icons/icons.min.svg#icon-envelope-o"></use></svg></span> e-mail me at *denishazamukeATgmailDOTcom*. You can also contact me through these following social networks and I'll be sure to respond in a timely manner!

<ul class="social-links">
  {% if site.author.twitter %}
  <li>
    <a rel="me" href="//twitter.com/azamukedenish1">
      <span class="svg-icon svg-baseline" aria-hidden="true">
        <svg><use xlink:href="/assets/icons/icons.min.svg#icon-twitter"></use></svg>
      </span><br><span class="label">Twitter</span>
    </a>
  </li>
  {% endif %}
  {% if site.author.facebook %}
  <li>
    <a rel="me" href="//www.facebook.com/Azamuke-Denish-111776309235790/?ref=page_internal">
      <span class="svg-icon svg-baseline" aria-hidden="true">
        <svg><use xlink:href="/assets/icons/icons.min.svg#icon-facebook"></use></svg>
      </span><br><span class="label">Facebook</span>
    </a>
  </li>
  <li>
     <a rel="me" href="//instagram.com/azamukedenish">
      <span class="svg-icon svg-baseline" aria-hidden="true">
        <svg><use xlink:href="/assets/icons/icons.min.svg#icon-instagram"></use></svg>
      </span><br><span class="label">Instagram</span>
    </a>
  </li>
  <li>
    <a rel="me" href="//github.com/azamukedenish">
      <span class="svg-icon svg-baseline" aria-hidden="true">
        <svg><use xlink:href="/assets/icons/icons.min.svg#icon-github"></use></svg>
      </span><br><span class="label">GitHub</span>
    </a>
  </li>
  {% endif %}
</ul>

<p class="pgp-key">
  <a href="//keybase.io/stevebaros/key.asc">
    PGP(MY Fingerprint): <code>E37D 2E73 91B1 050E F3E0 8BB7 7496 6850 BED3 0C3A</code>
  </a>
</p>

{% include google_maps.html %}

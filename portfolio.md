---
layout: page
title: Portfolio
permalink: /Portfolio/
---
  <ul>
    {% for project in site.projects %}
      <li>

        <h2>
          <a class="post-link" href="{{ project.url | prepend: site.baseurl }}">{{ project.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>

![Bet Me login page](/assets/Bet-Me-login.png)
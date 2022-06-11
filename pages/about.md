---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hey, I'm  **{{ site.author.name }}** :wave:,<br>
This site acts as both a portfolio and site to host my writing. I don't really post on here too much, but when I do, it'll mostly be programming related,
CTF related, or philosophy related. If you want to contact me, you can try to find my email, or just contact me on Discord at: Maple#0929

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
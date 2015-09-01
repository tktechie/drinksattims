---
layout: page
title: D&D Sessions
---

---
<br>


- Eladrin Warlock, Chris T.
- Shadar-Kai Shaman, Zach DeC.
- Wilden Battlemind, Michaela F.
- Half-Elf Ranger, Raleigh
- Dungeon Master, Tim K 2


{% for dnd in site.dnd %}
<p>
  <a class="post-link" href="{{ dnd.url | prepend: site.baseurl }}">{{ dnd.title }}</a>
  <span class="post-meta">{{ dnd.session-date | date: "%b %-d, %Y" }}</span>
</p> 
{% endfor %}
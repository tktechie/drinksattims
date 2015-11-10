---
layout: page
title: D&D Sessions
---

---
<br>


- Eladrin Warlock, Taracob
- Shadar-Kai Shaman, Namir
- Wilden Battlemind, Teldorath
- Half-Elf Ranger, Lady Moonshine of Doubtfire
- Dungeon Master, Me


{% for dnd in site.dnd %}
<p>
  <a class="post-link" href="{{ dnd.url | prepend: site.baseurl }}">{{ dnd.title }}</a>
  <span class="post-meta">{{ dnd.session-date | date: "%b %-d, %Y" }}</span>
</p> 
{% endfor %}
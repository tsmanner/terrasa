---
title: Caltrop Bloodless
subtitle: Ryan
---

{% assign entity = site.data.dnd.common.players | where: "name", page.title | first %}
<table>
  {% include dnd/entity-table-head.html %}
  {% include dnd/entity-row.html entity=entity %}
</table>

Former crew for captain [Izhi](../npcs/Izhi.md), a regionally infamous pirate.  Cheated Caltrop out of his share of "the profits" and he wants his due.

Died in an unfortunate run-in with a <a href="https://www.dndbeyond.com/monsters/{{ 'Rug of Smothering' | downcase | split: ' ' | join: '-' }}">Rug of Smothering</a> at a jewelry shop in Yalaqta.  Rest in peace, Caltrop Bloodless.

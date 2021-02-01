---
title: Caltrop Bloodless
subtitle: Ryan
---

{% assign entity = site.data.common.players | where: "name", page.title | first %}
<table>
  <thead><tr><th>Name</th><th>Init</th><th>AC</th><th>HP</th><th>STR</th><th>DEX</th><th>CON</th><th>INT</th><th>WIS</th><th>CHA</th></tr></thead>
  {% include common/entity.html entity=entity %}
</table>

Former crew for captain [Izhi](../npcs/Izhi.md), a regionally infamous pirate.  Cheated Caltrop out of his share of "the profits" and he wants his due.


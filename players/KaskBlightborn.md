---
title: Kask Blightborn
subtitle: Ryan
---

{% assign entity = site.data.dnd.common.players | where: "name", page.title | first %}
<table>
  {% include dnd/entity-table-head.html %}
  {% include dnd/entity-row.html entity=entity %}
</table>



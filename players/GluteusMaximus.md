---
title: Gluteus Maximus
subtitle: Kurt
---

{% assign entity = site.data.common.players | where: "name", page.title | first %}
<table>
  {% include dnd/encounter-table-head.html %}
  {% include dnd/entity-row.html entity=entity %}
</table>

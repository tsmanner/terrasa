---
title: Brother Gromag
subtitle: Nick
---

{% assign entity = site.data.common.players | where: "name", page.title | first %}
<table>
  {% include dnd/encounter-table-head.html %}
  {% include dnd/entity-row.html entity=entity %}
</table>

| Orange | Green | Blue |
|--------|-------|------|
|    7   |   2   |   1  |
|    9   |   1   |   8  |
|    1   |   8   |   5  |

![Sudoku](assets/img/gromag-sudoku.png)

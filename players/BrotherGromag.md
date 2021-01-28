---
title: Brother Gromag
subtitle: Nick
---

{% assign player = site.data.common.players | where: "name", page.title | first %}

<div id="myEntity" class="entity hidden">
  <var class="proficiency" data-value="2">{% player.proficiency %}</var>
  <var class="ability str" data-value="8">{% player.str %}</var>
  <var class="ability dex" data-value="15">{% player.dex %}</var>
  <var class="ability con" data-value="10">{% player.con %}</var>
  <var class="ability int" data-value="14">{% player.int %}</var>
  <var class="ability wis" data-value="12">{% player.wis %}</var>
  <var class="ability cha" data-value="16">{% player.cha %}</var>
  <var class="bonus int" data-value="proficiency"></var>
  <var class="bonus dex" data-value="proficiency"></var>
  <var class="bonus initiative" data-value="chaMod"></var>
</div>

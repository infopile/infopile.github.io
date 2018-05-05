---
title: Lab Members
layout: single
permalink: /people/
collection: people
entries_layout: grid
classes: wide
---

The lab is always looking for prospective members, if you're interested in a PhD or a Post-Doc position, please contact [Alexey
Nesvizhskii](mailto:nesvi@med.umich.edu).

<h2>Current</h2>
<table>
{% for member in site.data.members.current %}
  <tr>
    <td style="width:100px;">
    <img src='{{ member.photo }}'/>
    </td>
    <td>
    {{ member.name }}
    </td>
  </tr>
{% endfor %}
</table>

<h2>Past</h2>
<ul>
{% for member in site.data.members.past %}
  <li>
    {{ member.name }}
  </li>
{% endfor %}
</ul>
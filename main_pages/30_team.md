---
layout: page
title: Team
permalink: team/
include_in_menu: true
---

<table>
{% assign rows = site.data.team.size | divided_by: 2.0 | ceil %}
{% for i in (1..rows) %}
<tr>
{% assign offset = forloop.index0 | times: 2 %}
{% for member in site.data.team limit:2 offset:offset %}
<td><img src="{{ member.picture }}" style="object-fit:contain; width:150px; height:150px;"/></td> <td> <a href="{{ member.website }}"> {{ member.name }} </a> <br> {{ member.position }} </td>
{% endfor %}
</tr>
<tr>
</tr>
{% endfor %}
</table>

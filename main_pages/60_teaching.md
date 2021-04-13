---
layout: page
title: Teaching
permalink: teaching/
include_in_menu: true
---

<table>
{% for course in site.data.teaching%}
<tr>
<td colspan=2><b style="font-size:20px"><a href="{{course.link}}">{{course.title}}</a></b></td>
</tr>
<tr>
<td>Level:</td><td>{{course.level}}</td>
</tr>
<tr>
<td>Teacher:</td><td>{{course.teacher}}</td>
</tr>
<tr style="height:40px">
</tr>
{% endfor %}
</table>

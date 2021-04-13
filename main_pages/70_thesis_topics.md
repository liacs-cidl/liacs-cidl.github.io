---
layout: page
title: Master thesis topics
permalink: thesis_topics/
include_in_menu: true
---

<table>
{% for topic in site.data.thesistopics%}
<tr>
<td colspan=2><b style="font-size:20px">{{topic.title}}</b></td>
</tr>
<tr>
<td>Supervisor:</td><td>{{topic.supervisor}}</td>
</tr>
<tr>
<td style="vertical-align:top">Summary:</td><td>{{topic.summary}}</td>
</tr>
<tr style="height:40px">
</tr>
{% endfor %}
</table>

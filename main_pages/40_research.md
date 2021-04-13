---
layout: page
title: Research
permalink: research/
include_in_menu: true
---

<table>
{% for topic in site.data.research%}
<tr>
<td style="width:150px; vertical-align:top"><img src="{{ topic.picture }}" style="object-fit:cover; width:150px; height:150px;"/></td> <td style="padding-left:10px">
<b style="font-size:20px">{% if topic.link And topic.link != "" And topic.link != nil %}<a href="{{topic.link}}"> {{topic.topic}}</a> {% else %} {{topic.topic}} {% endif %}</b>
{% if topic.people And topic.people != "" And topic.people != nil %} <br>{{topic.people}} {% endif %}
<br><br>
{{ topic.description }}

</td>
</tr>
<tr style="height:40px">
</tr>
{% endfor %}
</table>

# Introduction

This is a group project about how to work on github as a team.
 
## Code

## Contributors
{% for stu in site.stu %}
  <li><img src="{{ stu.image }}">@<a herf="https://github.com/{{stu.user}}">{{ stu.name }}</a>({{ stu.name }})<ul><p>{{ stu.content | markdownify }}</p></ul></li>
{% endfor %}

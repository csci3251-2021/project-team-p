# Introduction

This is a group project about how to work on github as a team.
 
## Code

## Contributors
{% for stu in site.stu %}
  >><img src="{{ stu.image }}">@<a herf="https://github.com/{{stu.user}}">{{ stu.name }}</a>({{ stu.name }})
  >><p>{{ stu.content | markdownify }}</p>
{% endfor %}

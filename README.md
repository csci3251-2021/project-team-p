# Introduction

This is a group project about how to work on github as a team.
 
## Code

## Contributors
{% for stu in site.stu %}
  <h2>{{ stu.user }} - {{ stu.name }}</h2>
  <p>{{ stu.content | markdownify }}</p>
{% endfor %}

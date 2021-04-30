# Introduction
What our team should do:
1. Task 1 (done)
2. Task 2 (done)
3. Task 3 (in progress)
4. Task 4
5. Task 5
6. Task 6
7. Task 7
8. Task 8

This is a group project about how to work on github as a team.

# Code

# Contributors
{% for stu in site.stu %}
  <li><img src="{{ stu.image }}">@<a herf="https://github.com/{{stu.user}}">{{ stu.name }}</a>({{ stu.name }})<ul><p>{{ stu.content | markdownify }}</p></ul></li>
{% endfor %}

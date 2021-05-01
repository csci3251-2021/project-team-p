# Introduction
What our team should do:
- [x] Task 1: Create new issues
- [x] Task 2: Create a new project board and set up automations
- [x] Task 3: Set up readme.md
- [ ] Task 4: Edit contributors in readme.md
- [ ] Task 5: Check previous tasks
- [ ] Task 6: Write C code
- [ ] Task 7: Get a status badge
- [ ] Task 8: Promote the repository

This is a group project about how to work on github as a team.


# Code

# Contributors
{% for stu in site.stu %}
  <li><img src="{{ stu.image }}">@<a herf="https://github.com/{{stu.user}}">{{ stu.name }}</a>({{ stu.name }})<ul><p>{{ stu.content | markdownify }}</p></ul></li>
{% endfor %}

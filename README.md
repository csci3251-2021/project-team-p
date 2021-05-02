# Introduction
What our team should do:
- [x] Task 1: Create new issues
- [x] Task 2: Create a new project board and set up automations
- [x] Task 3: Set up readme.md
- [x] Task 4: Edit contributors in readme.md
- [x] Task 5: Check previous tasks
- [x] Task 6: Write C code
- [ ] Task 7: Get a status badge
- [x] Task 8: Promote the repository

This is a group project about how to work on github as a team.


# Code

# Contributors
{% for stu in site.stu %}

  - <img src="{{ stu.image }}" width="60" height="60" /><a href="https://github.com/{{ stu.user }}">@{{ stu.user }}</a>({{ stu.name }})
  - {{ stu.content | markdownify }}

{% endfor %}

---
Last updated: {{ site.time }}

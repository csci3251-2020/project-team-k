# Introduction

- Task 1: Starting issues

- Task 2: Project board

- Task 3: Set up readme.md

- Task 4: Show your team to the Internet

- Task 5: Keep checking

- Task 6: Write C code

- Task 7: Get a status badge

- Task 8: Promote your repo

# Code

```c
{% include_relative code.c %}
```
![workflowOfTeamK](https://github.com/csci3251-2020/project-team-k/workflows/workflowOfTeamK/badge.svg)

# Contributors

{% for member in site.stu %}
-   ![Image]({{member.image}})@{{member.user}}({{member.name}})
    -   {{member.content | markdownify}}
{% endfor %}
 
# Last Update

Last updated : site.time 

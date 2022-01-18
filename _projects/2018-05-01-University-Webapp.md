---
layout: project
title: "University Webapp"
organization: "University of Salahuddin-Erbil, Software Engineering"
date: 2018-05-01
background: "/img/projects/library.jpg"
category: application # application, webapp, website,
myrole: "Developer & Team Leader"
source: ""
technologies:
  - fa: true
    icon: "fab fa-java"
    name: "Java"
  - fa: ture
    icon: "far fa-file-alt"
    name: "File based database"
  - fa: ture
    icon: "fas fa-project-diagram"
    name: "Netwrorking"
---

## Highlights

- **Project Title:** _{{page.title}}_
- **Organization:** _{{page.organization}}_
- **My Role:** _{{page.myrole}}_
- **Tools:** _{% for item in page.technologies %}{{ item.name }}&nbsp;&middot;&nbsp;{% endfor %}_
- **Completed Date**: _{{page.date  | date: '%B-%Y'}}_{% if page.source %}
- **Source**: [{{page.source}}]({{page.source}}){% endif %}

## Project Description

May-2018 Supervise a project for university staff management system
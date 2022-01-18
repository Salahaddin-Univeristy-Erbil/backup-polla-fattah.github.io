---
layout: project
title: "Web App"
organization: "University of Salahuddin-Erbil, Software Engineering"
date: 2004-09-01
background: "/img/projects/library.jpg"
category: application # application, webapp, website,
myrole: "Developer & Team Leader"
source: ""
technologies:
  - fa: true
    icon: "fab fa-php"
    name: "PHP"
  - fa: true
    icon: "fab fa-html5"
    name: "HTML"
  - fa: true
    icon: "fab fa-css3-alt"
    name: "CSS"
  - fa: ture
    icon: "fas fa-database"
    name: "MySQL"
  - fa: ture
    icon: "fas fa-server"
    name: "Apache Web Server"
---

## Highlights

- **Project Title:** _{{page.title}}_
- **Organization:** _{{page.organization}}_
- **My Role:** _{{page.myrole}}_
- **Tools:** _{% for item in page.technologies %}{{ item.name }}&nbsp;&middot;&nbsp;{% endfor %}_
- **Completed Date**: _{{page.date  | date: '%B-%Y'}}_{% if page.source %}
- **Source**: [{{page.source}}]({{page.source}}){% endif %}

## Project Description

Nov-2004 Design and implement a web based application for Software Dept. at Salahaddin University.
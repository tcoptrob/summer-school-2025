---
title: Organizers
---
# *Hello* 👋 from our team!

These individuals worked behind the scenes to make the Optimization for Robotics Summer School a reality!

## Organizers
{% for person in site.data.team.organizers %}
{% include team_person person = person %}
{% endfor %}

## Featured Speakers
{% for person in site.data.team.speakers %}
{% include team_person person = person %}
{% endfor %}
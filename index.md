---
layout: default
title: FDAT085
sidebar: true
---

# Frontiers in Security Research (FDAT085)

*PhD course for Chalmers/Gothenburg University, taking place at the Johanneberg campus. Lecturer: [Steven Van Acker](http://singularity.be/)*

In this course, we study advanced security topics by reading state-of-the-art
papers from top conferences in the field. Each student chooses relevant papers
for a specific topic in the beginning of the course and presents it at a
seminar. Each student also hands in a written report containing a summary of
his/her topic and an in-depth review of the selected papers, pros and cons of
the taken approach, and how the paper relates to other papers in the area.
These reports are then peer-reviewed by the other students in the course.

## Course schedule

This schedule can also be found in [the course's Google calendar](https://calendar.google.com/calendar/embed?src=uug7eb9ur7818nurkcsh6r8boc%40group.calendar.google.com&ctz=Europe/Brussels).
<a href="https://calendar.google.com/calendar/ical/uug7eb9ur7818nurkcsh6r8boc%40group.calendar.google.com/public/basic.ics"><img src='https://calendar.google.com/googlecalendar/images/ical.gif'></a>

<table class='smalltext nowrap'>
<thead><tr><th>Date</th><th>Room</th><th>Presenter</th><th>Topic</th></tr></thead>
<tbody>
{% assign nodes = site.pages | sort: 'date' %}
{% for node in nodes %}
{% if node.layout == "student" %}
<tr><td>{{ node.date |  date: "%a. %d %B %Y" }}, {{node.time}}</td><td>{{ node.room }}</td><td>{{ node.author }}</td><td><a href="{{ site.baseurl }}{{node.url}}">{{ node.title }}</a></td></tr>
{% endif %}
{% endfor %}
</tbody>
</table>


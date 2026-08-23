---
layout: page
permalink: /talk/
title: talks
description: Here you may find slides and videos from some talks I have presented. A complete list of all talks may be found in my CV.
nav: true
---
<div class="news">
  {% if site.talks %}
    <div class="table-responsive">
      <table class="table table-sm table-borderless">
        <caption class="sr-only">Selected talks, presentation dates, and locations</caption>
        <thead class="sr-only">
          <tr>
            <th scope="col">Date</th>
            <th scope="col">Talk</th>
            <th scope="col">Place</th>
          </tr>
        </thead>
        <tbody>
          {% assign talks = site.talks | sort: "date" | reverse %}
          {% for item in talks %}
            <tr>
              <th scope="row">{{ item.date | date: "%b %-d, %Y" }}</th>
              <td>
                {{ item.content | remove: '<p>' | remove: '</p>' | emojify }}
              </td>
              <td>
                {% if item.place %}
                  <span class="talks-place">{{ item.place }}</span>
                {% endif %}
              </td>
            </tr>
          {% endfor %}
        </tbody>
      </table>
    </div>
  {% else %}
    <p>No talks so far...</p>
  {% endif %}
</div>

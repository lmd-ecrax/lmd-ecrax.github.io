---
layout: home
title: "LMD Early Career Researchers' Assembly X"
---

<div class="big-title">LMD Early Career Researchers' Assembly X</div>

<div class="hline"></div>

{% assign upcoming = site.data.meetings | sort: "date" | first %}

<div class="upcoming">
    <div class="upcoming-title">Next Meeting!</div>
    Date: {{ upcoming.date }}<br>
    Time: {{ upcoming.time }}
</div>



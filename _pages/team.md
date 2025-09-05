---
title: "AMAAI Lab - Team"
layout: gridlay
excerpt: "AMAAI Lab: Team members"
sitemap: false
permalink: /team/
---

# Group Members

 **We are looking for new PhD students, Postdocs, and Master students to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/vacancies) **!**

Jump to [Principal Investigator](#principal-investigator), [Postdoctoral fellows](#postdoctoral-fellows), [PhD students](#phd-students), [MSc students](#msc-students), [Research Assistants](#research-assistants).

---

## Principal Investigator
<div class="row">
{% for member in site.data.team_pi %}
<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="15%" style="float: left" />
  <h4 style="display: inline-flex; align-items: center; gap: 6px;">
    {{ member.name }}
    {% if member.homepage %}
      <a href="{{ member.homepage }}" target="_blank" style="color: #1E90FF; text-decoration: none;">
        <i class="fa fa-link" style="font-size: 0.8em; color: #1E90FF;"></i>
      </a>
    {% endif %}
  </h4>
  <i>{{ member.info }}</i>
  <p>{{ member.bio }}</p>
</div>
{% endfor %}
</div>

---

## Postdoctoral fellows
<div class="row">
{% for member in site.data.team_postdoc %}
<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="15%" style="float: left" />
  <h4 style="display: inline-flex; align-items: center; gap: 6px;">
    {{ member.name }}
    {% if member.homepage %}
      <a href="{{ member.homepage }}" target="_blank" style="color: #1E90FF; text-decoration: none;">
        <i class="fa fa-link" style="font-size: 0.8em; color: #1E90FF;"></i>
      </a>
    {% endif %}
  </h4>
  <p>{{ member.bio }}</p>
</div>
{% endfor %}
</div>

---

## PhD students
<div class="row">
{% for member in site.data.team_phd %}
<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="15%" style="float: left" />
  <h4 style="display: inline-flex; align-items: center; gap: 6px;">
    {{ member.name }}
    {% if member.homepage %}
      <a href="{{ member.homepage }}" target="_blank" style="color: #1E90FF; text-decoration: none;">
        <i class="fa fa-link" style="font-size: 0.8em; color: #1E90FF;"></i>
      </a>
    {% endif %}
  </h4>
  <p>{{ member.bio }}</p>
</div>
{% endfor %}
</div>

---

## MSc students
<div class="row">
{% for member in site.data.team_msc %}
<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="15%" style="float: left" />
  <h4 style="display: inline-flex; align-items: center; gap: 6px;">
    {{ member.name }}
    {% if member.homepage %}
      <a href="{{ member.homepage }}" target="_blank" style="color: #1E90FF; text-decoration: none;">
        <i class="fa fa-link" style="font-size: 0.8em; color: #1E90FF;"></i>
      </a>
    {% endif %}
  </h4>
  <p>{{ member.bio }}</p>
</div>
{% endfor %}
</div>

---

## Research Assistants
<div class="row">
{% for member in site.data.team_ra %}
<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="15%" style="float: left" />
  <h4 style="display: inline-flex; align-items: center; gap: 6px;">
    {{ member.name }}
    {% if member.homepage %}
      <a href="{{ member.homepage }}" target="_blank" style="color: #1E90FF; text-decoration: none;">
        <i class="fa fa-link" style="font-size: 0.8em; color: #1E90FF;"></i>
      </a>
    {% endif %}
  </h4>
  <p>{{ member.bio }}</p>
</div>
{% endfor %}
</div>

---

## Graduated PhD students
<div class="row">
{% for member in site.data.team_grad_phd %}
<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="15%" style="float: left" />
  <h4 style="display: inline-flex; align-items: center; gap: 6px;">
    {{ member.name }}
    {% if member.homepage %}
      <a href="{{ member.homepage }}" target="_blank" style="color: #1E90FF; text-decoration: none;">
        <i class="fa fa-link" style="font-size: 0.8em; color: #1E90FF;"></i>
      </a>
    {% endif %}
  </h4>
  <p>{{ member.bio }}</p>
</div>
{% endfor %}
</div>

---

## Former members (research staff)
<div class="row">
{% for member in site.data.team_former_member %}
<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="15%" style="float: left" />
  <h4 style="display: inline-flex; align-items: center; gap: 6px;">
    {{ member.name }}
    {% if member.homepage %}
      <a href="{{ member.homepage }}" target="_blank" style="color: #1E90FF; text-decoration: none;">
        <i class="fa fa-link" style="font-size: 0.8em; color: #1E90FF;"></i>
      </a>
    {% endif %}
  </h4>
  <p>{{ member.bio }}</p>
</div>
{% endfor %}
</div>

---

## Graduated Masters in Engineering students
<div class="row">
{% for member in site.data.team_grad_msc %}
<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="15%" style="float: left" />
  <h4 style="display: inline-flex; align-items: center; gap: 6px;">
    {{ member.name }}
    {% if member.homepage %}
      <a href="{{ member.homepage }}" target="_blank" style="color: #1E90FF; text-decoration: none;">
        <i class="fa fa-link" style="font-size: 0.8em; color: #1E90FF;"></i>
      </a>
    {% endif %}
  </h4>
  <p>{{ member.bio }}</p>
</div>
{% endfor %}
</div>

---

## Former interns / visiting PhD students
<div class="row">
{% for member in site.data.team_former_intern %}
<div class="col-sm-12 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="15%" style="float: left" />
  <h4 style="display: inline-flex; align-items: center; gap: 6px;">
    {{ member.name }}
    {% if member.homepage %}
      <a href="{{ member.homepage }}" target="_blank" style="color: #1E90FF; text-decoration: none;">
        <i class="fa fa-link" style="font-size: 0.8em; color: #1E90FF;"></i>
      </a>
    {% endif %}
  </h4>
  <p>{{ member.bio }}</p>
</div>
{% endfor %}
</div>

---

## Selected SUTD UROP student collaborators
<ul>
{% for member in site.data.team_collab %}
<li>{{ member.name }}</li>
{% endfor %}
</ul>


<br><br>


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

## Principal Investigator
{% assign number_printed = 0 %}
{% for member in site.data.team_pi %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

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
  <i>{{ member.info }} <!--<br>email: <{{ member.email }}></i> -->
  <p>{{ member.bio }}</p>
  
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Postdoctoral fellows
{% assign number_printed = 0 %}
{% for member in site.data.team_postdoc %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

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

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}



## PhD students
{% assign number_printed = 0 %}
{% for member in site.data.team_phd %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

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

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## MSc students
{% assign number_printed = 0 %}
{% for member in site.data.team_msc %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

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

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Research Assistants
{% assign number_printed = 0 %}
{% for member in site.data.team_ra %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

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

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}



## Graduated PhD students
{% assign number_printed = 0 %}
{% for member in site.data.team_grad_phd %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

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

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Former members (research staff)
{% assign number_printed = 0 %}
{% for member in site.data.team_former_member %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

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

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Graduated Masters in Engineering students
{% assign number_printed = 0 %}
{% for member in site.data.team_grad_msc %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

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

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Former interns / visiting PhD students
{% assign number_printed = 0 %}
{% for member in site.data.team_former_intern %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

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

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

## Selected SUTD UROP student collaborators
<ul>
{% for member in site.data.team_collab %}
<li>{{ member.name }}</li>
{% endfor %}
</ul>


<br><br>


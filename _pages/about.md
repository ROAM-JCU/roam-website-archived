---
layout: page
title: About Us
permalink: /about/
---

ROAM is the research of animal movement group at James Cook University. Our group is made up of people across diverse disciplines, academic qualifications, gender, cultural backgrounds, and expertise. We are interested in a wide variety of animal movement topics in a manifold of ecosystems and taxa, including crustaceans, fish, birds, mammals, and reptiles.

ROAM was founded and is currently led by Kyana Pike and Emily Webster, with the invigorating collaboration of ROAM members.

We meet every second Tuesday at noon using a mixed virtual and in-person format.


<h1>Who we are</h1>

<div>
  {% for member in site.data.members.members %}
  <div style="display: flex;
              flex-wrap: wrap;
              padding: 20px">
    <div style="width: 50%;
                padding-right:15px;
                padding-left:15px;
                margin-right:auto;
                margin-left:auto;
                float:left">
      <img style="max-width: 300px;
                  max-height: 300px;
                  width: 100%;
                  height: auto;
                  float:left;" src="../images/people/{{ member.picture }}" alt="" width="300" height="300">
    </div>
    <div style="width: 50%;
                padding-right: 15px;
                padding-left: 15px;
                margin-right: auto;
                margin-left: auto;
                justify-content: center">
      <h3 style="margin-top: 0">{{ member.name }}</h3>
      <ul class="social-icons" style="margin-right: auto;
                                      margin-left: auto">  
        {% if member.twitter %}
        <a style="text-decoration:none" href="https://twitter.com/{{ member.twitter }}" rel="nofollow noopener noreferrer">
          <i class="fab fa-fw fa-twitter-square" aria-hidden="true"></i>
          <span class="label">Twitter</span>
        </a>
        {% endif %}
        {% if member.github %}
        <a style="text-decoration:none" href="https://github.com/{{ member.github }}" rel="nofollow noopener noreferrer">
          <i class="fab fa-fw fa-github" aria-hidden="true"></i>
          <span class="label">GitHub</span>
        </a>
        {% endif %}
        {% if member.email %}
        <a style="text-decoration:none" href="mailto:{{ member.email }}" rel="nofollow noopener noreferrer">
          <i class="fa fa-envelope" aria-hidden="true"></i>
          <span class="label">Email</span>
        </a>
        {% endif %}
        {% if member.linkedin %}
        <a style="text-decoration:none" href="https://linkedin.com/in/{{ member.linkedin }}" rel="nofollow noopener noreferrer">
          <i class="fab fa-fw fa-linkedin-in" aria-hidden="true"></i>
          <span class="label">Linkedin</span>
        </a>
        {% endif %}
      </ul>
      <p style="font-size:14px;
                text-align: justify;
                text-justify: inter-word;
                margin-right: auto;
                margin-left: auto">{{ member.description }}</p>
    </div>
  </div>
  <br>  
  {% endfor %}
</div>

---
layout: page
title: About Us
permalink: /about/
---

ROAM is the research on animal movement group at James Cook University. Our group is made of a diverse group of people across several disciplines, academic qualifications, gender, cultural backgrounds, and expertise. We are interested in a wide variety of matters associated to movement of animals in a manifold of ecosystems and taxa, including crustaceans, fish, birds, mammals, and reptiles.

ROAM was funded and is currently lead by Kyana Pike and Emily Webster, with the invigorating collaboration of ROAM members.

We meet every second Tuesday at noon using a mix virtual and presential format.


<h1>Who we are</h1>
<table border="0">
  <tr>
    <td width="200"> <img src="../images/people/kp.png"  alt="Kyana Pike" width = "200" height = "200" ></td>
    <td width="300">
        <b style="color:#4a4e69;font-size:25px;">Kyana Pike</b>
        <p>Kyana is a PhD candidate studying the effect of agriculture practices and infrastructure on the movement of giant tortoises in the Galapagos archipelago.</p>
    </td>
   </tr> 
   <tr>
      <td width="200"><img src="../images/people/ew.jpg" alt="Emily Webster" width = "200" height = "200"></td>
      <td width="300">
        <b style="color:#4a4e69;font-size:25px;">Emily Webster</b>
        <p>Emily is a PhD candidate researching the drivers of habitat use from green turtles in Queensland, Australia.</p>
      </td>
  </tr>
</table>


<div class="container">
<div class="row">
<h1>Contact us</h1>

{% for member in site.data.members.members %}

<ul class="social-icons" style="list-style: none;">
    <li>
        <b>{{ member.name }}</b>
        <p>{{ member.description }}</p>
    </li>
    {% if member.twitter %}
    <a style="text-decoration:none" href="https://twitter.com/{{ member.twitter }}" rel="nofollow noopener noreferrer">
        <i class="fab fa-fw fa-twitter-square" aria-hidden="true"></i><span class="label">Twitter</span>
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
    <a style="text-decoration:none" href="{{ member.linkedin }}" rel="nofollow noopener noreferrer">
        <i class="fab fa-fw fa-linkedin-in" aria-hidden="true"></i>
        <span class="label">Linkedin</span>
    </a>
    {% endif %}<br>
</ul>
{% endfor %}

</div>
</div>

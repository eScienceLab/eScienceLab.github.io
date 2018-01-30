---
layout: page
title: People
permalink: /people/

head:
- name: Professor Carole Goble
  orcid: 0000-0003-1219-2137
  img: carole-goble-sm.jpg
  role: Head

staff:
- name: Finn Bacall
  orcid: 0000-0002-0048-3300
  img: finn-bacall-sm.jpg
  role: Software Developer
- name: Niall Beard
  orcid: 0000-0002-2627-0231
  img: niall-beard-sm.jpg
  role: Scientific Web Technologist
- name: Nick Juty
  orcid: 0000-0002-2036-8350
  img: nick-juty-sm.jpg
  role: Senior Research Technical Manager
- name: Aleksandra Nenadic
  orcid: 0000-0002-2269-3894
  img: aleks-nenadic-sm.jpg
  role: Training Manager, Senior Research Software Engineer
- name: Stuart Owen
  orcid: 0000-0003-2130-0865
  img: stuart-owen-sm.jpg
  role: Senior Technical Architect
- name: Raniere Silva
  orcid: 0000-0002-8381-3749
  img: raniere-silva-sm.jpg
  role: Community Officer
- name: Stian Soiland-Reyes
  orcid: 0000-0001-9842-9718
  img: stian-soiland-reyes-sm.jpg
  role: Technical Architect
- name: Natalie J. Stanford
  orcid: 0000-0003-4958-0184
  img: natalie-stanford-sm.jpg
  role: Research Community Manager, Data Scientist
- name: Shoaib Sufi
  orcid: 0000-0001-6390-2616
  img: shoaib-sufi-sm.jpg
  role: Project Portfolio Manager, Community Manager
- name: Alan R Williams
  orcid: 0000-0003-3156-2105
  img: alan-williams-sm.jpg
  role: Senior Research Software Engineer

phd:

associate:
- name: Andy M. Brass
  orcid: 0000-0002-0389-7058
  url: http://www.manchester.ac.uk/research/andy.brass/personaldetails
  img: andy_brass-sm.jpg
- name: Alasdair J. G. Gray
  orcid: 0000-0002-5711-4872
  img: alasdair-gray.jpg
- name: Caroline Jay
  orcid: 0000-0002-6080-1382
  img: caroline-jay-sm.jpg
- name: Paolo Missier
  orcid: 0000-0002-0978-2446
  url: https://www.researchgate.net/profile/Paolo_Missier
  img: paolo-missier-sm.jpg
- name: Norman Morrison
  orcid: 0000-0003-1604-1512
  img: norman-morrison-sm.jpg
- name: Marco Roos
  orcid: 0000-0002-8691-772X
  img: marco-roos-sm.jpg
- name: Robert Stevens
  url: http://www.manchester.ac.uk/research/robert.stevens/
  img: robert-stevens.jpg
  orcid: 0000-0002-6038-9025
- name: Katy Wolstencroft
  orcid: 0000-0002-1279-5133
  img: katy-wolstencroft-sm.jpg

former:
- name: Sergejs Aleksejevs
- name: Pinar Alper
  orcid: 0000-0002-2224-0780
- name: Constantinos Astreos
- name: Khalid Belhajjame
  orcid: 0000-0001-6938-0820
- name: Jiten (Jits) Bhagat
- name: Mark Borkum
- name: Christian Y. A. Brenninkmeijer
  orcid: 0000-0002-2937-7819
- name: Tim Clark
  orcid: 0000-0003-4994-3803
- name: Oscar Corcho
  orcid: 0000-0002-9260-0753
- name: Phillip Cotter
- name: Don Cruickshank
  orcid: 0000-0002-0777-0855
- name: Ian Dunlop
  orcid: 0000-0001-7066-3350
- name: Suzanne Embury
- name: Donal Fellows
  orcid: 0000-0002-9091-5938  
- name: June Finch
- name: Paul Fisher
  orcid: 0000-0003-1983-9204
- name: Jeremy Frey
- name: Matthew Gamble
  orcid: 0000-0003-4913-1485
- name: Kristian Garza
  orcid: 0000-0003-3484-6875  
- name: Andrew Gibson
- name: Antoon Goderis
- name: Robert Haines
  orcid: 0000-0002-9538-7919
- name: Helen Hulme
- name: Duncan Hull
  orcid: 0000-0003-2387-503X
- name: Simon Jupp
  orcid: 0000-0002-0643-3144
- name: Bharathi Kattamuri
- name: Anna Leida
  orcid: 0000-0002-5945-1709
- name: Phillip Lord
- name: James Marsh
- name: Catarina Martins
  orcid: 0000-0001-9021-8860
- name: Philip McDermott
- name: Danius Michaelides
- name: Luc Moreau
- name: Georgina Moulton
- name: David Newman
- name: Rory Newton
- name: Eric Nzuobontane
- name: Tom Oinn
- name: Aleksandra Pawlik
  orcid: 0000-0001-8418-6735
- name: Steven Pettifer
  orcid: 0000-0002-1809-5621
  img: steve-pettifer-sm.jpg
- name: Rishi Ramgolam  
- name: Mark Robinson
  orcid: 0000-0002-8184-7507
- name: Mannie Tagarira
- name: Franck Tanohli
- name: Lefteris Tatakis
  orcid: 0000-0001-5554-7634
- name: Daniele Turi
- name: Anil Wipat
- name: David Withers
- name: Katy Wolstencroft
  orcid: 0000-0002-1279-5133
- name: Christopher Wroe
- name: Quiwei Yu
- name: Ed Zaluskali
---

## Staff

  {% for member in page.head %}
  <div class="profile_box head">
   <a {% if member.orcid %}href="http://orcid.org/{{member.orcid}}"{% endif %}><img src="/images/profiles/{{member.img}}" class="profile_picture"></a>
    <div class="name">{{member.name}}</div>
    <div class="role">{{member.role}}</div>
  </div>
  {% endfor %}

  {% for member in page.staff %}
  <div class="profile_box">
   <a {% if member.orcid %}href="http://orcid.org/{{member.orcid}}"{% endif %}><img src="/images/profiles/{{member.img}}" class="profile_picture"></a>
    <div class="name">{{member.name}}</div>
    <div class="role">{{member.role}}</div>
  </div>
  {% endfor %}

{%if page.phd %}
## PhD Students

  {% for member in page.phd %}
  <div class="profile_box">
   <a {% if member.orcid %}href="http://orcid.org/{{member.orcid}}"{% endif %}><img src="/images/profiles/{{member.img}}" class="profile_picture"></a>
    <div class="name">{{member.name}}</div>
    <div class="role">PhD Student</div>
  </div>
  {% endfor %}
{% endif %}

## Current Associates

  {% for member in page.associate %}
  <div class="grid-item profile_box">
   <a href="{% if member.url %}{{member.url}}{% elsif member.orcid %}http://orcid.org/{{member.orcid}}{% endif %}"><img src="/images/profiles/{{member.img}}" class="profile_picture"></a>
   <div class="name">{{member.name}}</div>
  </div>
  {% endfor %}

## Former Team Members and Associates

<div markdown='1' class="former-members">

{% for member in page.former %}
{% if member.orcid %}
- [{{member.name}}](http://orcid.org/{{member.orcid}})
{% else %}
- {{ member.name }}
{% endif %}
{% endfor %}

</div>

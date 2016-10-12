---
layout: page
title: People
permalink: /people/
head:
- name: Professor Carole Goble
  orcid: 0000-0003-1219-2137
  img: carole-goble-sm.png
  role: Head
staff:
- name: Finn Bacall
  orcid: 0000-0002-0048-3300
  img: finn-bacall-sm.png
  role: Software Developer
- name: Niall Beard
  orcid: 0000-0002-2627-0231
  img: niall-beard-sm.png
  role: Scientific Web Technologist
- name: Donal Fellows
  orcid: 0000-0002-9091-5938
  img: donal-fellows-sm.png
  role: Senior Research Software Engineer
- name: Anna Leida
  orcid: 0000-0002-5945-1709
  img: anna-leida-sm.png
  role: Senior Research Software Engineer
- name: Aleksandra Nenadic
  orcid: 0000-0002-2269-3894
  img: aleks-nenadic-sm.png
  role: Training Manager, Senior Research Software Engineer
- name: Stuart Owen
  orcid: 0000-0003-2130-0865
  img: stuart-owen-sm.png
  role: Senior Technical Architect
- name: Natalie J. Stanford
  orcid: 0000-0003-4958-0184
  img: natalie-stanford-sm.png
  role: Research Community Manager, Data Scientist
- name: Stian Soiland-Reyes
  orcid: 0000-0001-9842-9718
  img: stian-soiland-reyes-sm.png
  role: Technical Architect
- name: Raniere Silva
  orcid: 0000-0002-8381-3749
  img: raniere-silva-sm.png
  role: Community Officer
- name: Shoaib Sufi
  orcid: 0000-0001-6390-2616
  img: shoaib-sufi-sm.png
  role: Project Portfolio Manager, Community Manager
- name: Alan R Williams
  orcid: 0000-0003-3156-2105
  img: alan-williams-sm.png
  role: Senior Research Software Engineer
phd:
- name: Lefteris Tatakis
  orcid: 0000-0001-5554-7634
  img: lefteris-tatakis-sm.png
associate:
- name: Andy Brass
  orcid:
  url: http://www.manchester.ac.uk/research/andy.brass/personaldetails
  img: andy_brass-sm.png
- name: Paolo Missier
  orcid:
  url: https://www.researchgate.net/profile/Paolo_Missier
  img: paolo-missier-sm.png
- name: Katy Wolstencroft
  orcid: 0000-0002-1279-5133
  img: katy-wolstencroft-sm.png
- name: Steven Pettifer
  orcid: 0000-0002-1809-5621
  img: steve-pettifer-sm.png
- name: Marco Roos
  orcid: 0000-0002-8691-772X
  img: marco-roos-sm.png
- name: Norman Morrison
  orcid: 0000-0003-1604-1512
  img: norman-morrison-sm.png
former:
- name: Kristian Garza
  orcid: http://orcid.org/0000-0003-3484-6875
- name: Pinar Alper
  orcid: http://orcid.org/0000-0002-2224-0780
- name: Aleksandra Pawlik
  orcid: http://orcid.org/0000-0001-8418-6735
- name: Matthew Gamble
  orcid: http://orcid.org/0000-0003-4913-1485
- name: Robert Haines
  orcid: http://orcid.org/0000-0002-9538-7919
- name: Christian Y. A. Brenninkmeijer
  orcid: http://orcid.org/0000-0002-2937-7819
- name: Katy Wolstencroft
  orcid: http://orcid.org/0000-0002-1279-5133)
- name: Rishi Ramgolam
- name: Sergejs Aleksejevs
- name: Constantinos Astreos
- name: Jiten (Jits) Bhagat
- name: Khalid Belhajjame
  orcid: http://orcid.org/0000-0001-6938-0820
- name: Mark Borkum
- name: Tim Clark
  orcid: http://orcid.org/0000-0003-4994-3803
- name: Oscar Corcho
  orcid: http://orcid.org/0000-0002-9260-0753
- name: Phillip Cotter
- name: Don Cruickshank
  orcid: http://orcid.org/0000-0002-0777-0855
- name: Ian Dunlop
  orcid: http://orcid.org/0000-0001-7066-3350
- name: Suzanne Embury
- name: June Finch
- name: Paul Fisher
  orcid: http://orcid.org/0000-0003-1983-9204
- name: Jeremy Frey
- name: Andrew Gibson
- name: Antoon Goderis
- name: Alasdair J. G. Gray
  orcid: http://orcid.org/0000-0002-5711-4872
- name: Helen Hulme
- name: Duncan Hull
  orcid: http://orcid.org/0000-0003-2387-503X
- name: Simon Jupp]
  orcid: http://orcid.org/0000-0002-0643-3144
- name: Bharathi Kattamuri
- name: Phillip Lord
- name: James Marsh
- name: Philip McDermott
- name: Danius Michaelides
- name: Georgina Moulton
- name: Luc Moreau
- name: David Newman
- name: Rory Newton
- name: Eric Nzuobontane
- name: Tom Oinn
- name: Mannie Tagarira
- name: Franck Tanohli
- name: Daniele Turili
- name: David Withers
- name: Anil Wipat
- name: Christopher Wroe
- name: Quiwei Yu
- name: Ed Zaluskali
---
<script src="https://cdnjs.cloudflare.com/ajax/libs/masonry/3.3.2/masonry.pkgd.min.js"></script>

## Staff

<div class="grid js-masonry"
  data-masonry-options='{ "itemSelector": ".grid-item", "columnWidth": 100 }'>
  {% for member in page.head %}
  <div class="grid-item profile_box">
	<a href="http://orcid.org/{{member.orcid}}"><img src="/images/profiles/{{member.img}}" class="profile_picture"></a>
 	<div class="name">{{member.name}}</div>
 	<div class="role">{{member.role}}</div>
  </div>
  {% endfor %}
</div>

<div class="grid js-masonry"
  data-masonry-options='{ "itemSelector": ".grid-item", "columnWidth": 100 }'>
  {% for member in page.staff %}
  <div class="grid-item profile_box">
	<a href="http://orcid.org/{{member.orcid}}"><img src="/images/profiles/{{member.img}}" class="profile_picture"></a>
 	<div class="name">{{member.name}}</div>
 	<div class="role">{{member.role}}</div>
  </div>
  {% endfor %}
</div>

## PhD Students

<div class="grid js-masonry"
  data-masonry-options='{ "itemSelector": ".grid-item", "columnWidth": 100 }'>
  {% for member in page.phd %}
  <div class="grid-item profile_box">
	<a href="http://orcid.org/{{member.orcid}}"><img src="/images/profiles/{{member.img}}" class="profile_picture"></a>
 	<div class="name">{{member.name}}</div>
 	<div class="role">PhD Student</div>
  </div>
  {% endfor %}
</div>

## Current Associates

<div class="grid js-masonry"
  data-masonry-options='{ "itemSelector": ".grid-item", "columnWidth": 100 }'>
  {% for member in page.associate %}
  <div class="grid-item profile_box">
	<a href="{% if member.url %}{{member.url}}{% else %}http://orcid.org/{{member.orcid}}{% endif %}"><img src="/images/profiles/{{member.img}}" class="profile_picture"></a>
 	<div class="name">{{member.name}}</div>
  </div>
  {% endfor %}
</div>

## Former Team Members and Associates

{% for member in page.former %}
{% if member.orcid %}
- {{ member.name }}
{% else %}
- [{{member.name}}]({{member.orcid}})
{% endif %}
{% endfor %}

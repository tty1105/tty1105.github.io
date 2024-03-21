---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S., Nanjing University, 2018-2022
* Ph.D, Nanjing University, 2022- 

Work experience
======
Currently nothing
  
Skills
======
* Python
* Data reduction softwares of radio/millimeter/sub-millimeter telescope
  * [Gildas](https://www.iram.fr/IRAMFR/GILDAS/)/CLASS for data reduction of IRAM 30m, PMOD 13.7m, Yebes 40m, etc.
  * [Miriad](https://www.atnf.csiro.au/computing/software/miriad/) for ATCA data calibration and imaging
  * [CASA](https://casa.nrao.edu/casa_obtaining.shtml) for SMA data calibration and imaging
* Open-source codes of astronomical numerical simulation
  * [pNautilus](https://forge.oasu.u-bordeaux.fr/LAB/astrochem-tools/pnautilus) for astrochemistry
  * [Paris-Durham shock code](https://ism.obspm.fr/shock.html) for 1D plane-parallel shock physics and chemistry
  * [UCLCHEM](https://uclchem.github.io/) for astrochemistry
  * [PLUTO](http://plutocode.ph.unito.it/) for computational fluid dynamics (basic)
* Observation experience
  * Qualified observer of ATCA (NH<sub>3</sub> spectral lines)

Publications
======
  <ul>{% for post in site.publications %}
    {% if post.firstauthor == 'Yes'%}
    {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* LOC of [*Supernova Remnant and Interstellar Medium 2023*](https://astronomy.nju.edu.cn/njdx/front/expand/registration/view.do?iid=85) (超新星遗迹与星际介质2023) in Suzhou

Approved observation proposals as PI
=====
* NOEMA (W22AS: 11h): Shock and cosmic ray chemistry in molecular clouds interacting with supernova remnant W28
* SMA (2022B-S009: 16h): Shock and cosmic ray chemistry in molecular clouds interacting with supernova remnant W28
* ATCA (C3530: 24+10.6h): NH3 observation towards three ATLASGAL clumps associated with supernova remnant W28 
* Yebes (23A021: 22h) A 3mm line survey towards supernova remnant 3C391 
* GBT (GBT23B-090: 12h): Probing the cosmic-ray-ionized dense gas associated with supernova remnant HB9
* Yebes (24A003: 30.5h): Molecular Chemistry Induced by J-shock in Supernova Remnant W51C

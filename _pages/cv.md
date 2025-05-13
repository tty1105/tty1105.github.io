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
* B.S., Kuang Yaming Honors School, Nanjing University, 2018.9-2022.6
* Ph.D, School of Astronomy and Space Science, Nanjing University (Supervisor: Prof. Yang Chen), 2022.9-2027.6 (expected)
* Visiting PhD student, Laboratoire d'Astrophysique de Bordeaux (Supervisor: Dr. Valentine Wakelam. Sponsored by China Scholarship Council), 2024.12-2025.12 (expected)
  
Skills
======
* Python
* Data reduction softwares of radio/millimeter/sub-millimeter telescope
  * [Gildas](https://www.iram.fr/IRAMFR/GILDAS/)/CLASS for data reduction of IRAM 30m, PMOD 13.7m, Yebes 40m, etc.
  * [Miriad](https://www.atnf.csiro.au/computing/software/miriad/) for ATCA data calibration and imaging
  * [CASA](https://casa.nrao.edu/casa_obtaining.shtml) for SMA data calibration and imaging
  * [Spextool](https://irtfweb.ifa.hawaii.edu/~spex/observer/) for IRTF/SpeX data reduction
  * [IRAF](https://iraf.noirlab.edu/) for CTIO-4m/NEWFIRM data calibration
* Open-source codes of astronomical numerical simulation
  * [Nautilus](https://forge.oasu.u-bordeaux.fr/LAB/astrochem-tools/pnautilus) for astrochemistry
  * [Paris-Durham shock code](https://ism.obspm.fr/shock.html) for 1D plane-parallel shock physics and chemistry
  * [UCLCHEM](https://uclchem.github.io/) for astrochemistry
  * [Meudon PDR code](https://ism.obspm.fr/pdr.html) for simulation of photodissociation regions (basic)
  * [PLUTO](http://plutocode.ph.unito.it/) for computational fluid dynamics (basic)
* Observation experience
  * Qualified observer of ATCA (NH<sub>3</sub> spectral lines, remote)
  * IRTF/SpeX observation (remote)
  * CTIO/Blanco-4m/NEWFIRM observation (remote)

Publications (as 1st author)
======
  <ul>{% for post in site.publications %}
    {% if post.firstauthor == 'Yes' %}
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
* Teaching assistant of graduate course _Astrophysical Radiation Mechanisms_ (2023.9-2024.1)

Approved observation proposals (as PI)
=====
* NOEMA (W22AS: 11h): Shock and cosmic ray chemistry in molecular clouds interacting with supernova remnant W28
* SMA (2022B-S009: 16h): Shock and cosmic ray chemistry in molecular clouds interacting with supernova remnant W28
* ATCA (C3530: 24+10.6+5.5h): NH3 observation towards three ATLASGAL clumps associated with supernova remnant W28 
* Yebes (23A021: 22h) A 3mm line survey towards supernova remnant 3C391 
* GBT (GBT23B-090: 12h): Probing the cosmic-ray-ionized dense gas associated with supernova remnant HB9
* Yebes (24A003: 30.5h): Molecular Chemistry Induced by J-shock in Supernova Remnant W51C
* Yebes (24B010: 36.5h): Chemistry induced by cosmic rays towards supernova remnant Kes79
* JCMT (M24BP015: 23.7h, filler): Estimation of cosmic-ray ionization rate towards supernova remnant Kes79
* IRTF (2024B008: 11h): Cosmic-ray processing of interstellar ice towards supernova remnant W44
* ALMA (2024.1.00194.S, 7m: 11.6h, TP: 23h): Physics and chemistry of dense molecular gas interacting with SNR W28
* CFHT (25AS01, 4.54h, through TAP): Probing the interaction between supernova remnant and molecular cloud towards Galactic PeVatron: G106.3+2.7
* CTIO-4m (2025A-734415, 2 nights): Probing the interaction between supernova remnants and molecular clouds towards TeV gamma-ray sources
* CTIO-4m (2025A-127790, 0.5 nights): Probing the shock-cloud interaction towards supernova remnant RX J1713.7-3946
* IRTF (2025A003, 28.2h): Cosmic-ray processing of interstellar ice towards supernova remnant W51C
* IRTF (2025A007, 14h): Probing the cosmic-ray ionization towards the Cygnus Cocoon
* Yebes (25A004, 27.2h): A Q-band line survey towards supernova remnant W28
* IRAM 30m (006-25, 28.9h): Cosmic ray ionization towards supernova remnant HB9
* IRAM 30m (016-25, 39.4h): Origin of the narrow SiO emission in IRDC G33.69-0.01
* NOEMA (S25AN, 19.0h): J- and C-shock chemistry towards clump C of supernova ramnant IC443
* NOEMA (S25AS, 15.6h): Probing the molecular cloud exposed to shock and cosmic rays from supernova remnant 3C391
* GBT (GBT25B-001, 37.5h): NH3 map of molecular clouds interacting with supernova remnants W28 and IC443

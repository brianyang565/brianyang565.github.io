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
* Ph.D. in Physics (Experimental AMO), University of Michigan, Ann Arbor, 2021–present (expected 2027)
  * Focus: quantum optics, Rydberg atom ensembles, and phase-matched emission
* B.S. in Honors Physics, University of Michigan, Ann Arbor, 2021
  * Honors thesis: *Analysis of Iterative Beam Shaping Algorithm for Simultaneous Amplitude and Phase Control*

Research experience
======
* **Graduate Research Assistant**, Kuzmich Research Group, University of Michigan, 2021–present
  * Implemented optical interference techniques to measure photon bunching and antibunching in light emitted by atomic ensembles.
  * Quantified coherent transfers between hyperfine magnetic states and recorded superfluorescent quantum beats between Rydberg states.
  * Modeled Rydberg ensemble dynamics using the Jaynes–Cummings model.
  * Built laser intensity servos and acousto-optic modulator and fiber paths, and characterized the phase noise of the 780 nm laser.
  * Implemented experimental timing sequences in Cicero and Atticus to control laser pulse durations and trigger detectors for data acquisition.
  * Wrote standard operating procedures for lab devices and coached junior group members and undergraduates in hands-on experimental skills.
* **Undergraduate Research Assistant**, Kuzmich Research Group, University of Michigan, 2019–2021
  * Upgraded the timing control of the Rydberg ensemble experiment to the Cicero/Atticus framework.
  * Designed a custom objective lens in Zemax for atom imaging and trapping.
  * Developed beam-shaping algorithms in Mathematica for simultaneous phase and amplitude control and tested them on a spatial light modulator, culminating in a senior honors thesis.
  * Simulated the light fields produced by 2D arrays of excited atoms and computed mode matching with zeroth-order Gaussian beam modes.
* **Summer Undergraduate Research Assistant**, Hong Kong University of Science and Technology, summers of 2017 and 2018
  * In 2018, co-designed and constructed a Bitter-type electromagnet for an ultracold magneto-optical trap, and integrated solid-state relay modules to optimize fast magnetic switching.
  * In 2017, developed Fast Fourier Transform analysis scripts in MATLAB to isolate and test the eigenfrequencies of prototype dampers, leading to a co-authored publication in *Scientific Reports*.

Skills
======
* **Laser systems:** laser intensity servos, acousto-optic modulator and fiber paths, laser locking with Vescent systems, optimization of Pound–Drever–Hall cavity locks and second-harmonic generation, phase-noise characterization
* **Atomic physics:** laser cooling and trapping, magneto-optical trap optical layouts, Bitter-type electromagnets, ultrahigh-vacuum systems, precision spectroscopy
* **Software:** Python (NumPy, Pandas, Tkinter), Mathematica, MATLAB, C++, IGOR Pro, LabVIEW, Git and GitHub
* **Optical and mechanical design:** Zemax, GaussianBeam, SolidWorks
* **Experiment control:** Cicero and Atticus

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
* **Graduate Student Instructor**, University of Michigan, 2021–2026
  * Taught undergraduate physics laboratory courses in mechanics, fluids, electricity and magnetism, and modern physics. Individual courses are listed on the [Teaching](/teaching/) page.
  * Managed real-time hardware troubleshooting and classroom safety across concurrent student work stations.
  * Introduced students to statistical uncertainty, error propagation, and clear technical reporting.

Side projects
======
* **[PDH laser-lock simulation](/portfolio/pdh-lock-simulation/)**, 2026
  * Wrote a Python simulation of a Pound–Drever–Hall laser lock from the parameters of our experiment, and compared the closed-loop model with the measured noise of the cavity-transmitted light.
* **Open-source contributor and editorial team member**, [IS Central](https://is-central.github.io), 2026–present
  * Co-developed a responsive web platform with dynamic calculators, tournament calendars, and other interactive components, working through branches and pull-request reviews within a distributed team.

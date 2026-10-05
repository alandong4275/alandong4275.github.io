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
* Ph.D. in Engineering, University of Cambridge, Sep 2025 - 2028 (expected)
* M.Eng. in Engineering, University of Cambridge, Sep 2024 - Jul 2025
* B.A. in Engineering, University of Cambridge, Sep 2021 - Jul 2024

Work experience
======
* Silicon Physical Design Intern, Graphcore, Jul 2024 - Aug 2024
  * Developed an experimental Python tree algorithm for identifying common groupings of standard cells in a
processor netlist to reduce power consumption, assembling a database of logically equivalent groupings with
their number of instances. Delivered grouping proposals for a relevant processor.
    
[//]: # (* Duties includes: Updates and improvements to template)
[//]: # (* Supervisor: The Users)

* Silicon Logical Design Intern, Graphcore, Jul 2023 - Sep 2023
  * Designed a FP32 hardware instruction to compute a quick approximation for an ML activation function in
10x fewer instruction cycles, optimised for timing and functionally verified with a companion testbench. Ran
inference tests with LLMs to compare performance against exact function and established approaches.
    
[//]: #  (* Duties included: Merging pull requests)
[//]: #  (* Supervisor: Professor Hub)

* Silicon Verification Intern, Graphcore, Jul 2022 - Sep 2022
  * Delivered up to 100x faster Python message parsing from external EDA tools using Intel Hyperscan, core to a
Python/C++/SQL database system used for processor development. Built a Python tool to generate random
strings from regular expressions, used to evaluate performance of regex libraries and create unit tests.
    
* Unity Developer Intern, KXcontrols, Oct 2020 - Mar 2021
  * Prototyped a 3D virtual interface using Unity game engine for building systems management software.

[//]: #  (* Duties included: Tagging issues)
[//]: #  (* Supervisor: Professor Git)
  
[//]: # (Skills)
[//]: # ======
[//]: # * Skill 1
[//]: # * Skill 2
[//]: # * Sub-skill 2.1
[//]: # * Sub-skill 2.2
[//]: # * Sub-skill 2.3
[//]: # * Skill 3
<!--
[//]: # (Publications)
[//]: # (======)
[//]: # ( <ul>{% for post in site.publications reversed %})
[//]: # ({% include archive-single-cv.html %})
[//]: # ({% endfor %}</ul>)

  
[//]: # (Talks)
[//]: # (======)
[//]: # (<ul>{% for post in site.talks reversed %})
[//]: # ({% include archive-single-talk-cv.html  %})
[//]: # ({% endfor %}</ul>)
  -->

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
[//]: # (Service and leadership
[//]: # ======
[//]: # * Currently signed in to 43 different slack teams)

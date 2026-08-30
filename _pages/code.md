---
layout: archive
title: ""
permalink: /code/
author_profile: true
---

#  <a href="https://aucyberlab.github.io/adsynthesizer/"> ADSynthesizer </a>

We build a realistic Active Directory attack graph generator using metagraph abstractions.

![ADSynth-generated Active Directory attack graph](https://hxnguyen.github.io/images/adsynth.png "ADSynth")
![Active Directory attack graph example](https://hxnguyen.github.io/images/ad_and_attack.jpeg "Active Directory attack graph")


#  <a href="http://autonetkit.org"> Autonetkit </a>

I built  the first version of Autonetkit - open source code to automatically  generate emulations of large networks with sophisticated policies. Autonetkit is now used in the Cisco VIRL lab.

![AutoNetkit network emulation](https://hxnguyen.github.io/images/autonetkit.png "AutoNetkit")


#  <a href="https://github.com/dinesharanathunga/mgtoolkit"> MGtoolkit </a>

Mgtoolkit is a python package for modelling and analysing  metagraphs - a special type of hypergraph. We used metagraphs for modelling network security policies.

{% include base_path %}

{% for post in site.code reversed %} 
{% include archive-single.html %} {% endfor %}

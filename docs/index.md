---
title: Welcome to Sherlock - Offline Voice Assistant
layout: default
nav_order: 1
has_toc: true
---

<!-- <details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details> -->


# Welcome To Sherlock - Offline Voice Assistant
Sherlock is a simple to use offline voice assistant, it's based on the [Rhasspy project](https://rhasspy.readthedocs.io/en/latest/). 
It's an opensource project and is working local offline on your [Raspberry Pi](https://de.wikipedia.org/wiki/Raspberry_Pi). 
So you don't need to worry about your privacy, it stays all on your own device. Unlike the Google Assistant or Alexa, 
they upload all you say to them to their cloud to process it. This is not a good way, when you want to have a good privacy for example for vulnerable person.

# Skills
- [Read the clock](/pages/skills/time)
- [Set an alarm clock](/pages/skills/alarm/)
- [Weather forecast](/pages/skills/weather-forecast)
- [Light control](/pages/skills/light-control)
- [Get latest news](/pages/skills/news/)
- [Get infos about exchange rate](/pages/skills/exchange-rate)

# How to use
This website is separated in three parts. One part is [Installation](/pages/installation), a tutorial for 
installing Sherlock. The second one is the [Knowledge](pages/knowledge) section. There you find interesting 
background information about Rhasspy and the surrounding programs. The third one is [Skills](/pages/skills) which contains 
the preset skills for Sherlock and how to configure them.

# Why Sherlock?
Sherlock is a short, catchy word that is rarely used in everyday language. It also consists of two syllables and is 
therefore a perfect wake word. Furthermore, Sherlock is based on the character Sherlock Holmes whose brother is 
Mycroft Holmes. There is an open source language wizard called [Mycroft](https://mycroft.ai/).

# Software-Stack
| Software                                                | Version            | Note
|---------------------------------------------------------|--------------------|--------------------------------------------|
| [Rhasspy](https://rhasspy.readthedocs.io/en/latest/)    | 2.5.9              | Intent recognition not working on v2.5.10. See [issue 234](https://github.com/rhasspy/rhasspy/issues/234)
| DeepSpeech                                              | 0.9.0              | 
| Hermes LED Control                                      | 2.0.10             | 
| Node-RED	                                              | 1.3.4              | 
| Snips-NLU	                                              | 0.2.0              | 
| Mosquitto	                                              | 1.5.7              | 


# Links
- Archilab project page: [www.archi-lab.io](https://www.archi-lab.io/pages/viewpage.action?pageId=41156613)
- Intia project page: [dites.web.th-koeln.de](https://dites.web.th-koeln.de/forschung/projekte/intia/)
- Project repository: [th-koeln-intia/ip-sprachassistent-team4](https://github.com/th-koeln-intia/ip-sprachassistent-team4)

## Our other repositories we created for this project:
  - [Sh4der/rhasspy-asr-deepspeech](https://github.com/Sh4der/rhasspy-asr-deepspeech)
  - [Sh4der/rhasspy-asr-deepspeech-hermes](https://github.com/Sh4der/rhasspy-asr-deepspeech-hermes)
  - [kevinbischof/node-red-contrib-smalltimer](https://github.com/kevinbischof/node-red-contrib-smalltimer)
  - [Sh4der/MQTTMozillaTTSGerman](https://github.com/Sh4der/MQTTMozillaTTSGerman)
---
layout: page
title: Surveillance System
description: Surveillance system with motion detection, image capture, and wireless notifications using a Raspberry Pi and Arduino with attachments.
img: assets/img/surveillance_system.jpg
importance: 2
category: Miscellaneous
---

<div class="row">
    <div class="col-sm-7 mt-3 mt-md-0">
        <p>
        Building on my <a href="https://nicholasbdunn.github.io/projects/smart_alarm">smart alarm system</a> work, I collaborated with another student to create a motion-detecting surveillance system using an Arduino Uno, NodeMCU, Raspberry Pi, motion sensor, Arducam, and an LED. After detecting motion, a picture was taken with the Arducam and saved onto a computer. The NodeMCU was then used to transmit a wireless notification to the Raspberry Pi to indicate system activation. The Raspberry Pi would save the data from the notification and activate an LED to alert observers of the event. My contributions included co-designing the system, developing code for the Arduino, NodeMCU, and Raspberry Pi, and assisting with wiring the hardware components.
        </p>
    </div>
    <div class="col-sm-5 mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/surveillance_system.jpg" title="Surveillance System" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
---
layout: page
title: GRATTIS
description: Gravitational Reference Advanced Technology Test in Space - A NASA ESTO funded satellite mission with the goal to confirm performance of the S-GRS, an ultra-sensitive electrostatic inertial accelerometer in space.
img: assets/img/GRATTIS/GRATTIS_Geoid-88_4kb_cropped.png
importance: 1
category: work
related_publications: true
---

The Gravitational Reference Advanced Technology Test In Space (GRATTIS) mission will demonstrate the end-to-end functionality and sensitivity performance of the Simplified Gravitational Reference Sensor (S-GRS), an ultra-precise inertial sensor for future Earth geodesy missions. 
These sensors are used to measure or compensate for all non-gravitational accelerations of the host spacecraft so that they can be removed in the data analysis to recover spacecraft motion due to Earth’s gravity field, the main science observable. 
The S-GRS concept is a simplified version of the flight-proven LISA Pathfinder GRS. 
It consists of a free-falling cubic test mass inside an electrode housing that senses the position and orientation of the test mass and electrostatically applies forces and torques to it to keep it centered at a nanometer-level. 
The improved performance of the S-GRS is enabled by removing the small grounding wire used in the GRACE accelerometers, which limits its performance, and replacing it with a UV LED-based charge management system, increasing the mass of the sensor’s TM, and increasing the gap between the TM and its electrode housing. 
GRATTIS will fly two identical S-GRS mounted next to one another at the center of mass of a 160 kg ESPA-class commercial microsatellite with a planned launch in 2027. 
The six-axis acceleration measurement capability of the S-GRS allows precision measurement of the spacecraft drag-induced translational acceleration, as well as the residual angular acceleration of the nominally inertially-pointed bus. 
By combining the outputs of each sensor and with the known relative position of the two TMs, we can recover the acceleration sensitivity (noise floor) of the S-GRS [1].

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image"
    class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image"
    class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}

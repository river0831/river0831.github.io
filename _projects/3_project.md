---
layout: page
title: Vector-based painting
description: A painting representation
img: assets/img/ntu.png
importance: 3
category: research
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj_painting.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview of boundary stroke-based occlusion representation for 2D line drawing.
</div>

<p class="justify">
The aim of this project is to propose a stroke-based painting representation to store the color information of a vector lineart and applicable in inbetweening.
</p>

<p class="justify">

There are many approaches to paint line drawings. However, they are limited in dynamic color update while drawing editing. This curtails the editability of drawings and also hampers the auto-painting of animated drawings. We propose a stroke-based painting representation that associates colors with strokes. A painted drawing is represented purely with strokes, based on which region colors are resolved. With this representation, users can freely modify painted drawings with colors being updated automatically. Color stroke is further extended to auto-paint 2D animated drawings. Experimental results demonstrate the advantages of our method in painting drawings and managing colors.
</p>

<p class="justify">
<strong>Keywords:</strong> lineart, painting, stroke-based representation
</p>

<p class="justify">
<strong>Paper:</strong> Jiang, J., Seah, H. S., & Liew, H. Z. (2023, March). Stroke-based painting. In <i>International Workshop on Advanced Imaging Technology (IWAIT) 2023</i> (Vol. 12592, pp. 6-11). SPIE.
</p>

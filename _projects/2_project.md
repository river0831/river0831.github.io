---
layout: page
title: Vector-based inbetweening
description: An occlusion representation
img: assets/img/ntu.png
importance: 2
category: research
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj_boundary_stroke.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview of boundary stroke-based occlusion representation for 2D line drawing.
</div>

<p class="justify">
The aim of this project is to propose a stroke-based occlusion representation, which makes occlusion manageable and is applicable in 2D stroke-based inbetweening.
</p>

<p class="justify">
In conventional 2D drawing systems, a drawing usually consists of multiple layers and is composited by rendering layers from back to front. A shape in a higher layer occludes contents in lower layers. However, shapes must have boundaries that form closed regions for occlusion. This limitation causes problems in occlusion resolution. We therefore propose a method to allow users to specify and resolve occlusion in stroke-based drawing with boundary strokes. Rather than defining shapes, we introduce boundary strokes, which are strokes with occluding sides that work as occluding surfaces. We further introduce a series of user interactions, such as grouping, linking and inverting, on the boundary strokes to realize different occlusion effects. Geometry is then used to find the regions of occluding surfaces to resolve occlusion. The drawings are ready to be coloured, if needed. We extend our method to resolve occlusion in 2D stroke-based inbetweening. We demonstrate the effectiveness of our method by applying it to resolve occlusion in single drawings and 2D stroke-based inbetweening.
</p>

<p class="justify">
<strong>Keywords:</strong> inbetweening, lineart, occlusion
</p>

<p class="justify">
<strong>Paper:</strong> Jiang, J., Seah, H. S., & Liew, H. Z. (2022, February). Stroke‐Based Drawing and Inbetweening with Boundary Strokes. In <i>Computer Graphics Forum</i> (Vol. 41, No. 1, pp. 257-269).
</p>
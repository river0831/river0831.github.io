---
layout: page
title: Vector-based drawing
description: Handling Gaps for Vector Lineart
img: assets/img/ntu.png
importance: 1
category: research
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/proj_gap_close.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview of the vector lineart gap closing method.
</div>

<p class="justify">
The aim of this project is to propose an semi-automatic gap handling method for 2D hand-drawn vector lineart to restore stroke connections and make it colorable.
</p>

<p class="justify">
In computer-assisted 2D vector drawing systems, due to the precision of stroke representation, a stroke endpoint may not precisely connect to another stroke or endpoint during drawing so that the stroke endpoints become dangling. We call such dangling endpoints, gap points. With the presence of gaps on the region boundaries, regions formed by strokes frequently cannot be correctly colored using the standard ‘flood fill’ algorithm. In this paper, we propose a stroke-based technique to handle gaps in a vector drawing. The main contribution of our work is automatic computation of gap sizes of gap points without a predefined gap size and using a least energy method to handle gap points by estimating their relationship with surrounding strokes. Our approach consists of two major steps. Firstly, we cluster gap points in a drawing using Minimum Spanning Tree. Secondly, for each endpoint cluster, we use a least energy method together with predefined gap handling priority to estimate the connection of gap points. We demonstrate the effectiveness of our approach by applying it to line drawings with unresolved gap points.
</p>

<p class="justify">
<strong>Keywords:</strong> vector graphics coloring, gap size independence, minimum spanning tree-based clustering, least energy function
</p>

<p class="justify">
<strong>Paper:</strong> Jiang, J., Seah, H. S., & Liew, H. Z. (2021). Handling gaps for vector graphics coloring. <i>The Visual Computer, 37</i>(9-11), 2473-2484.
</p>
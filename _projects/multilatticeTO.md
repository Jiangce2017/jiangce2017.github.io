---
layout: page
title: Multi-lattice Topology Optimization with Smooth Spatial Lattice Transition
description:  Achieve material extreme through geometry
importance: 1
category: work
---

Multi-Lattice Topology Optimization is a computational design framework that enables decoupled tuning of mechanical properties by embedding multiple interacting lattice architectures within a single structure. By integrating physics-based simulation and machine-learning-driven optimization, the approach supports the design of high-performance, additively manufacturable systems whose functionality emerges from their physical architecture.

<div class="row justify-content-center align-content-center">
    <div class="col-md-12 mt-3 mt-md-0 text-center">
        {% include figure.html path="assets/img/projects/tipload.gif" title="Optimize part shape and lattice distribution at the same time" class="img-fluid rounded z-depth-1" %}
        <p>Optimize part shape and lattice distribution at the same time</p>
    </div>
</div>


<div class="publications">
<h2>Related publications</h2>  
  
{% bibliography -f papers -q @*[multilattice=true]* %}
</div>

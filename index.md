---
title: 🧠 Index 🧠
slug: index
feed:
  count: 1000
date: 2021-05-22
---

# Hi! <img src="https://user-images.githubusercontent.com/1303154/88677602-1635ba80-d120-11ea-84d8-d263ba5fc3c0.gif" width="28px" alt="hi"> I'm Mark.

``` {=html}
<!-- Three.js -->
<script src="https://unpkg.com/three@0.127.0/build/three"></script>
<script src="https://unpkg.com/three@0.127.0/examples/js/renderers/CSS2DRenderer.js"></script>
<script src="https://unpkg.com/three-spritetext@1.6.3"></script>

<!-- 3D force  -->
<script src="https://unpkg.com/d3-dsv@3.0.1"></script>
<script src="https://unpkg.com/d3-octree@0.2.0"></script>
<script src="https://unpkg.com/d3-force-3d@3.0.2"></script>
<script src="https://unpkg.com/element-resize-detector@1.2.4/dist/element-resize-detector.min.js"></script>
<script src="https://unpkg.com/3d-force-graph@1.70.7"></script>

<!-- Styles -->
<link rel="stylesheet" href="./static/css/3d-graph.css">

<div id="graph-visibility-controls" class="graph-controls">
  <button id="visibilityToggle">
    Hide Graph
  </button>
</div>

<div id="3d-graph-container">
  <div id="dat-gui"></div>
  <div id="3d-graph"></div>

  <blockquote id="graph-instructions">
    Drag to rellocate a node. Click to focus on node (while rotation is paused).
    Double click a node to view its Zettel page. Double click background to
    zoom-to-fit. Nodes are colored and sized based on clustering. Nodes that has
    more subnodes will be displayed relatively bigger.
  </blockquote>
</div>

<script src="./static/js/3d-graph.js" type="module"></script>
```
## Recent Posts

<!-- NOTE: Forward folge # is essential for RSS -->
[[z:zettels?tag=zettel&limit=10&timeline]]#

[[zettel|See more]]


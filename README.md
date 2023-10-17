# 3D Wireframe Cube - JavaScript Software Rendering

A software rendered 3D Wireframe Cube demo for HTML5. No 3D libraries and no HTML Canvas are used. The the 3D transformations and 3D&rarr;2D calculations are done in the JavaScript code.

<br/>
<p align="center">
  <img width="618" alt="3dwf" src="https://github.com/ZeroDayArcade/HTML5-3D-Wireframe-Cube/assets/141867962/a2fabb93-a49f-49ed-9ee9-e3f4c51ceaf1">
</p>

<br/>

This demo modulates the the vertices of SVG polygons on the DOM to produce a 3D cube. No HTML Canvas is used. The rendered triangles are in fact `<polygon>` elements nested within an `<svg>` element. The value of the `points` attribute for each `<polygon>` is changed every frame (using `setInterval`) based on the the 2D coordinates obtained from the 3D&rarr;2D projection of the triangles in 3D space calculated explicitly in the JavaScript. 

This demo was inspired by One Lone Coder / javidx9's brilliant video tutorial on building a 3D engine from scratch in C++. If you are new to 3D graphics or software rendering, I highly recommend you watch his tutorial <a target="_blank" href="https://www.youtube.com/watch?v=ih20l3pJoeU">here</a>.

### See the <a href="https://zerodayarcade.com/demos/3d-wireframe">Live Demo</a>

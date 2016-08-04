# LJ Code 201 Day - 13

“Tell me and I forget Teach me and I remember. Involve me and I learn.”

Today we talked about UI and UX...
UI is a step in the overall process that delivers UX, and not the process itself.
Research - interviews, observations, surveys
Analysis - personas, scenarios, synthesis
Design - workflow, wireframes, prototypes
production - visual design, development, technical testing
Launch
Beta Launch
Evaluate

We also talked about CSS wireframes. Example is found on codepen... worked out problem to show the correct layout and how the page should flow. Ultimately to have a performing html and css implementation, you need to build your markup in a way that mimics this wireframe.  The goal is to build all your markup and html first, then apply stylistic elements. Start with text and images, then add CSS flare.

Scrollable containers

CSS masterclass Containers are the biggest piece in understanding how CSS works, and containers are in conjunction with HTML.

- Our goal is to make our CSS directly mimic our HTML. Limit your use of containers and start working with more abstract concepts like positioning and floats.
- For HTML, content dictates height.

Chart js

Chart.js draws its magic from an html element called canvas.

The canvas element in HTML (width and height attributes are modifiable):
     <canvas id=“tutorial” width=“150” height=“150”> </canvas>

In JS, you’ll need to specify:

- Where you’re pulling canvas from html
    - var canvas = document.getElementById(‘tutorial’);
- Context
    - var ctx = canvas.getContext(‘2d')

charts.org/docs/#bar-chart

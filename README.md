# Html_Canvas
Leanrning more about using the HTML Canvas Element and using JS to control it

## What can it do ?

- Provides a space for program-controlled drawing
    
    - Images, video, shapes, curves, etc.

- Supported in all major modern browsers

    - Fallback content displayed in browsers that don't support canvas

- Pages can have multiple canvases, even overlapping ones

## About the Element

- Canvas content is not part of the DOM itself

- SVG would be more suitable for mixing graphics with the DOM

![Canvas Element image of a rectangle](/img/CanvasElement.PNG)

- The <canvas> tag is used to draw graphics, on the fly, via scripting (usually JavaScript).

- The <canvas> tag is transparent, and is only a container for graphics, you must use a script to actually draw the graphics.

- Any text inside the <canvas> element will be displayed in browsers with JavaScript disabled and in browsers that do not support <canvas>.

## Attributes

Attribute  | Value  | Description
---------- | ------ | --------
height | pixels | Specifies the height of the canvas. Default value is 150
width | pixels | Specifies the width of the canvas Default value is 300
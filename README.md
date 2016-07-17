This repo contains some experiments that I have done while trying out WebGL.

## The Mandelbrot set

A simple rendering of the Mandelbrot set. Zoom in and out using the mouse wheel. Recenter and zoom in using the left and middle mouse buttons.

Different color mappings are available in the source.

[Live demo](http://htmlpreview.github.io/?raw.githubusercontent.com/andrelaszlo/webgl/master/mandel.html)

Default view:

![The Mandelbrot set](/samples/mandel.png)

Zoomed:

![Zoomed in on part of the Mandelbrot set](/samples/mandel_zoom.png)


## Metaballs

This is a modified example of a metaballs tutorial (see links below). I changed the color of the blobs and added blobs with negative weight.

[Live demo](http://htmlpreview.github.io/?raw.githubusercontent.com/andrelaszlo/webgl/master/metaballs.html)

![Modified metaballs example](/samples/metaballs.png)

## Links

Here are some links I found useful:

* Tutorial on metaballs and fragment shaders: http://jamie-wong.com/2016/07/06/metaballs-and-webgl/
* Marching squares algorithm: http://jamie-wong.com/2014/08/19/metaballs-and-marching-squares/
* Implementation tips for rendering the Mandelbrot set: http://csl.sublevel3.org/post/mandelbrot-rendering/
* Smooth coloring algorithm for the Mandelbrot set: http://linas.org/art-gallery/escape/smooth.html
* GLSL reference: http://www.shaderific.com/glsl/
* WebGL tutorial (starts from 0): http://learningwebgl.com/
* An old (quite slow) Mandelbrot set renderer based on some .NET code I wrote in high school, unfortunately I have lost the source code. It kind of works in Wine: http://download.cnet.com/The-Mandelbrot-Set/3000-2053_4-10838730.html
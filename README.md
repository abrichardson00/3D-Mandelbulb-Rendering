# 3D-Mandelbulb-Rendering
Live web demo rendering fractals with a raymarching shader. Try it out here: https://abrichardson00.github.io/raymarching_fractals_demo.html

![mandelbulb2](mandelbulb2.png?raw=true "mandelbulb2")
![mandelbulb3](mandelbulb3.png?raw=true "mandelbulb3")
![mandelbulb4](mandelbulb4.png?raw=true "mandelbulb4")

Ray-marching works by 'marching' some ray out step by step from the camera position, and at each iteration checking if it's hit our fractal. If it does hit, we then know to colour an appropriate pixel on the screen some colour.

In the future I want to revisit this, perhaps improving the colouring with finding a normal vectors to the mandelbulb surface and using proper shadows. However things would just get more CPU intensive and I’d want to try improve the code’s efficiency, perhaps by using a distance estimator for the mandelbulb.

I’m pretty content with what it’s at right now. It has some nice style and uniqueness to it – and while more detailed fancy mandelbulb renderings look cool, they’ve been done by hundreds of others already. However I do want to play about with more colour.

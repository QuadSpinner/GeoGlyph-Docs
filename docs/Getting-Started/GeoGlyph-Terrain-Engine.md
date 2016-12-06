## Inception of Terrenderer
We are a proud contributor to the World Machine ecosystem and are equally excited about the direction of terrain design. GeoGlyph 2.0, its modern new interface, and first ever external synthesizer are stirring things up! 

When we began developing GeoGlyph 1.0 for both World Machine 2 & 3, we faced compatibility issues. This is normal. 3dsmax 2010 and 3dsmax 2016 are widely different under the hood, for example. We also met limitations in what we could do inside World Machine with our macros. This led to the inception of our fully external engine, Terrenderer (pronounced *T·ren′der·er*). External engines are quite common in CG. Popular packages such as V-Ray, Corona, Octane, and even Vue xStream all run outside their host environment. 

![Chart](http://cdn.quadspinner.com/blog/gg2-outside-chart2.png)

## Advantages of an external engine
A primary advantage of having an external engine is the ability to decouple our development with World Machine's. What does this mean in real terms?

- GeoGlyph's development is not tied to World Machine's, so we can move at our own pace.
- The engine provides a seamless experience across both World Machine 2 & 3.
- We can add things to World Machine which normally would be cumbersome, time consuming, and sometimes impossible.
- We can utilize modern architecture, programming language, and 3rd party libraries not supported in World Machine's C++ core, including using the GPU.
- The way is paved for pure GPU powered devices in the near future (already in development).
- Memory usage is reduced and better parallel processing is allowed.
- We can augment support for more 2D and 3D formats.
- We can include native 48-bit color support (HDR support is already in development for GeoGlyph 2.1).
- We can utilize DirectX based viewports in our device editors.
- And we can design new forms of erosion, something sorely lacking in CG terrains for quite a while.

## Productivity overhaul
On top of these massive internal changes, we have overhauled the user interface (also executed externally) through the GeoGlyph Integrated Design Environment (IDE). New productivity tools can be added - like the new Toolbox and Toolbar, Build Stack, and more - without destabilizing World Machine or hindering its development.

![Chart](http://cdn.quadspinner.com/blog/gg2-blog-breakdown.jpg)

To us, productivity tools and seemingly simple enhancements are critical features. Artists often work 80 hours a week and spend countless hours tinkering with their TMD files. Shaving off a couple of seconds or even a few minutes from repetitive tasks adds up!

One key example is waiting for a build to finish. With 4k and 8k builds, a build can often take hours to complete. This is typically when the artist has a chance to take a needed break before the next task begins. However, if you don't know the state of the build, you either can't leave your desk, or you have to check back frequently. The Build Notifications in GeoGlyph 2 Professional sends an email, along with a 3D preview of the finished build, once the build completes.
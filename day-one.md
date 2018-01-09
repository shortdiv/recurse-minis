# Day One: 

## Background
Over the last couple of months, I've been working with WebGL based libraries for data visualization, primarily for creating and visualizing maps on the web. Working at a high, abstracted level, I've been able to get visualizations and prototypes up and running without much fuss and with a few straightforward lines of code. The more I worked on these libraries however, the more I realized how much I leaned on their optimizations and implementations of GL without myself understanding what was happening under the hood. Though the APIs and libraries I used helped me get the job done, I found myself wanting to create my own implementations and methods without having to rely on and pull in other dependencies in order to accomplish tasks. Therein the idea of diving deep into out WebGL was born. Considering how relevant learning WebGL was to my current passion projects and how different it was to my current fulltime responsibilities as a frontend developer, I decided the mini batch would be the perfect opportunity for me to work on WebGL. 

## Getting Started, pre-batch.
As someone coming from a web development background, graphics programming seemed like a deep abyss and I had no idea where to even begin. Thankfully, in my initial forays into researching WebGL, I stumbled on two resources that helped me navigate the world of WebGL as a newbie. The first was The Book of Shaders, which is a step-by-step guide through the complex universe of Shaders. The book is not quite complete, but it provided enough for me to grok the basics of WebGL. The other resource was Shader School, a tutorial in the form of an npm module that you can run in your browser. It has a series of exercises you can step through and serves as a gentle guide through data types, conditionals and functions in WebGL. I spent a week pouring through these resources as much as I possibly could in preparation for my week at RC. 

## Day One
Day One at RC was not as intimidating as I had made it out to be. Many of us in the mini batch felt that we had very little time to accomplish a lot but we were confident that we would regardless gain a lot from our time here. Despite the little time, I spent Day One trying to get to know as many RC-ers as possible and to hear about the various projects they were all working on. As expected, I have added many new projects to my ever increasing backlog of side projects and have made plans to pair with many RC-ers on their projects to get a taste of something I would otherwise not have worked on or even known about at all. The enthusiasm and vigor at RC is incredibly infectious and I couldn't be happier to be here soaking it all in. 

I spent the better half of the day pairing with a fellow mini batch mate on writing basic webgl code that runs in the browser and that proved a challenging, yet rewarding task. We read about and discussed the concept of [uniforms in WebGL](http://thebookofshaders.com/03/) and tried to write code to draw a triangle on a screen. A huge challenge we found as we were trying to write WebGL code was trying to bridge the gap between writing GLSL (GL Shader Language) and viewing it in the browser. Because we didn't want to lean on frameworks or editors for this, we took a detour and ran through a running pen in codepen from the [WebGL Fundamentals website](https://webglfundamentals.org/webgl/lessons/webgl-fundamentals.html) to better understand how to write GLSL in the browser without having to compile code.

## Things Learned

- Data Types in WebGL 
  - Uniforms
  - Varyings
  - Textures
  - Attributes and Buffers

- Shaders
  - Vertex Shaders
  - Fragment Shaders

- Canvas
  - `canvas.getContext("webgl")` is the key to the wonderful world of WebGL
  - WebGL follows the spec of OpenGL mostly, so the names of methods carries over
  - Resizing the canvas is pretty easy (canvas.height vs canvas.style.height)
  - 


## Things to Learn (that I know of)
- Array Buffers
- Textures
- Geometry in WebGL
- Shapes in WebGL (don't think I fully understand this yet)
- RequestAnimationFrame & WebGL; how do they work together?





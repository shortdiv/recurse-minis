# Day Two:

It's only Day Two but I'm already feeling the pressure of how short of a time I have at RC. My goal for the day was to work on understanding how data gets passed into a shader but I ended up spending my time creating a local build of WebGL up and running so I could take advantage of  the WebGL chrome debugger moving forward. Though this was a bit of a detour from my original goal, it proved useful because the WebGL debugger let me visualize the various pieces of my shader. Via the debugger, I could see contents of my array buffer and how JS had handled my floats. LOL. 

[0, 0, 0, 0.5, 0.7, 0] -> [0, 0, 0, 0.5, 0.699999988079071, 0]

I also spent a good part of the morning reworking my webGL code and grouping the various gl calls into distinct functions so I could have a clearer sense of the order of operations in WebGL. The hope in pursuing this task was to create a standardized JS file, that was independent of the GLSL code so that I can theoretically focus on writing GLSL code without having to futz with how JS pulls it into the canvas context. Although I'm still far from creating standardized JS for WebGL code, I was able to concretize my understanding of the rendering pipeline in WebGL. 

The rest of my day was spent pairing, I paired on some MapboxGL code, React code and some WebGL code and talked extensively about the differences between Vue and React. 

## Things Learned
- WebGL Render Pipeline
    - createShader => shaderSource => compileShader
    - createProgram => attachShader => detachShader
    - linkProgram => useProgram 
    - deleteShader => deleteProgram

## Things to Learn (that I know of)
- Array Buffers
- Primitive Types (triangle, lines, squares)

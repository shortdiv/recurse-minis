# Day Four:
Day Four was a little frustrating, progress was slow. I worked through transformations and that took a bit of work to wrap my head around. It's been a while since I've done linear algebra so I needed to refresh my knowledge on the various formulas for translate, rotate etc and to figure out the matrix math required to perform those operations. I managed to figure it out however and realized that in WebGL matrices are column majors not row majors, which is weird.

Row Major
1, 0, 0, Tx
0, 1, 0, Ty
0, 0, 1, 0
0, 0, 0, 1  

Column Major (WebGL Uses this)
1, 0, 0, 0
0, 1, 0, 0
0, 0, 1, 0
Tx, Ty, 0, 1

## Things Learned
- Transformations in WebGL 
- WebGL matrices are column majors not row majors 
- The difference between GLSL and the WebGL API

## Things to Learn (that I know of)
- Drawing a circle in WebGL
- Animating a shape across a screen
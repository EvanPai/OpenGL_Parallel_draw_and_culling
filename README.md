# OpenGL_Parallel_draw_and_culling
- use OpenGL compute shader to draw those grasses in parallel. 
- use frustum culling to reduce huge amount of grasses that the user cannot see, and only draw the grasses that can be viewed.
- Blinn-Phong shading applied on the grasses and the blue ball. 
- the blue ball will eat the grasses that it walked through.
- by using techniques above, the program can still maintain high FPS even when there are a lot of instances in the scene.
usage  :  
open the Rendering_Framework.sln and run it in Visual Studio.

image  :  
![image](https://user-images.githubusercontent.com/84391176/230564197-3ff533ea-5fda-490e-a2d7-6d1efa082d42.png)

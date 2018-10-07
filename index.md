---
title: homepage
---
Hello! 

I am Charles Giessen, a Software Engineer focused on systems programming and computer graphics. 
Currently I'm a senior Computer Science student at the University of Tulsa. 
I enjoy getting into the nitty-gritty details, high performance software, and making code fast.


## Contact info

Email: cdgiessen@gmail.com

[Resume](Charles_Giessen_Resumes.pdf)

[Github](https://github.com/cdgiessen)

[LinkedIn](https://www.linkedin.com/in/charles-giessen-22976411a/)

## Programming Projects

### Vulkan Game Engine​ 

Designed around the new Vulkan graphics API. C++17. A testing ground for learning software techniques, game engine design, and exploring solutions for engineering problems.
	
##### Major Features:
* Terrain Renderer​: Heightmap based with automatic level of detail adjustment using a Quadtree and Memory pool for quick allocation.

* Procedural Noise Texture Generator​: Lets users create noise textures in a visual node graph editor and uses SIMD acceleration for calculation.

* Cross platform - CMake based, with both Windows and Linux Support​. Tested with both gcc and msvc.

* Multitasking System​, (WIP) Thread pool based tasking system that enables task based multithreading of various jobs.

* Frame Graph​, (WIP) Abstracts all rendering operations and resources into a single graph, enabling global reasoning about how a frame is rendered.

* Physically based rendering, Uses the Cook-Torrance BRDF and currently only implements albedo, roughness, metalness, with normal mapping.

-- [Source](https://github.com/cdgiessen/VulkanRenderer) --

##### Screenshots

Example Landscape
 ![Lanscape Example](/images/Siggraph_lanscape2.jpg)

Terrain Level of Detail
 ![Terrain LOD](/images/siggraph_terrain_lod.jpg)

PBR showcase
 ![PBR](/images/PBR_materials.jpg)

### Pascal Compiler
Project for the Compiler Construction course. C++17

Compiles a Pascal dialect, not standard Pascal

The parsing method employed is Recusive Descent parsing.

Tokenizer is working; Parsing, AST generation, and LLVM integration for code gen in progress.

-- [Source](/https://github.com/cdgiessen/pascal-compiler) --
 
### Orange Sherbet Game Engine
Cumulative project for the Game Engine Design course. C++11 and is OpenGL 4.0 based.

##### Features
 * Phong Shading​, with diffure and specular texture sampling.
 * Point, Direction, and Spot Lighting​, dynamic lighting of environment
 * Custom Model Loading​, using Wavefront Obj’s with optional normal recalculation
 * Transform Hierarchy​, Position, Rotation, and Scaling supported.

-- [Source](https://github.com/cdgiessen/OrangeSherbetGameEngine) -- 
 
Screenshot of exmaple scene
 ![OSGE](/images/OSGE_lighting.jpg)


### Charles Math Library
Written in conjunction with the Orange Sherbert Game Engine

Simple math library built for 3d graphics

Vectors 2,3,4, Matrix 3x3,4x4, & Quaternions

Written in C++

-- [Source](https://github.com/cdgiessen/cml) --
 
### USGS Survey Data FPS Viewer
Loads and lets users walk around a USGS GridFloat data file

Sample data is of Mt. Saint Helens

Uses OpenGL 3.3, GLFW, and GLEW

Written in C++11

-- [Source](https://github.com/cdgiessen/TerrainExplorer) --
 
 ![FPS cinematic](/images/TerrainFPS_cinematic.jpg)

 ![FPS overhead](/images/TerrainFPS_overhead.jpg)

### Project Luna
Unity 3d based RTS style colony builder

Procedural created lunar surface in RollerCoaster Tycoon 2 style

-- [Source](https://github.com/cdgiessen/project-luna) --

 ![Project Luna](/images/ImportedModels.jpg)

 ![Project Luna](/images/ProjectLuna_RC2_style.jpg)

### Various High Performance Computing projects
MPI, OpenMP, pthreads

Simple projects, served to learn basic API concepts and hpc programming practices.

Developed to run on the 100 node Tandy Supercomputer (no longer in operation) 

-- [Source](https://github.com/cdgiessen/HighPerformanceProgrammingProjects) --

### USGS Survey Data Visualizer
Loads and displays a USGS Survey data file

Lets the viewer orbit the camera around the file

Able to change the color and gradient based on the height

C++, fixed function OpenGL using FreeGLUT

-- [Source](https://github.com/cdgiessen/FreeGlut-Terrain-Visualizer) --

 ![FreeGlutViewer](/images/FreeGlutViewer.png)

### Icosohedral Subdivision Sphere

Automatic subdivision of icosoheron sphere

Walkable planet with heightmap and texture mapping 

Written in C# & Unity3d

-- [Source](https://github.com/cdgiessen/InnerEarth) --

 ![Icosohedron](/images/SubdividingIcosohedron.jpg)
 
 * Youtube Video of WIP version [Link](https://youtu.be/gXtS96FRIDQ)

### Contour Line Visualizer
Creates a contour map of a USGS GridFloat data file

Example data is of Mt. Saint Helens

Written in C++

-- [Source](https://github.com/cdgiessen/ContourLines) --

 ![Contour Lines](/images/contour_lines.png)


### Koch Snowflake
Draws a Koch Snowflake fractal

Written in C++

-- [Source](https://github.com/cdgiessen/KochSnowflake) --

![Snowflake](/images/KochSnowflake.png)

### PollPoll: Hackathon Project
Scrapes webdata of congresional voting for comparison

Written in Python
 
-- [Source](https://github.com/cdgiessen/pollpoll) -- 
 
## Non-Programming Work


### 3d Modeling 
 Comfortable working in Maya 2017 and Blender 2.7. 

 ![Sewing](/images/maya_sewing_render.jpg)

 ![Train](/images/Maya_train_render.jpg)




 


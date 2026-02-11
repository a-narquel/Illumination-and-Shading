# Illumination and Shading



## Overview
Interactive WebGL application demonstrating Phong and Gouraud shading with multiple configurable light sources, camera controls, and a full-browser scene.


## Objective
This project creates a 3D scene rendered with WebGL, allowing objects to be viewed under different light sources with Phong or Gouraud shading. Users can interactively manipulate the camera, lights, and materials through a GUI.  

**Scene composition:**
- **Platform:** 10 x 0.5 x 10 parallelepiped, aligned with world axes, upper face at y = 0.  
- **Objects:** 4 primitives (cube, torus, cylinder, bunny) placed in quadrants on top of the platform.  
- **Lights:** 3 user-configurable lights (point, directional, spotlight).  
- **Camera:** Full-browser perspective projection with adjustable position and viewing volume.  


## Features
- Switch between **Phong (fragment)** and **Gouraud (vertex)** shading.  
- Enable/disable **backface culling** and **depth test**.  
- Fully configurable **camera** via GUI, including eye, at, up, fovy, near, far.  
- Adjustable **light properties**: type, position, intensities, axis, aperture, cutoff, on/off.  
- Bunny material is fully editable via GUI (Ka, Kd, Ks, shininess).  
- Supports multiple lights with minimal code changes.  
- Scene resizes dynamically with the browser window.  




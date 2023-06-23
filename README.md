# Unity-Meta-Quest-Template
Unity template project optimised for Meta Quest devices.
Current Project Version Unity 2022.3.2f

Changes from default Unity project with Android build target:  

Packages:  
Installed XR Plug-in Management. Targets Quest, Quest 2, Quest Pro  
Installed OpenXR Plugin  
Installed Oculus XR Plugin  
Installed XR Interaction Toolkit version 2.4.0
Installed XR Hands 1.2.1
Installed Meta OpenXR Feature 0.1.1
URP Samples imported (includes useful blob shadow shader)  

Quality Settings:  
Custom Quality profiles  for Quest, Quest 2, Quest Pro, Quest 3. (Default Quest 2)  
Vsync disabled  
Anisotropic Textures set to Per Texture.  
Shadowmask Mode set to Shadowmask  
LOD Bias set to 0.7  
Skin Weights set to 2 Bones  

Player Settings:  
Auto Graphics API disabled, set to OpenGL ES 3.0  
Texture Compression format set to ATSC  
Minimum API Level set to Android 10.0 (API Level 29)  
Lightmap encoding set to High Quality  
HDR Cubemap encoding set to High Quality  
Use Incremental GC enabled 
Scripting Backend set to IL2CPP  
IL2CPP Code generation set to Faster (smaller) builds *Change this to Faster runtime for release build  
Target Architecture set to Arm64  
Active Input Handling set to Both  
Optimize Mesh Data enabled   


Physics Settings:  
Reuse Collision Callbacks enabled  
Default Max Angular Speed set to 7 
Enabled Improved Patch Friction 

Time Settings:  
Maximum Allowed Timestep set to 0.0138 (for 72 Hz)  

URP Renderer Settings:  
Shadows – Transparent Receive Shadows disabled   

URP Pipeline asset settings for Quest 2: (minor differences for Quest 1 and Quest Pro)  
Disable Terrain Holes  
Main Light – Cast Shadows disabled  
Additional Lights set to Per Pixel  

Notes:  
The project is set up to have to realtime shadows and no additional lights.
Adjust URP shadow settings according to the needs of your game/app.   
For release builds enable Low Overhead Mode under Oculus XR Plug-in Management options.  

Cornell Box model taken form Sketchfab - Cornell Box- Original - Download Free 3D model by t-ly (@t-ly) https://sketchfab.com/3d-models/cornell-box-original-0d18de8d108c4c9cab1a4405698cc6b6

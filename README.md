# ShadowBaker
 Simple tool for baking blob shadow textures in Unity!
 
 [Demo GIF](https://gyazo.com/5ce594c8f29729b1841618a4561612d3)
 
# Usage
 Open the Shadow Baker window from the Tools section of the top layout.
 
# Parameters:
 -Target
 
 The target Transform of the object that you want to create a shadow.
 
 -Texture Size
 
 Shadow texture resolution. Higher means more quality but a larger file size.
 
 -Orthographic Scale
 
 Scale of the camera used for rendering the shadow. 
 Increase it if the shadow appears black or decrease it if it appears too small or white.
 
 -Shadow Blur
 
 Gaussian blur effect for the shadow Texture
 
 # Output
 The shadow output will be generated at Assets/Shadows/(ObjectName)(ObjectID).png
 
 # Extra
 This asset also includes a shadow projector shader and a projector falloff texture.


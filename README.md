# Unity Full Dome Camera
### If you are using Default Graphic Pipeline, Check this version of my camera: <a href="https://github.com/mrarashiyan/Unity-Full-Dome-Camera">LINK</a>

This project is a simple Full Dome Camera created by me for Ferdowsi University Planetarium (<a href="www.fum360.com">FUM360</a>)
We decided to share this project to help our friends in other planetarium to make new contents in Unity3d Engine.
Develope your own content and share it with us!

Unlike regular Dome cameras, We are not using 6 or 4 cameras to make dome camera. In this project we are using a Dome mesh with a Reflective Material to reflect everything on a Dome surface.
It will help you to increase performance 4 times better!

## How to use
There is a Main Camera under "Spherical Camera" prefab. you can use it as an Output camera to change output display, Record your scene, or send it to external applications with <a href="https://github.com/sloopidoopi/Spout4Unity">SPOUT</a> technology. 
Also I've forwarded camera output to a Renderer Texture in "EngariumSphericalCamera > _Textures >  Camera Render Texture". If you seed a simple output camera for one projector planetariums, remove it!
A "Dummy Camera" is created under "Spherical Camera" prefab. Remove it for better performance.

## Cusomize Textures
If you need to change size of Output Texture, Just change Texture size on "Camera Render Texture"
If you want to add PostProcessEffects, add it to Main Camera

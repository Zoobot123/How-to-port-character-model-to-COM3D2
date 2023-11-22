# How-to-port-character-model-to-COM3D2

  This guide won’t go over every detail but only provides the fastest and easiest way to port your model to COM3D2 while still keeping the quality. Most of the written steps are just to give you an idea of what going on, watch the video under each tutorial for the full progress. There is also a workflow video with no comment that shows all tutorials.
  
Used term:
- COM: the game COM3D2
- Your model: the model you want to port to COM 
- COM body: the LOhighpoly body provided in the .blend flies inside the Zoobot's modding tools
(Really need to remember “Your model” and “COM body”, they will be mentioned a lot in this guide)
- Scripts: Many Python scripts are used to automate some progress. Written and saved inside Zoobot workflow.blend 
- The temp folder: the temp folder contains temporary menu files provided inside Zoobot's modding tools

Requirement:
- Zoobot's modding tools(including blend files, and mass rename script): [link](https://github.com/Zoobot123/How-to-port-character-model-to-COM3D2/releases/tag/tutorial)
- NKK mods(mostly for the hair menus): [link](https://mega.nz/folder/06ViRZJL#fB-zihiNHKWzQyftc6XMug)
- Converting tools (to convert .png to .tex, and .txt to .menu): [link](https://mega.nz/file/ZrsRyZAb#WNfT2tTk7s5Je6h8I5qPIFX5JjxwtrfE4DWm0wKkoHw)
- Blender 3.4 with latest Blender-CM3D2-Converter install: [link](https://github.com/luvoid/Blender-CM3D2-Converter)
- Dynabone edit plugin(for edit collider and physic): [link](https://ux.getuploader.com/trzr_tool/download/25)
- PC with Python


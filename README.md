# project_base
Prazan projekat sa pratećim bibliotekama koje koristimo na času. 

# Uputstvo
1. `git clone https://github.com/matf-racunarska-grafika/project_base.git`
2. CLion -> Open -> path/to/my/project_base
3. Main se nalazi u src/main.cpp
4. Cpp fajlovi idu u src folder
5. Zaglavlja (h i hpp) fajlovi idu u include
6. Šejderi idu u folder shaders. `Vertex shader` ima ekstenziju `.vs`, `fragment shader` ima ekstenziju `.fs`
7. ALT+SHIFT+F10 -> project_base -> run

# The project contains:
1. Models: treasurechest, fish
2. Textures: skybox - aqua4, atlantis.jpg
3. Lighting: directional, spot, point light - Blinn-Phong lighting model
4. Shaders: skybox, 2.model_lighting, bloom, blur
5. Skybox cubemap: cube that encompases the entire scene, contains 6 images
6. Face culling: if a side on an object cannot be seen, don't render it
7. HDR: High dynamic range - large range of details are visible based on the combined exposure levels
8. Bloom: Bloom gives all brightly lit regions of a scene a glow-like effect.
9. By pressing:
	B - activate/deactivate Blinn-Phong lighting model
	V - spot light on/off
	Arrow keys - move the ring forwards, backwards, left and right


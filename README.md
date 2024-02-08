# SuperSimpleTerrainShader
A super simple terrain shadergraph for unity's terrain system

![Terrain01](https://github.com/MichaelEGA/SuperSimpleTerrainShader/assets/67586167/10090e00-ff65-4ac9-9cb3-7d472484bb1e)

![Terrain02](https://github.com/MichaelEGA/SuperSimpleTerrainShader/assets/67586167/7ceccfc8-ad03-465d-b2aa-d84cebe9978d)

![Terrain03](https://github.com/MichaelEGA/SuperSimpleTerrainShader/assets/67586167/8c99829d-9a0d-4b92-a19c-3db5a39d452a)

Features:
- Made to be used with the unity terrain system.
- Blends by height and angle to make a natural looking terrain
- Six layers: Water, Sand, Grass, Rock, Snow, Cliffs
- Includes normal map slots to make a realistic looking terrain
- Includes metallic and smoothness settings for each different layer
- Cliffs use a triplanar node to prevent texture warping
- Made using only Unity's default nodes, nothing fancy, it just works.

How to use:
1. Make a material with the shader
2. Set the material to the terrain in the terrain settings
3. The height value is determined by the height of your terrain in the terrain settingss i.e. if your terrain is 5000 units high you would set the values to something like water 500, sand 1000, grass 2000, rock 3000, snow 4000, etc

Credits
- I improved upon the terrain shader created by Snubber here: https://github.com/jacklaplante/Unity-URP-Terrain-Shader

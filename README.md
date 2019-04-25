# Randomized Tiling Materials
This is a small example of my tiling material function and how it can be used.
Compatible with Unreal Engine Version 4.22.0.

There are two material functions. One is responsible for creating the coordinate offsets, the other is used for sampling textures with the generated offsets and blending them.

The functions are set up for two RGBA Textures with Color(RGB) and Roughness(A) packed in one and Normal(RG), Ambient Occlusion(B) and Height(A) in the other. The "TiledHeightBlend" function can be modified for different Texture set ups.

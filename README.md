# Randomized Tiling Materials
This is a small example of my tiling materials and how they can be used.
Compatible with Unreal Engine Version 4.23.1.

Height based blending:
There are two material functions. One is responsible for creating the coordinate offsets, the other is used for sampling textures with the generated offsets and blending them.

The functions are set up for two RGBA Textures with Color(RGB) and Roughness(A) packed in one and Normal(RG), Ambient Occlusion(B) and Height(A) in the other. The "TiledHeightBlend" function can be modified for different Texture set ups.

Temporal blending:
There is now a second variation of this material with TAA blending which is much easier to set up, please take a look at the TilingTemporalExample material. Expanding this with more texture sampler nodes should be very straightforward and will only require a single texture fetch per sampler.
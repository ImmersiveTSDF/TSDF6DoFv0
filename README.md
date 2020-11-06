# View-dependent Texture Mapping for TSDF Scene Model

We are constantly updating at this time to time.

## UV Map Lookup Table

Our initial version of the UV map lookup table (256 pairs of Marching Cube topology and UV Map) is presented below.

<p align="center">
  <img src="images/mcuvlut.png" width=700 />
</p>

## Waste-rate of Texture Space

On average, 12.81% of texture space was not used for conventional UV texture maps, and 1.94% of space was not used for our texture maps.

<p align="center">
  <img src="images/wasteratio.png" width=700 />
</p>

## View-Dependent Texture Synthesis

<p float="left" align="center">
  <img src="images/syn_metals5x5.png" width="300" />
  <em>image_caption</em>
  <img src="images/syn_showcase5x5.png" width="300" />
  <em>image_caption</em>
</p>

<p float="left" align="center">
  <img src="images/syn_glasses5x5.png" width="300" />
  <em>image_caption</em>
  <img src="images/syn_mirror5x5.png" width="300" />
  <em>image_caption</em>
</p>

# torch-texture-synthesis


This is a Torch implementation of a texture-synthesis algorithm.
Given an input texture patch, the algorithm generates a larger version of the same texture.


## Usage
Texture synthesis is implemented in the script `synthesis.lua`. The following command line options are available:
* `-source`: Path to the source image.
* `-output_file`: Path where the output should be written.
* `-height`: Height of the output file, in pixels.
* `-width`: Width of the output file, in pixels.
* `-k`: Kernel size; must be an odd integer.
* `-gpu`: Which GPU to use. Setting `gpu >= 0` will run in GPU mode, and setting `gpu < 0` will run in CPU-only mode.
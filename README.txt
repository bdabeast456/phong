Names: Austin W Shyu (cs184-dv); Brandon M Pearl (cs184-au)
Platform: OSX
Code located at: example_01.cpp
README Submitted by Brandon M Pearl, Code Submitted by Austin W Shyu

Kd values go from 0 to 1
RGB values go from 0 to max_float

Extra features:
-TOON SHADING:
    Use the flag '-toon' to create a toon-like shading on the surface
    Example command: -ka 0.3 0.3 0.3 -kd 1 1 1 -ks 1 1 1 -sp 64 -pl 2 2 2 1 0 0 -pl -2 2 2 0 1 0 -pl 0 -2 2 0 0 1 -toon
    (try getting rid of the -toon flag to see what it looked like before the toon shading!)

-INVERTED COLORS:
    Use the flag '-invert' to create a color inverted image 
    Example command: -ka 0.3 0.3 0.3 -kd 1 1 1 -ks 1 1 1 -sp 256 -pl 2 2 2 1 0 1 -pl -2 2 2 0 1 0 -invert
    (try getting rid of the -invert flag to see what it looked like before the inversion!)

-GREYSCALING:
    Use the flag '-greyscale' to greyscale the shading. greyscale takes 0 or 1. 
        -1 averages the RGB color channels
        -0 spreads the maximum across the 3 RGB values.
    Example command: -ka 0.3 0.3 0.3 -kd 1 1 1 -ks 1 1 1 -sp 64 -pl 2 2 2 1 0 0  -pl 0 -2 2 0 0 1 -greyscale 1
    (try getting rid of the -greyscale flag to see what it looked like before the greyscaling!)

Caution: Make sure to enter the correct number of arguments!
         Also, character strings entered in place of floats will be parsed to 0.
                                     

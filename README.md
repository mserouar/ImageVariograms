# ImageVariograms

The variogram is a tool commonly used in geostatistics. It allows the spatial variability within an image to be accounted for through feature structures and variations 

This tool would make it possible to know the size of elements in the image in pixels, failing to know the Ground Sampling Distance (the physical distance on the ground between the centers of two neighboring pixels in the image) in cm or m, depending on several parameters including the lens, the focal length and thus different for each dataset.  


**This module has been made thanks to the Scikit-GStat library on Python** (*Mirko Mälicke, & Helge David Schneider. (2019, November 7). Scikit-GStat 0.2.6: A scipy flavoured geostatistical analysis toolbox written in Python.*).

In the example, leaves are estimated at 26 pixels. Then, we reduce the image (with a factor 2) and variogram estimate the leaves at 13 pixels.


Adaptive Composite Map Projection (Lite)
=======

Based on...
1. The Adaptive Composite Map Projection as described and demonstrated
by Berhard Jenny - http://cartography.oregonstate.edu/pdf/2012_Jenny_AdaptiveCompositeMapProjections.pdf

2. The d3.v2 implementation of the Adaptive Composite Map Projection
by Gabor Angeli & Sukolsak Sakshuwong - https://github.com/gangeli/d3/blob/master/src/geo/composite.js

3. Zoom & pan code from Mike Bostock - http://mbostock.github.io/d3/talk/20111018/azimuthal.html

What this interpretation seeks to accomplish:
1. Utilize the Adaptive Composite Map Projection within d3.v3
2. Simplify/optomize the description and implementation for fast performance and aesthetics
    - i.e. sacrifice some accuracy for simplicity

What this interpretation fails to accomplish:
1. Does not implement the ACMP as a d3 projection for reusability, mostly due to 
  lack of understanding
2. Smooth performance across a range of devices
3. Integration with map tiles at small scales
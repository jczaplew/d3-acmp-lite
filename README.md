Adaptive Composite Map Projection (Lite)
=======

SVG demo - http://bl.ocks.org/jczaplew/6603431

Canvas demo - http://bl.ocks.org/jczaplew/6798471

Based on:
1. The Adaptive Composite Map Projection as [described](http://cartography.oregonstate.edu/pdf/2012_Jenny_AdaptiveCompositeMapProjections.pdf) and [demonstrated](http://cartography.oregonstate.edu/demos/CompositeMapProjection/) by Berhard Jenny
2. The [d3.v2 implementation](https://github.com/gangeli/d3/blob/master/src/geo/composite.js) of the Adaptive Composite Map Projection by Gabor Angeli & Sukolsak Sakshuwong
3. [Zoom & pan code](http://mbostock.github.io/d3/talk/20111018/azimuthal.html) from Mike Bostock

Goals:
* Utilize the Adaptive Composite Map Projection within d3.v3
* Simplify/optomize the description and implementation for fast performance and aesthetics
    - i.e. sacrifice some accuracy for simplicity
* Smooth performance on mobile devices

Current shortcomings: 
* Does not implement the ACMP as a d3 projection for reusability/integration
* Smooth performance across a range of devices
* Integration with map tiles at large scales

License:
CC0 1.0 Universal
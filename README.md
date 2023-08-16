# complete
My place to keep track of my repositories, and store project notes. 


[cornerContour](https://github.com/nanjizal/cornerContour) this project works with recent Haxe and provides some vector drawing for graphics using WebGL or OpenGL using lots of triangle. It has support for Ceramic, Heaps, OpenFL, NME, Lime, Flixel as well as basics for js WebGL directly with mouse support and triangle hit test. Can take SVG paths, allows turtle style commands or just drawing ones.
[trilateral3](https://github.com/nanjizal/trilateral3) this adds to cornercontour allowing drawing 2D within 3D WebGL/OpenGL.
trilateral,trilateralXtra, trilateralBazzar - contain aspects of an older project which may have more features.

[pixelImageXY](https://github.com/nanjizal/pixelImageXY) this project provides an image that can be drawn on and then rendered in Canvas or via the many haxe toolkits.
- Have been looking into XML format, which is well structured but incompletly implemented, it maybe removed as it is quite complex and aspect like fine edge options are complex.
- TODO: Latest concept will be to provide an abstract for aspect of a pixelImage like 'transformation' or 'fill', allowing clean api.
pixelImage.transform.flipX();
pixelImage.fill.triangle(...);
so transform getter in this case will return an abstact type containing the transform methods currently in the large pixelImage, hopefully this will enable a simple api.
pixelImage is an older version it maybe more complete in some aspects.

[hxDaedalus](http://github.com/hxDaedalus) The project can convert images or object shapes to triangulated pathfinding, it is a port of an as3 project that I have worked on with another haxe developer. It supports cornerCanvas and all haxe game engines.

[jigsawX](http://github.com/nanjizal/jigsawX) just provides a customisable jigsaw engine, so there is a swing, openfl/nme version ( the old flash one has WebCam ) and there is a Kha version that allows rotation of the pieces.

[hxRectPack2D](http://github.com/nanjizal/hxRectPack2D) is a port of some code for creating spritesheets, starting to merge with pixelimageXY.

[hxSpiro](http://github.com/nanjizal/hxSpiro) a port of Raph Levin spiro curve algorithm's unfortunately it is GPL and so not so useful, do have a more recent version that I wanted to release as MIT but due to an objection I removed.

[xGLfonts](http://github.com/nanjizal/xGLfonts) this is partial port of a webgl engine to help with rendering sdf fonts, it is a project keen to do more work on soon. TODO.

TODO: go through my repo and add detail of other projects, but this is a start atleast.

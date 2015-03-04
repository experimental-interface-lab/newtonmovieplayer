Newton Movie Player 2.0
=======================

This repository hosts the Mac Newton Toolkit (NTK) source code for Newton Movie Player 2.0. Originally developed by Lee Moon around 1997 (and later extended by Brad Tober around 2001), this code provides a template for creating Newton apps that play short video clips. In essence, Newton Movie Player plays an audio track while simultaneously progressing through a sequence of image frames.

This demonstration plays the opening titles to NBC's [Providence](http://en.wikipedia.org/wiki/Providence_%28TV_series%29).

You will need an MP2x00 to play NMP 2.0 movie packages.


Files
-----

- **providence.rsrc**: Holds image and audio content. All but 3 PICT resources are movie image frames, the others are interface elements.
- **nmp_data**: Loads image frames into an array and audio into a constant.
- **nmp_layout**: Mac NTK layout file. Of note is the value for sampleticks in the PlayButton buttonClickScript: this corresponds to the length of your movie (1 second = 60 Newton ticks).
- **nmp_project**: Mac NTK project file.
- **nmp_demo.pkg**: A built package, ready for installation on your MP2x00.


Helpful (?) Tools
-----------------

- [Newton Toolkit 1.6.4](http://www.unna.org/view.php?/apple/development/NTK/macntk) (with main and build heap set to ~16000 KB each)
- [ResEdit 2.1.3](http://mac.org/utilities/resedit/)
- [SheepShaver](http://www.emaculation.com/doku.php/sheepshaver) (running Mac OS 9.0.4)
- [Einstein Platform](https://code.google.com/p/einstein/) (although NMP will not work in Einstein due to emulation limitations)
- [Newton Movie Converter](http://www.unna.org/unna/macos/NewtonMovieConverterRC3a.sit) (originally by Eric Schneck; works, but poor quality video)
- [Newton Movie Converter 2013.1](http://www.unna.org/unnasearch/entry.php?pkey=12969) (an updated version by Vladislav Korotnev, but buggy)
- [Original NMP 2.0 "Providence" demos](http://www.unna.org/view.php?/movies/Providence) (by Brad Tober)
- [NMP 0.91 demo](http://www.unna.org/view.php?/utilites/graphics-movies/NewtonMoviePlayer0.91Demo) (by Lee Moon)


Support
-------

This code is provided as a courtesy to the Newton community with no warranties or guarantees whatsoever. Please do not contact me regarding support.


License
-------

Newton Movie Player 2.0 is licensed under The MIT License.

Copyright (c) 2001, 2015
Experimental Interface Lab <http://www.experimentalinterfacelab.org>
Brad Tober <http://www.bradtober.com>

Copyright (c) 1997
Lee Moon
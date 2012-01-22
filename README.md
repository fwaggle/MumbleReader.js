Mumble-CVP.js

This is a fork of the Javascript front-end portion of Pimmitje's MumbleReader[1]
script, with a goal towards improving the readability and usability for novice 
users. I don't pretend to be great at JS and I'm near clueless with jQuery,
but I think that at least for my purposes this is a more useful starting point
than Pimmitje's reference code - I hope someone else finds it useful too.

I've disabled the tooltip feature by default, so that users can make use of
Google's code libraries to load jQuery (they don't host qtip). If you want to
enable tooltips, you'll need to host your own qtip, and load that along with
jQuery, then settooltip(true);.

Most of the included stylesheet should be reasonably self-explanatory, and you
should hopefully have little trouble skinning it to fit any website. If you wish
to change the icons, upload the modified icon files to a web host and set the
imgpath like so:

  mr.setimgpath('http://fwaggle.github.com/mumble-cvp.js/');

As with the original MumbleReader scripts and related files, it is released 
under the terms of the GPL.

1) http://code.google.com/p/mumblereader/

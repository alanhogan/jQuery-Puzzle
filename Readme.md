jQuery Puzzle
===

Essentially the same sliding puzzle game extension that [Ben Nadel](http://www.bennadel.com/blog/1009-jQuery-Demo-Creating-A-Sliding-Image-Puzzle-Plug-In.htm) created back in 2007. Obviously it belongs on GitHub!

Usage is simple. You only need one image from which the puzzle will be created.

    $('.puzzle-container').puzzle(100);
    // where .puzzle-container is an element that contains an image (<img>)
    // and 100 is the size, in pixels, of the puzzle pieces to create.
    // (It should divide fairly cleanly into the height and width.)

You should also style the container something like this:

    .puzzle-container {
        width: 300px; /* width of puzzle image */
        border: 1px solid #222; /* if desired */
    }

For more information, please see [Ben's original page for this plugin][1].

### License

Public domain

### Author

Originally by [Ben Nadel](http://www.bennadel.com/).
This version maintained by [Alan Hogan](http://alanhogan.com/).

### Changelog

Differences from version available on Ben's site as of August 30, 2011:

- Fixed syntax error
- Omitted styles applied to the container

[1]: http://www.bennadel.com/blog/1009-jQuery-Demo-Creating-A-Sliding-Image-Puzzle-Plug-In.htm


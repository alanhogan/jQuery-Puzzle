jQuery Puzzle
===

### Demo

**[Demo here](http://jsfiddle.net/alanhogan/tRmkx/)**.

### Overview & Usage

Essentially the same sliding puzzle game jQuery plugin that [Ben Nadel created][1] back in 2007. Obviously it belongs on GitHub!

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

### Strengths

- Unlike similar plugins, you can move whole rows/columns of pieces with one click.
- Requires no more than one image.
- Every initial (shuffled) position is solvable. (If you "picked up" the pieces and placed them randomly, there is a [50% chance the puzzle would be solvable](http://mathworld.wolfram.com/15Puzzle.html).)

### Room for Improvement

- Arrow key support would be nice
- Drag & Drop and/or touch event support would be great
- Currently there is no way to do anything when someone wins

[1]: http://www.bennadel.com/blog/1009-jQuery-Demo-Creating-A-Sliding-Image-Puzzle-Plug-In.htm


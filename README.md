webshot
=======

Utility to create screenshota and thumbnails of web pages

Usage 
-----

webshot [options] URI [out.png]

Options: 
    -h|--height     Height of the browser windown. If not specified
                    the window will be resized in order for HTML
                    document to fit inside

    -w|--width      Width of the window

    -s|--scale      If specified the resulting image will be scaled
                    to have this width, aspect ratio will be preserved
                    (Image::Magick is required)

    -t|--thumb      Filename to save scaled image. If not specified the 
                    output will be replaced

    -v|--verbose    Print error messages from the browser while 
                    processing the page

    --help          This help


Dependencies
------------

- perl
- Gtk3::WebKit
- Image::Magick (if you want thumbnail generation)

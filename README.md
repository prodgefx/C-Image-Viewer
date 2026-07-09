Image Viewer (C + SDL2)

A lightweight SDL2-based image viewer written in C.

    Reads raw RGB pixel data from stdin.

    Parses image dimensions from input.

    Renders pixels directly into an SDL window surface.

    Supports interactive window closing via SDL events.
    
To run:

i) gcc -Wall -Wextra -g -o iv iv.c `sdl2-config --cflags --libs` 
ii) cat <image with extention> | ./iv
